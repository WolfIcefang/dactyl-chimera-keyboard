Dactyl Chimera Neo design goals:

This is the list of goals for Dactyl Chimera NEO.

New parts:
- The Conductor: screw-down wire management
- Stagger Guide Rail: Screws onto rack instead of arches for easier adjustment. Removable after initial alignment
- OLED Tray
- Possible: snap-on accent panels

New techniques:
- Use named dimensions to reduce the burden on the spreadsheet
- Adjust location of each body's origin instead of making datum planes
- Simplify column spacing to be 20 mm from column to column and 19 mm for column width.
- Find quality parts to use and recommend
	- Screws
	- Wiring
	- Rubber feet
	- Cushion foam

TODO: before Reddit announcement:
- Fully wired RGB keyboard
- QMK Vial support
- Build guide

Later Reddit announcements:
- Sound demo
- ZMK firmware support
- Thumb cluster designs
- Design an adjustable palm rest (sister repository, compatible with all Dactyls)

The arches:
- Align the home row with an origin plane (before stagger)
- MX and Choc support (note: Choc will need to be handwired because it is only 2.2 mm thick.)
- Skeleton frame for easy wiring and nut access
- Use activated and deactivated dimensions so that users can either set column height
  - (A) relative to adjacent columns
  - (B) relative to the rack
- per-key angle and height adjustment

The thumb cluster:
- Use ball joints for articulation - thanks Azeron Cyborg

The Rack:
- model the arches before the rack, allowing the rack to adapt to the stagger of each arch

Tenting:
- Reuse the tenting solution from Dactyl Chimera EX