# Dactyl Chimera build guide

This build guide is a work in progress. It is written for the Dactyl Chimera 3.0 branch.

## Is Dactyl Chimera right for you?

Dactyl Chimera (DC) is a split keyboard with 5 rows and 6 columns in each half. It has 60 keys, similar to a 60% keyboard.

DC is NOT a medical tool. I have not studied ergonomics or human anatomy. I made this keyboard because I dislike spacebar stablilizers.

Dactyl Chimera is a "test bench" keyboard. It prioritizes adjustability and experimentation, but sacrifices beauty, sound profile, and portability.

Dactyl Chimera is compaible with MX-style and Kailh Choc v1 keyswitches.

If all that sounds good to you, then let us begin!

## Designing your keyboard layout:

A "layout" determines how your keys are arranged on your keyboard. It is also called a Keymap. You may already know where the letters are going, but what about the arrow keys? F1-F12? The enter key? Layouts can also determine how many physical keys your keyboard needs; maybe you need a physical number pad.

Start thinking about your layout today. It will give you something to do while you wait for hardware parts.

### Understanding layout basics:

To start, read one of the following guides:

- Thomas Baart's guide to working with a small keyboard. https://blog.splitkb.com/how-to-work-with-small-keyboards
- Currently there is only one guide in this list...

Now that you've got the general idea, I highly recommend these articles:

