# dactyl-chimera-keyboard

## A mechanical keyboard designed for 3D printing, tinkering, and experimentation.

This project aims to provide a "test bench" for various column curvatures in mechanical keyboards. Potential side effects include: shorter 3d printing times, instant fine-tuning of column height and stagger, adjustable tenting, and comfortable computer usage. Interchangable thumb clusters are also a goal of the project, but have not been seriously researched.

Dactyl Chimera (DC)'s primary purpose is as a testing and research tool. It is not designed to look stylish, sound spectacular, or increase compactness. If you do not mind a couple (dozen) dangling wires or visible screws, DC should offer adequate reliablility and durability for long-term, even permanent, use.

## How it works (and why it's awesome):

### Dactyl Chimera is comprised of three main components: arches, the rack, and the tenting foot.

**The Rack** is similar to the bottom plate of a traditional keyboard. It is mostly flat and has a pattern of screw holes to mount the other components.

**The Tenting Foot** mounts to the underside of the rack. Because the foot is entirely responsible for the tenting angle, a DC Rack without any tenting is completely flat and can be modeled parallel to the XY origin plane. Wolf Icefang's "travelling foot" is a simple kickstand. It has two positions: "flat", which is parallel to the rack, and "out", which is perpendiclar to the rack and provides a tenting angle of 40 degrees. You can design any type of tenting foot you desire and attach it to the underside of Dactyl Chimera to give it your perfect tenting angle.

**The Arches** are the keyboard's switch columns and front/back walls. Each arch contains one column of switches, except for the outer (pinky) arch which contains two columns. Arches mount directly to the rack, not to one another. Because each column can be printed independently, failed prints don't waste your whole day and don't use a ton of support material. Because arches mount directly to the rack, and the rack is parallel to the CAD software's base plane, there is no need to factor in the keyboard's tenting angle while designing a column. Finally, because arches are not connected to each other, changes in height from one column to the next never cause keycap interference.

## How to participate:

We (that is, so far, just Wolf Icefang) are developing Dactyl Chimera in FreeCAD and intend to duplicate the design in SolveSpace. If you prefer a different 3D modeling platform, use the \[sizing chart\] (coming soon) to help fit your arches to the rack. If you don't know anything about 3D modeling, you can download a set of "standard" STL files from our releases page and use a 3D printer at your local library/school/makerspace. However, if you do own a 3D printer, I HIGHLY recommend learning FreeCAD.

You should also join the Dactyl Chimera Center in [Matrix](https://matrix.to/#/!mArixoOlqsCQNWsaFc:matrix.org?via=matrix.org) The Dactyl Chimera Center is a great place to troubleshoot problems, but also discuss improvements, ideas, and successful builds. You can also use the Issues and Pull requests tools in this GitHub repo.

Wiring up a Dactyl Chimera shouldn't be too different from handwiring a regular Dactyl, but I haven't finished wiring mine together yet or working on the software. Dactyl Chimera is a case first, and a keyboard second. (in other words it's not a fully functional keyboard yet.)

## Designing a keymap

Dactyl Chimera is a 5 row, 6 column layout. Having anything bigger than a 40% may be intimidating to some of you, but this section will teach you that it's okay to use large keyboards. First, why so many keys? Simply put, Dactyl Chimera needs to be massive so that it can accommodate both large and small layout experiments. Equally importantly, bigger curves provide more space to hide screws.

### But what do I do with all these keys?

First off, you don't need to use all the keys on this keyboard. You can use an asetniop layout in DC; you don't even need to wire switches into all the sockets. However, even if you stick with a smaller "core" layout, you may also want to fill the top and bottom rows with macros. These "extra keys" can be used to quickly accommodate a strange keyboard shortcut, (for example, "why does Microsoft Excel force me to use F2 as the Edit Cell shortcut?") to patch a deficit in your layout, ("I didn't realize I needed an Enter key on my left hand!"), or for actions you often take when your hands aren't settled into a typing rhythm ("Leave Zoom Meeting" and "mute computer" are among my top picks.)

### But I use a full size keyboard! Where are my arrow keys and function row?

Dactyl Chimera has approximately the same keys as a 60% keyboard, depending on your thumb cluster choice.  Included with each release is an easy-to-read spreadsheet showcasing the best layouts available. I recommend starting off with the Traditional-ish layout. But why, and how, does it work? To understand it, we need to:

### Understand basic theories of keyboard layouts

For beginners, I'd recommend reading Thomas Baart's Guide to working with a small keyboard https://blog.splitkb.com/how-to-work-with-small-keyboards

Once you're beyond the basics, you might want to check out:

[Precondition's Guide to Home Row Mods](https://precondition.github.io/home-row-mods) **VS** [why you shuold BAN Key Chords](http://xahlee.info/kbd/banish_key_chords.html)

I use Colemak mod-DH and highly recommend it. It helps my fingers rest on the keyboard, instead of hovering. It's easy to learn using the [Tarmak](https://dreymar.colemak.org/tarmak.html) system!

However, I challenge someone to use [Asetniop](http://asetniop.com/) with 50 macro keys as their keyboard.

Finally, DreymaR's explanation of "[Extend](https://dreymar.colemak.org/layers-extend.html)" is a fantastic jumping off point for designing secondary layers.


### Okay but we need firmware!

I have not wired up my own keyboard yet, and will definitely need help getting QMK support. I intend to use my keyboard with Vial (a real-time QMK keymap editor), and I believe "official" ZMK firmware support would also be good. If you have the expertise to make this happen, please join the Matrix Space or open an issue here in GitHub.

## License information:

Dactyl Chimera currently does not have a license associated with it. I recognize the problem of this and want to find a solution, but need help to do so. At the basic level, Chimera is really just a plastic sheet with a bunch of holes in it. I want to encourage users to design their own arches and tenting feet from scratch, and license them however they want. However, most licenses are written to encourage the distribution and modification of existing work, and the Chimera's purpose is to let you test the work you've done yourelf. If someone knows of an appropriate license, let me know and I'll be very grateful.

## History of the Dactyl / Special Thanks:

The first [Dactyl keyboard](https://github.com/adereth/dactyl-keyboard), created by Adareth, is a 3D printable adaptation of the Kinesis Advantage keyboard. The Kinesis Advantage, in turn, bears a striking resemblance to the even older Maltron Keyboard. This Dactyl Chimera also takes inspiration from the bezel-free sides of the [Dactyl Manuform](https://github.com/tshort/dactyl-keyboard), the adjustability of the [Squeezebox keyboard](https://peterlyons.com/problog/2021/04/squeezebox-keyboard/), the Tenting Puck of the [Kyria](https://splitkb.com/products/tenting-puck) and various discussions on the #kb-ergo channel in the [MechKeys Discord](https://discord.gg/mechkeys)
