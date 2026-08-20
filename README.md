# 2025-26-GD-3DGD-ICA-Stephen-C-Kelly



## Abandoned Mall Escape Room



### Overview

This project is a small first-person escape-room experience made in Unreal Engine.



The game is set inside an abandoned shopping mall. The player begins trapped inside the environment and has to explore the area, examine objects and work out how to restore power before they can escape.



The main aim of the project was to create a simple but complete gameplay loop rather than a large level with lots of unfinished systems.



The environment is designed around an abandoned and neglected mall. Dark lighting, broken electrical equipment, old props, locked doors and environmental audio are used to make the space feel empty and run-down.



The basic progression is:

Explore the mall

→ Find and examine the fuse

→ Collect the fuse

→ Use the fuse at the power switch

→ Restore power

→ Use the keypad

→ Enter the correct code

→ Unlock the exit door

→ Walk into the exit area

→ Escape





The project uses three main interaction types:

\* Examine

\* Collect

\* Modify



The Examine system lets the player inspect objects close to the camera, rotate them and read a title and short description.

The Collect system allows the player to take the fuse and store it in the inventory. The fuse is then removed from the world.

The Modify system is used at the power switch. The switch cannot be used properly until the fuse has been collected. Once the fuse is available, the player can restore the power and change the state of the environment.



I also added a custom Substrate material, Niagara sparks for the power system and a short camera sequence that reveals the unlocked exit.





#### How to Play

Input -> Action

W / A / S / D -> Move

Mouse -> Look

E -> Interact

Left Mouse Button -> Collect / save an inspected item

Right Mouse Button / Escape -> Exit inspection

Left Shift -> Sprint

Left Ctrl -> Crouch

Space -> Jump



#### Gameplay

The player begins inside the abandoned mall and cannot immediately leave.



Explore the environment and look for useful objects or clues.

When an interactable object is highlighted, press `E` to interact with it.

Inspectable objects are moved in front of the camera. During examination the camera FOV changes and the object title and description are shown on screen. The player can rotate the inspected object to look at it. The imprtant collectible is the electrical fuse.



When the fuse is collected:

\* it is added to the player's inventory;

\* the fuse is removed from the game world;

\* the player receives feedback confirming that it has been collected.



The player must then find the power switch.

If the player tries to use the power switch without the fuse, the power will not turn on.

After collecting the fuse, interacting with the power switch restores the power.



This causes:

\* the linked keypad to become powered;

\* electrical sound feedback;

\* a Niagara spark effect;

\* a power-restored dialogue line.



Once the power is restored, the keypad can be used.

Enering the correct code unlocks the linked door.

A short camera sequence then shows the player the newly available exit route.

The player can walk through the unlocked area and reach the exit trigger.

Reaching the final area displays the `YOU ESCAPED` screen and ends the experience.



#### Third-Party Audio References



The following sourced audio assets were downloaded from freesound and are listed as creative commons 0.



Room Tone Office 13 by mzui -- https://freesound.org/s/203306/ -- License: Creative Commons 0

Room tone air conditioning equipment 4 by mbezzola -- https://freesound.org/s/652477/ -- License: Creative Commons 0

Lights Flicker on and some electrical Noises.wav by mmaruska -- https://freesound.org/s/232446/ -- License: Creative Commons 0

Long Metal Creak by LoafDV -- https://freesound.org/s/238289/ -- License: Creative Commons 0

Wood Creak.wav by claretcanelon -- https://freesound.org/s/346140/ -- License: Creative Commons 0

Metal\_Hatch\_Small\_Open\_02 by Rudmer\_Rotteveel -- https://freesound.org/s/718444/ -- License: Creative Commons 0

metdoorclose.wav by Mihacappy -- https://freesound.org/s/828133/ -- License: Creative Commons 0

Door Locked 02 by pp87 -- https://freesound.org/s/341302/ -- License: Creative Commons 0

solid wood armoire bottom drawer opening 1 by FOSSarts -- https://freesound.org/s/740188/ -- License: Creative Commons 0

Closed squeaky cabinet door to large wooden dresser - 1 by FOSSarts -- https://freesound.org/s/761919/ -- License: Creative Commons 0

Kill Switch (Large Breaker Switch) .WAV by EchoCinematics -- https://freesound.org/s/131599/ -- License: Creative Commons 0

Mid-High Tone Button Click by wubitog -- https://freesound.org/s/188388/ -- License: Creative Commons 0

Error Signal 2 by Breviceps -- https://freesound.org/s/445978/ -- License: Creative Commons 0

Pickup / Notification Videogame UI Sound by Nomagician -- https://freesound.org/s/833635/ -- License: Creative Commons 0

Suspense Pad and Bass Loop by f-r-a-g-i-l-e -- https://freesound.org/s/594068/ -- License: Creative Commons 0

Steps on concrete, indoor by areniporgen -- https://freesound.org/s/712084/ -- License: Creative Commons 0

Stepping on/crushing small plastic particles by not\_yr -- https://freesound.org/s/669656/ -- License: Creative Commons 0

Stone Steps by Phil25 -- https://freesound.org/s/208103/ -- License: Creative Commons 0



#### Self-Produced Audio



The following asset was recorded for the project:

VO\_PowerRestored



This voice line is triggered after the player successfully restores power.



YOUTUBE SCREENCAST: https://youtu.be/YwcGAnr8LxM

