# dactyl-chimera-keyboard

## A mechanical keyboard designed for 3D printing, tinkering, and experimentation.

This project aims to provide a "test bench" for various column curvatures in mechanical keyboards. Potential side effects include: shorter print times, instant fine-tuning of column height and stagger, adjustable tenting, and comfortable computer usage. Interchangable thumb clusters are also a goal of the project, but have not yet been researched.

Dactyl Chimera (DC)'s primary purpose is as a testing tool. It is not designed to look stylish, sound spectacular, or increase compactness. If you do not mind a couple (dozen) dangling wires or visible screws, DC should offer reliable long-term use and potentially even hold up to the rigors of PC gaming, although my laptop (and lifestyle) are personally unable to verify such claims.

## How it works (and why it's awesome):

###Dactyl Chimera is comprised of three main components: arches, the rack, and the tenting foot.

**The Rack** is similar to the bottom plate of a traditional keyboard. It is mostly flat and has a pattern of screw holes to mount the other components.

**The Tenting Foot** mounts to the underside of the rack. Wolf Icefang's "travelling foot" is a simple kickstand. It has two positions: "flat", which is parallel to the rack, and "out", which is perpendiclar to the rack and provides a tenting angle of 25 degrees. Because the foot provides the tenting angle, a DC Rack without any tenting is completely flat. It can be modeled parallel to your 3D modeling software's origin plane. You can design any type of tenting foot you desire and attach it to the underside of Dactyl Chimera to give it your perfect tenting angle.

**The Arches** are the keyboard's switch columns and front/back walls. Each arch contains one column of switches, except for the outer (pinky) arch which contains two columns. Arches mount directly to the rack, not to one another. Because each column can be printed independently, failed prints don't waste your whole day and don't use a ton of support material. Because arches mount directly to the rack, and the rack is parallel to the CAD software's base plane, there is no need to worry about the keyboard tenting angle when designing a column. Finally, because arches are not connected to each other, changes in height from one column to the next can't cause keycap interference.

## How to participate:

We (that is, so far, just Wolf Icefang) are developing Dactyl Chimera in FreeCAD and intend to duplicate the design in SolveSpace. If you prefer a different 3D modeling platform, use the \[sizing chart\] (coming soon) to help fit your arches to the rack. If you don't know anything about 3D modeling, you can download a set of "standard" STL files and use a 3D printer at your local library/school/makerspace. However, if you do own a 3D printer, I HIGHLY recommend learning FreeCAD.

You should also join the Dactyl Chimera Center in [Matrix](https://matrix.to/#/!mArixoOlqsCQNWsaFc:matrix.org?via=matrix.org) The Dactyl Chimera Center is a great place to troubleshoot problems, but also discuss improvements, ideas, and successful builds. You can also use the Issues and Pull requests tools in this GitHub repo.

Wiring up a Dactyl Chimera shouldn't be too different from handwiring a regular Dactyl, and I'll post a link to a good build guide once I find one. For now, here's a link to the more generalized r/mechanicalkeyboards custom keyboards wiki: https://www.reddit.com/r/MechanicalKeyboards/wiki/customkeyboards to learn about hardware, and for software, here's a link https://www.reddit.com/r/MechanicalKeyboards/wiki/customkeyboards You'll be using Custom Firmware, most commonly QMK or ZMK.

##Designing a keymap

Dactyl Chimera is a 5 row, 6 column layout.

## History of the Dactyl / Special Thanks:

The first [Dactyl keyboard](https://github.com/adereth/dactyl-keyboard), created by Adareth, is a 3D printable adaptation of the Kinesis Advantage keyboard. The Kinesis Advantage, in turn, bears a striking resemblance to the even older Maltron Keyboard. This Dactyl Chimera also takes inspiration from the bezel-free sides of the [Dactyl Manuform](https://github.com/tshort/dactyl-keyboard), the adjustability of the [Squeezebox keyboard](https://peterlyons.com/problog/2021/04/squeezebox-keyboard/), the Tenting Puck of the [Kyria](https://splitkb.com/products/tenting-puck) and various discussions on the #kb-ergo channel in the [MechKeys Discord](https://discord.gg/mechkeys)
