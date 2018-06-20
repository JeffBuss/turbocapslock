## TURBOCAPSLOCK 

### Overview

Do you ever use caps lock? No? How about we turn the most well-placed modifier key on the keyboard into something significantly more useful. We'll use Seil to remap your caps lock key to FN, which by default is used as a modifier for basically nothing besides the actual function keys. Then the private.xml file in this repo can be loaded into Karabiner with all the keybindings listed below.

### Setup

1. Navigate to system preferences > keyboard > modifier keys and set caps lock to "no action". If you use external keyboards, be sure to set this for them as well using the dropdown at the top of the screen. While you're at it, I'd suggest turning up your key repeat and delay until repeat to the max setting if you haven't already :)
2. Download and install [Seil](https://pqrs.org/osx/karabiner/seil.html.en)
3. Change caps lock key to keycode 80 (FN key) in Seil
4. Download and install [Karabiner](https://pqrs.org/osx/karabiner/)
5. Open Karabiner, and navigate to the "Misc & Uninstall" tab
6. Open private.xml
7. Replace private.xml with the one in this repo (or just copy and paste it in using a text editor)
8. Navigate to the "Change Key" tab
9. Make sure "TURBOCAPSLOCK" is checked. It should be at the very top of the list
10. Click the "Reload XML" button in the top right corner and enjoy
 

### Current keybindings

##### System (OS X)
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

##### Spectacle Window Management App ([link](https://www.spectacleapp.com/))
* FN A - split left
* FN S - split down
* FN W - split up
* FN D - split right
* FN Q - split upper-left quadrant
* FN E - split upper-right quadrant
* FN Z - split lower-left quadrant
* FN C - split lower-right quadrant

##### Atom ([link](https://atom.io/))
* FN ; - highlight current line
* FN ' - move line up
* FN / - move line down

### Adding custom keybindings
Adding more keybindings is relatively straightforward. Just open up the private.xml file in your favorite text editor, and use one of the previously-created keybindings as a template. For example, this keybinding remaps OPTION + CMD + RIGHT to FN + D.

`<autogen>
            __KeyToKey__
            KeyCode::D, ModifierFlag::FN,
            KeyCode::CURSOR_RIGHT, ModifierFlag::OPTION_L, | ModifierFlag::COMMAND_L
        </autogen>`

If you want to dive deeper, you can find the documentation for karabiner private.xml files [HERE](https://pqrs.org/osx/karabiner/xml.html.en).