- DreymaR's explanation of "[Extend](https://dreymar.colemak.org/layers-extend.html)", for where to put your arrow keys.
- [Precondition's Guide to Home Row Mods](https://precondition.github.io/home-row-mods) **VS** [why you shuold BAN Key Chords](http://xahlee.info/kbd/banish_key_chords.html) for where to put ctrl, shift, gui, and alt.
- I use Colemak mod-DH. It helps my thumbs rest on the small spacebar key. It's easy to learn using the [Tarmak](https://dreymar.colemak.org/tarmak.html) system.
- You can join the https://www.reddit.com/r/KeyboardLayouts/ subreddit for some really mind-bending ideas.
- Finally, I challenge someone to combine [Asetniop](http://asetniop.com/) with 50 macro keys. There is no reward.

#### If you are already using smaller keyboards...

...Then you might be intimidated by a staggering **60 keys**. Fortunately, you don't actually need to USE every key on this keyboard. You don't even need to put switches in all the holes! That being said, "extra keys" can quickly accommodate an unexpected keyboard shortcut, (for example, "why does Microsoft Excel use F2 as the Edit Cell shortcut?"), temporarily patch a deficit in your layout, ("I didn't realize I needed an Enter key on my left hand."), or trigger actions when your hands aren't settled into a typing rhythm. ("I need to mute my computer for this phone call.")

If you still wish for a smaller keyboard, you can check out:
- The squeezebox keyboard, possibly the closest to the Dactyl Chimera in design and features. https://www.reddit.com/r/ErgoMechKeyboards/comments/rvuvk2/squeezebox_keyboard_v2112/
- The Corne is open source and a tentpole of the split ergo community. https://github.com/foostan/crkbd
- The Lily58 has 58 keys but is flat and travel-friendly. Many online retailers offer versions with unique features. https://github.com/kata0510/Lily58
- The Azeron Cyborg is a one-handed keypad designed for gaming. https://store.azeron.eu/index.php?route=extension/azeron_store_design_product/getAllKeypads#keypad=cyborg


#### If you are accustomed to larger keyboards...

...Then you might be concerned by the lack of arrow keys or a function row. Small keyboards are not for everyone. You can use key remapping software to "shrink" the keyboard you already own, add layers, and more: https://www.reddit.com/r/MechanicalKeyboards/wiki/remapping_software

Only a few Dactyl-like keyboards have more keys than the Dactyl Chimera. 
- [Maltron](https://www.maltron.com) is the brand that started it all.
- The [Kinesis Advantage 2](https://kinesis-ergo.com/shop/advantage2-refurbished/) borrowed some ideas from Maltron, and the first Dactyl borrowed some ideas from Kinesis.

Many exciting projects are in the works, though:

- Redditor [RMTZ](https://www.reddit.com/user/rmTizi/)'s Naïve keyboard is in development.
- MoErgo's [Glove80](https://geekhack.org/index.php?topic=114881.msg3086876) has a finalized design but has not gone into production yet.
- ScarletSwordfish's [AEK II Split](https://geekhack.org/index.php?topic=103804) is beautiful, but it requires gutting a vintage keyboard and may never see a public release.

### Choosing your firmware:

Inside of your keyboard is an arduino-like **microprocessor**. This microprocessor runs a type of program called "firmware". Firmware tells the microcontroller how to identify keystrokes and how to communicate with your PC over USB (or bluetooth).

Your keyboard's features will be limited (or enhanced) by the firmware you choose.
- Vial provides a friendly interface where you drag letters onto a picture of your keyboard. https://get.vial.today/
- QMK offers nigh-unlimited customization and control. You'll need to write code and run Linux to get the most out of it. https://docs.qmk.fm/
- ZMK is the best choice if you want Bluetooth. https://zmk.dev/
- There is plenty of other firmware out there. The unabridged list can be found here: https://www.reddit.com/r/MechanicalKeyboards/wiki/firmware/

### Tips for making an efficient layout:

- Use a spreadsheet or Inkscape drawing to brainstorm. Spreadsheets are easy to edit, but Inkscape lets you represent combos and tap dance sequences by drawing lines and arrows.
- Place the keys you use most often in the center of each layer, and unimportant keys near the edges.
- Sometimes your fingers will "already know where to go". If you keep hitting the "wrong" key because you expect a certain keycode to be there, find a way to move that keycode there.
- Keep a list of every possible keyboard key. Cross off keycodes once you've found a spot for them. Include every key found on a full size keyboard.
- Beware of Enter and Escape! Pressing these keys can clear text boxes or instantly send a message. Tab and Alt are also mildly powerful.
- Never bridge your combos or tap dance across both halves of the keyboard. There will come a time when you must hold something in one hand and type in the other. (even if it's just your mouse.) My original Corne layout used a combo of left thumb and right thumb as "enter"; it was almost impossible to use.
- Pay attention to "bigrams" and "trigrams", keys you often press in a particular sequence. For example, every sentence you write ends with a tap dance of [period] -> [space] -> [shift]. If you put shift and spacebar under the same thumb, you'll feel inclined to write run-on sentences.
- A spreadsheet of "starter layouts" is included this GitHub's releases page. These layouts are provided to inspire you, not restrict you.
- Finally, never be afraid to change your layout. Finding a good keymap is a mixture of experimentation, logical patterns of symbols, muscle memory, and the keyboard shortcuts you use.


## Buying components

We'll need some tools (3d printer, soldering iron), some normal keyboard parts (switches, keycaps), and some special parts (screws, 3d printer filament.)

### Let's start with tools.

Take advantage of publically available tools; this will let you invest (or sink) more money into the actual components of your keyboard. Your local makerspace, public library, or college campus are great places to look.

Make sure you have access to the following:
 - A soldering iron, solder, flush cutters, and a method of desoldering. You will not need a heat gun. https://docs.keeb.io/soldering-tools
 - You'll need a 3D printer. The users of https://www.reddit.com/r/3Dprinting/ can help. The Dactyl Chimera doesn't need dual extrusion, resin-level quality, or an enclosed build area, but those features are the gatekeepers to many other projects. From my perspective, a large heated bed, good cooling fans, and automatic bed leveling are always worth the expense.
 - You can accent this keyboard with an acrylic bottom plate. I believe Keyhive offers an acrylic cutting service if you contact them directly. https://keyhive.xyz/
 - Is your screwdriver always camming out? It might not be the screw's fault. [Project Farm has multiple videos on the topic.](https://www.youtube.com/c/ProjectFarm/search?query=screwdriver)
 - If you need safety glasses, I recommend the Uvex Sperian, Uvex Protégé, and Pyramex Ztek. Clear lens variants are great for working indoors and still provide UV protection outdoors.

### Normal keyboard parts (the keys).

First, the keyswitches. There are nigh-unlimited options here, look no further than [ThereminGoat's](https://www.theremingoat.com/) blog of 1,000 switches.

I recommend silent switches on the Dactyl Chimera. With no walls, it can be difficult to reduce unwanted sound. Silent switches have tiny rubber bumpers inside the switch itself! Many popular switches have a silent variant.

The r/mechanicalkeyboards wiki has an extensive list of switch vendors https://www.reddit.com/r/MechanicalKeyboards/wiki/switch_suppliers

Keycaps are just as important as switches. 
 - Use the r/MechanicalKeyboards [Keycap Guides](https://www.reddit.com/r/MechanicalKeyboards/wiki/keycap_guides) to learn all about keycap shapes and materials
 - Then head over to [KeyCapSellers](https://www.reddit.com/r/MechanicalKeyboards/wiki/keycapsellers) for pricing and vendor options.

### Parts unique to the Dactyl Chimera

WSB: World's smallest board - 


Wires: 


Diodes: 


Microcontrollers: You will need one microcontroller for each side of the keyboard. (two in total.)
 - The Raspberry Pi Pico is the newest, most powerful, and cheapest microcontroller I know of. It's the best in every category! https://www.raspberrypi.com/products/raspberry-pi-pico/
 - The Arduino Pro Micro is a classic in the split keyboard community. It's cheap, small, and popular enough to make troubleshooting a breeze. However, it is an older chip with limited specs; you might struggle to install Vial onto this microcontroller.
 - The QMK Proton-C is a direct upgrade, or sequel if you will, to the Pro Micro. It has better specs, more pins, and USB-C instead of Micro-USB. It is also more expensive and produced in limited quanitities. Read more and find retailers here: https://qmk.fm/proton-c/
 - The Nice!Nano has the same shape and layout as a Pro Micro, but it adds bluetooth and battery charging. This microcontroller utilizes ZMK's wireless features. https://nicekeyboards.com/nice-nano/

Microcontroller sockets:

Hotswap switch sockets: I got my sockets from [KeyHive](https://keyhive.xyz/shop/kailh-sockets). Other vendors are listed here: https://www.reddit.com/r/MechanicalKeyboards/wiki/switch_suppliers

RJ-9 phone cord and jacks: I need to find something good before I can make a recommendation.

3D printer filament: The Prusa Knowledge Base includes a handy catalog of materials, in both [list form](https://help.prusa3d.com/en/category/material-guide_220) and [Chart form](https://help.prusa3d.com/en/materials). Your local makerspace might already have rolls of filament for you to use. I used a combination of PETG arches and a PLA rack for Dactyl Chimera, more for the color combination than the printing performance.

Screws: Did you think you could just pick random screws from Amazon and call it a day? Think again! The screws I used in my Dactyl Chimera are horrible! The black coating rubs off on my hands and one of the screws got jammed into place. I cannot recommend screws to you because I need better recommendations for myself!


### Optional parts

RGBs, OLEDs, Rotary encoders, and joysticks will populate this section... eventually.  All I know so far is... Amazon is not a good vendor if you want your OLEDs to arrive in one piece.

## Hand sizing chart

*Dactyl Chimera's .stl files have similar spacing to a regular Dactyl Manuform. If you like the default Dactyl shape but need DC's shorter print times, you can skip this secion.*

In order to use FreeCAD, you first need to download it. Do so here: https://www.freecadweb.org/ The bottom of FreeCAD's homepage also lists various social media sites for troubleshooting.

FreeCAD has an [official manual](https://wiki.freecadweb.org/Manual) but it covers a ton of non-keyboard stuff from Raytracing to architecture. I'll give you the basics here.

Like a lot of software, the trickiest step is figuring out which button to click on first. In FreeCAD, that's the "Workbench" dropdown list: (it might be in a different location and a different color for you)

![image](https://user-images.githubusercontent.com/38160450/138741323-3e677a1e-5984-4150-b918-8e67fb78d1a6.png)

If you don't have a workbench dropdown list, use the View button in the menu bar:

![image](https://user-images.githubusercontent.com/38160450/138741609-7195e519-66bd-4e6f-86e3-57d5c432d033.png)

FreeCAD is highly customizable; that means it's easy to accidentally hide or disable important features. If you get lost at any point, don't hesitate to ask for help.

FreeCAD, like Blender, is separated into Workbenches. Each workbench provides a unique set of tools for a different type of work. For example, the "Part" workbench is like an advanced version of Tinkercad, and the Draft workbench is for 2D drawing like Inkscape. For Dactyl Chimera, the most important workbenches are "Part Design", "Sketcher", and "Spreadsheet".

But wait! Before we get started, make sure to choose your favorite Mouse Navigation mode, as explained here: https://wiki.freecadweb.org/Mouse_navigation Not doing this is like playing Super Metroid with the default control scheme.

Oh yeah, also, make sure AutoRecovery is turned on so it creates backup files! There are plenty of buttons in FreeCAD that will just... destroy your the model; sometimes it's bad enough that the undo button starts spewing out error messages. AutoRecovery is nestled deep in the [Preferences editor](https://wiki.freecadweb.org/Preferences_Editor/en) there are a ton of other toggles to play with but **don't change anything until you're familiar with how FreeCAD works by default.**

### Part Design workbench

The Part Design workbench is for navigating 3d space and extruding your 2d sketches. Once again, there are a few "very important" buttons hidden around the UI. You need to find the Create Body, Create Sketch, and Create Datum Plane buttons, as well as "Pad selected sketch" and "Pocket selected sketch" buttons. They look like this:

![image](https://user-images.githubusercontent.com/38160450/138745612-2e0ba2d3-b624-4f3a-b0f5-871e31b9e9cd.png)

You will also need to locate your [Tree View](https://wiki.freecadweb.org/Tree_view), which lists all the different parts in your file. It looks like this:

![image](https://user-images.githubusercontent.com/38160450/138747077-9d407efe-86a0-4679-b6d8-50faf0b111a4.png)

If you cannot find it, you might be in the "Tasks" tab isntead of of the "Model" tab.

Double clicking on something in the Tree View will let you edit that thing, whatever it is. (You can usually press the Escape key to stop editing.) Clicking on an object once in tree view then pressing the spacebar will toggle its visibility. Hovering your mouse over an item Tree View will make its 3d Model "Glow", which helps you see the internals of an object like the Tenting Screw or to help you identify an unnamed item. The item has to be visible for the hover glow trick to work.

If you want to create a new component for your keyboard, like a rotary encoder mount or a different type of thumb cluster, click the "Create a new Body" button. In FreeCAD, each [Body](https://wiki.freecadweb.org/PartDesign_Body) is a different solid part. When you export the model, each body becomes a separate .stl file.

The Body's origin might be invisible, so find it in Tree View and toggle its visibility on.

Now that you can see your Origin, you might want to place down some Datum Planes. Datum Planes can help you do things align screw holes and provide the bounding edges for where your part begins and ends, but they are optional. Read more about arranging Datum Planes here: https://wiki.freecadweb.org/PartDesign_Plane/en

With your datum planes in place, you're ready to start sketching! Click on one of your datum planes or origin planes and then press the Create a New Sketch button. You will be thrown into the Sketcher Workbench.

### Sketcher workbench

There are now a ton more buttons, and better yet, you'll be using most of them. Don't freak out.
 - Icons with white lines connecting big red dots are your sketcher geometry. They let you draw things like circles, arcs, and lines.
 - Icons that are entirely red are your constraints. They keep your geometry lines from moving around. For example, if you want your keyswitch holes to be 14mm wide, then you'll add a length constraint to your geometry lines.
 - Icons with green in them are... mostly there to help power users work faster, I think. I haven't actually learned what they do.

Now don't go drawing a bunch of lines all over the place! This will tank FreeCAD's performance and not be fun. (dragging a line around on screen is like asking OpenSCAD to repeatedly regenerate a model, so you can imagine what having a ton of freely floating lines would be like) Instead, draw a few lines (about 4 or 5) and try adding constraints to them until they turn green. A green sketch is "fully constrained" and cannot be dragged around any more. If your lines turn orange, you've added too many constraints.

FreeCAD's [Sketcher Workbench documentation](https://wiki.freecadweb.org/Sketcher_Workbench) is very good, honestly.

*OK but what are we actually drawing?* In FreeCAD, you draw the shape you want your 3d model to be, then extrude it out into a column like pushing play-doh through a tube. You can also think of your sketch as the base plate of your 3d printer, or the floor plan of a house. Even though you only see the floor, you can picture what the entire building will look like.

Keep your sketches simple. You can always draw multiple sketches, and keep in mind that everything in a sketch gets extruded (or "padded" in FreeCAD's terminology) the same distance. Not every sketch can be padded; there are a few rules you must follow so that FreeCAD can understand what you drew:
 - All lines must form a closed loop. FreeCAD's padding tool is kind of like a bucket fill tool. If you have any gaps in your loop, FreeCAD won't be able to tell the difference between the inside and outside of your drawing. Make sure to use the [Coincident contrtaint](https://wiki.freecadweb.org/Sketcher_ConstrainCoincident) to connect the endpoints of your lines together.
 - Lines may never criss-cross. Think of the lines you draw as the external perimeter of your 3D prints. If parts get too thin, they'd just snap apart instantly. Try to draw all your shapes like [bubble letters.](https://www.lettering-daily.com/bubble-letters/)
 - That being said, you can put a smaller loop inside a bigger loop. For example, if you but a small circle inside of a bigger circle, you'll get a tube with a hole in it.
 - You can have as many inner loops as you like, but you are only allowed one outer loop. Each Body in a FreeCAD file must be a single solid object; multiple outer loops would break this rule.
 - You may feel the need to draw support beams and arches to help hold your loop in place, and in fact you can! However, you'll need a new tool: construction geometry. Think of construction geometry like the scaffolding around a building. It is important when the building is being built, but is taken away for the final product. Read more about construction geometry here: https://wiki.freecadweb.org/Sketcher_ToggleConstruction
 - You technically don't need to fully define your sketch (turn it green) but I think my college professor described doing so as "a good way to quickly get fired from your job." Needless to say it's generally frowned upon.
 - One last thing. As long as you aren't ready to pad a sketch into a 3D shape, you can ignore all of the above rules and draw lines wherever you want. Sometimes you need to leave your sketch to look at something else, save your work, do whatever you want.

Once you have sketched the shape you want to pad, it's time to exit the Sketcher. Don't use the Workbenches dropdown list, instead hit the escape key of find the close button in the left panel on-screen. (don't just "close" freecad.) I typically recommend pressing escape on the keyboard.

You should be thrown back into the 3d model view, and you should be transferred back to the PartDesign workbench.

### Back to the PartDesign workbench

It is time to turn your 2D sketch into a 3D object. Press the yellow Pad button, explained here: https://wiki.freecadweb.org/PartDesign_Pad If you see a solid object, congratulations! You just made it through weeks worth of college-level CAD courses in... hours? Days? I don't know how long it took you to read this. If nothing appears on screen and you get a big error message, then you've drawn your sketch incorrectly. Send a screenshot, or better yet the actual file, to https://matrix.to/#/#dactyl-chimera-center:matrix.org and don't feel bad, when I first started I thought drawing a circle would create a sphere. (it actually creates  cylinder)

Now that you have your basic object, you can create more sketches, using the Pad tool to add more material and the [Pocket tool](https://wiki.freecadweb.org/PartDesign_Pocket) to carve away at material.

#### The spreadsheet workbench: editing the existing model.




## how to 3d print the pieces

Print the racks first, then the columns from outermost to innermost, and finally the thumb cluster.

### The Racks:

RackA and RackB are your keyboard's bottom plate. If you're completely new to 3D printing, it should be as simple as drag-and-dropping the file into the printer's slicer and hitting "Go". RackA and RackB can also be laser-cut or CNC milled out of a variety of materials; .dwg and .svg are provided for your convenience.

RackC, also known as RackStagger, is also very simple, however, it may be your first introduction to support material, but your 3D printing software might decide it's not necessary. You should print this part upright, just like it is in the .stl file. Your print may have issues sticking to the print bed. A heated bed, a "brim" (enabled in the 3d printing software) or a layer of glue from a water-soluble glue stick should help. If you still encounter issues, the excellent community over at https://www.reddit.com/r/FixMyPrint/

RackD is a large piece, but it shouldn't be too much of a challenge. All you really need to do is make sure support material is turned on. If you are printing at a public printer, insist that the gap between the support material is not increased from its default setting in the slicing software. The curve's overhang is quite steep and it'll need close support to look good. If you're using PrusaSlicer, I recommend using the [variable layer height](https://help.prusa3d.com/en/article/variable-layer-height-function_1750) feature. For removing support material, the tools to use are a pair of flush cuters and a pair of needle nose pliers. Do not use knives or chisels to remove the support material. You will cut into the print, or worse, cut yourself. You will also wear safety glasses to protect your eyes from tiny bits of flying plastic.

### The Arches:

Pring the inner most arch, the one with 4 switch holes, first. Do this because when something inevitably goes wrong, you'll have wasted less plastic. Lay the part flat on its side, with the "legs" that support the arch flat against the printer's build plate. If you are using PrusaSlicer, set the seam position to the under the arch between each socket, and restrict support material from being generated near the clip overhangs of the sockets. Once you get the hang of things you can print multiple arches at once. Remember, you have a total of 10 arches to print; 5 for each side.

After printing each arch, check to make sure the switches and screws fit.

### Everything else:

Finally, print the microcontroller holder, tenting foot, thumb cluster, and any other accessories you desire. There are various choices for each available, and none should be particularly difficult to make.

## soldering and wiring

The wiring matrix for Dactyl Chimera looks like this:

Dactyl Chimera is designed for hotswap sockets. Solder togetner a mesh/web of sockets together, making sure to leave generous amounts of wiring for the changes between column height. Arch 2, aka the ring finger, needs to be "woven" into the mesh becuase it has no gaps on the underside.

If you choose to wire by hand anyway, refer to [the QMK hand-wiring guide](https://docs.qmk.fm/#/hand_wire). You might also find it useful to extend the length of the switch pins, as explained in [the Squeezebox blog](https://peterlyons.com/problog/2021/04/squeezebox-keyboard/)

If you desire RGB, check out Wolf Icefang's S-S-S-S-P-C-B (super simple single switch printed circuit board) which can hold SK68 mini-e RGB LEDs in place without changing anything else about the wiring process! It's coming soon!

Make sure to socket your microcontroller. This is not "optional" like in some keyboards; it is necessary to take advantage of the swappable thumb cluster feature. **Links explaining socketing due to show up soon.**

Unlike some low-profile keyboards, Dactyl Chimera is usb port-side up. To be more accurate, the VCC pin is in the upper right corner.

This keyboard uses RJ-9 jacks to eliminate the issues of shorting over a TRRS cable. Here are close-up photos of how that is wired.

### Software and firmware



You can use the [editor on GitHub](https://github.com/WolfIcefang/dactyl-chimera-keyboard/edit/build-guide/docs/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.
