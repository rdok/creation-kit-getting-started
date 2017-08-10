#### [Wiki](https://www.creationkit.com/index.php?title=Bethesda_Tutorial_Creation_Kit_Interface)
Overview:
- The basic components of the Creation Kit interface
- How to navigate in the 3D Render Window

#### Navigation
- Use empty cell for simplicity. On Cell View window, click on any cell, and start typing 'un' to find the 
'Unowned Cell'. Double click on this cell. 
    

#### Cheat sheet
##### Camera
- Precise Zoom in/out: Hold V + scroll mouse
- Move camera: Drag scroll button
- Turn camera around selected object: Hold Shift + Move Mouse
- Center on an object   
    - From Cell a View's object: double click 
    - From Render Window: Shift + F
- Refocus camera
    - Press Shift+F. This focuses the camera on the currently selected object(s). It does not affect camera angle, and 
        resets the camera pivot if no objects are selected.
    - Press "T". This forces a top-down view. If anything is selected, it will zoom the camera to the extents of that 
        selection. With nothing selected, it simply rotates the camera down (which can sometimes disorient you if 
        there's nothing to look at directly below the camera!)
    - Press "Y". This cycles through a few pre-set camera angles, and otherwise works exactly like "T". Easy to 
        remember because they're right next to each other (assuming a QWERTY keyboard). Convenient!
    - Use the mouse wheel to zoom the camera in or out.
- Enable/Disable markers: M
- Handle objects
    - Move object on the horizontal plane 
        - With mouse: (x + y): Drag with left button mouse 
        - With keyboard: arrows keys 
            - Move up/down: hold z + arrow keys
    - Move on a specifix axis: Hold down the x, c (y axis), z
    - Drop to floor: f
    - Rotate: Hold the right mouse button and turn the mouse 
        - Hold the z button to rotate on the various axis planes (x, c, z)
    - Scale: Hold the s key 
##### Gizmos
    - "E" Enables the Movement gizmo
        - Use arrow to move on relevant axis
        - Use side plane handlers to move on relevant planes 
    - "W" Enables the Rotation gizmo
    - "2" Enables the Scaling gizmo

##### Objects
    - Drag and drop to create a reference of an object
    - Ctrl + D to copy the reference        

#### Snapping
- Jump objects: "Q" hotkey.
- Rotate objects: CTRL-Q 

#### Save and test mod

    

    
```
mklink /H "D:\Code\creation-kit\2. Bethesda Tutorial Creation Kit Interface\testinterface.esp" "D:\SteamLibrary\steamapps\common\Skyrim Special Edition\Data\testinterface.esp"

mklink /H "D:\Code\creation-kit\1. Getting Started\fallout-4-testquest.esp" "D:\SteamLibrary\steamapps\common\Fallout 4\Data\testquest.esp"
```
