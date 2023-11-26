# Game 1

## The Adventure begins!

Project "Riverside"

Tuesday, 5 October 2021
13:08

A storybook platform for an immersive reading experience, tailored to a branching story.
Interactive choice and consequence supported by sound and visual layout.

Release in EN, RU

Black Screen
========================================

§ StartupScreen
pitch-black, fixed
Loading the Game, startup sequence begins here:
1. black screen with glimmering loading icon
2. <studio name> appears, 3 sec
    3. clears, black screen, roll in Start Menu

    § TransitionScreen
    pitch-black, fixed
    used for transitions
    1. fade out into black screen
    2. black screen with chapter number and quote from the last player's choice
    3. fade out into black screen
    4. roll in <next>


        Start Menu
        ========================================
        Minimalistic, functional design

        Buttons:
        v STORY -> proceeds to Introduction / or Continue
        ▪  a small Pick Save pictorial button next to it; scroll and quill icon
        v SETTINGS -> leads to the Settings page
        v ABOUT US -> leads to Credits
        v WATCH ADS -> leads to the Commercial page
        ▪ a visible text beneath:
        "We've isolated most ads to a separate page.
        Volunteer to watch it, to support our projects. Thank you!"

        Introduction
        First start of the Pick Save slot.
        Intro text from the developers:
        "Thank you; <warning about sounds>; <social network symbols> below"
            fade out
            roll in the Game

            Continue
            Continues the Game from where the Player left off last time
            TransitionScreen

            PickSave
            3 memory slots.
            Each slot contains a name:
            Soul 1 [DD/MM/YY] [hh:mm] (24h format)
            Soul 2 {same}
            Soul 3 {same}

            Click on slot changes its name to green button Begin
            v Begin -> proceeds to Introduction / or Continue

            small round red button with an X symbol inside, next to each slot name
            clicking it makes X symbol disappear, the round shape stretches into pill shape.
            Border highlights in yellow, eraser symbol appears inside.
            v Click on eraser -> border highlights in red, inside the pill button a black progress bar fills for 9 seconds, eraser symbol changes to green "restoration" icon, 9 second countdown -> empty memory slot
            If "restoration" is clicked -> reset, contract pillbox back to initial round button shape with red X symbol, keep slot selected

            At the bottom, there is a rectangular button:
            v Three stripes symbol -> leads to Start Menu

            Settings
            notifications
            left-handed/right-handed

            Credits
            auto-scroll, stops when picks up user's scroll
            fully manual scroll, with inertia
            scroll state resets on return to Start Menu or app exit

            About the studio, photos
            Credits to everyone involved
            Thank you to the player
            Ways to support us

            Player statistics of the Pick Save slot, general statistics across all save slots

            Accessibility settings:
            zoom setting
            text-to-speech


            Text
            ========================================
            ▪ formatting; capitalization, color variation
            ▪ text scrolling
            ▪ MAKE A CHOICE button at the bottom of the text segment
            ▪ highlighting
            ▪ saving quotes to the notebook
            ▪ font; 2-3 variations
            ▪ light or dark theme of choice

            Edge
            ========================================
            ▪ pulling efffect, stretching; deformations; dynamic
            ▪ texture
            ▪ vignette

            Face
            ========================================
            ▪ Particles (sand, reeds, grime, soot)
            ▪ Fade-in/out

            Menu button; siderolling menu, overlay
            ========================================
            ▪ satisfying side-scrolling effect
            ▪ notebook, immediately available:
            ○ personal notepad style
            ○
            ▪ settings and bug report icon
            ▪ purchase full version
            