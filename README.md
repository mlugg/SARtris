# SARtris

Route credit: AMJ
This is a dumb project, but I'm glad it ended up working.
After the introduction of svar arithmetic and svar substitution in sar functions, it has become possible to implement games in the sar hud or the console. This is modern tetris.

You need to be on master SAR for this to work. It DOES NOT work on SAR 1.12.3, but will most likely work on 1.12.4-pre1.
REMINDER: Don't do runs on master SAR.

AMJ's classic tetris: NOT YET
Video demonstration: COMING SOON

## Setting up

- Put the tetris folder such that you have `cfg/tetris/tetris.cfg` `cfg/tetris/display.cfg`, etc
- Set your binds in the `tetris/controls.cfg` file (do not override other binds)
- Optionally modify the coordinates at which the tetris board appears on your screen at the top of `tetris/display.cfg`
- Run `exec tetris/tetris` in the console to run SARtris ! Do NOT run this twice ! It will make the game forget your HUD/toasts parameters. Bind the premade reset and hide commands in the controls config.

## Features
- Hide and display SARtris at will without affecting the hud or toasts
- No gravity
- Legal in portal 2 runs
- Cool UI
- Open source
- Created using the SAR game engine

## Upcoming features
- SRS
- 7-bag
- hold
- Maybe loss detection

## Known issues
- Makes portal 2 stop for a split second when updating the UI. Improvements may come
- Some pieces can override the border color at the top

