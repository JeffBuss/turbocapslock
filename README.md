## TURBOCAPSLOCK 

### Overview

Remap your caps lock key to FN using Seil, then use Karabiner to create keybindings using the FN key as a fourth modifier key.

### Required Apps

[Karabiner](https://pqrs.org/osx/karabiner/)

[Seil](https://pqrs.org/osx/karabiner/seil.html.en)

### Setup

1. Navigate to system preferences > keyboard > modifier keys and set caps lock to "no action". If you use external keyboards, be sure to set this for them as well using the dropdown at the top of the screen. While you're at it, I'd suggest turning up your key repeat and delay until repeat to the max setting if you haven't already :)
2. Download and install Seil
3. Change caps lock key to keycode 80 (FN key) in Seil
4. Download and install Karabiner
5. Open Karabiner, and navigate to the "Misc & Uninstall" tab
6. Open private.xml
7. Replace private.xml with the one in this repo (or just copy and paste it in using a text editor)
8. Navigate to "Change Key"
9. Make sure "TURBOCAPSLOCK" is checked. It should be at the very top of the list
10. Keep your hands in the center of your keyboard, and actually put to use the most well-placed modifier key on your keyboard.
 

### Current keybindings

##### System
* FN H - delete
* FN delete - delete forward
* FN J - left 
* FN K - down
* FN L - right
* FN I - up
* FN U - skip to last word 
* FN O - skip to next work
* FN Y - skip to beginning of line
* FN P - skip to end of line 
* Shift FN U/O/Y/P - highlight to //

##### Spectacle Window Management App([link](https://www.spectacleapp.com/))
* FN A - split left
* FN S - split down
* FN W - split up
* FN D - split right
* FN Q - split upper-left quadrant
* FN E - split upper-right quadrant
* FN Z - split lower-left quadrant
* FN C - split lower-right quadrant

##### Atom
* FN ; - highlight current line
* FN ' - move line up
* FN / - move line down

