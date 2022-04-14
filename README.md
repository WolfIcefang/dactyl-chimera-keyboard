# dactyl-chimera-EX: the Experimental branch.

## Dactyl Chimera EX printed successfully, but has a few critical issues:
- It is difficult to assemble and disassemble.
- It has no method to handle wiring.
- The outer columns are difficult to print.
- The rack was not level between the bottom row and top row.
- The excessive use of FreeCAD's Spreadsheet slowed down the program.

Work has been moved to the Dactyl Chimera Neo (v3.0) branch. **This branch will no longer be updated.**

![image](https://user-images.githubusercontent.com/38160450/137390333-8405c472-2334-4be3-90fa-50e817eeb17e.png)

Dactyl Chimera EX will have the following completed before it becomes the main branch and gets a Reddit announcement post:

3D modeling stuff:
- DONE: "90% parametric", that is, changes to part geometry from the spreadsheet work about 90% of the time. Sometimes things still break, that's inevitable
- an adjustable thumb cluster (twist, height, and stagger) 
- joystick thumb cluster variant
- adjustable tenting foot angle after printing
- split top and bottom arch01
- DONE: CNC machinable rack plates
- stagger rack (aka the back plate rack) with mounting holes for extra components
- Mounting bracket for OLED display
- mounting bracket for microcontroller
- mounting bracket for rotary encoder

kicad/software stuff
- Single switch PCB design for per-key RGB (will be in a separate repository)
- QMK support
- Vial support
- ZMK support

testing requirements:
- must print out, assemble, and wire both sides of the keyboard.

documentation stuff:
- have a build guide.
- have reasonable defaults for column sizes
