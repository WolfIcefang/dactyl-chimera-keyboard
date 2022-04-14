# dactyl-chimera-keyboard

### Notice: work is currently focused on the Dactyl Chimera Neo (v3.0) branch. This branch is "complete" and will no longer receive updates.

## A mechanical keyboard designed for 3D printing, tinkering, and experimentation.

![image](https://user-images.githubusercontent.com/38160450/137078004-720b4ac5-ea5a-46e6-8267-8d04506273c3.png)

This project aims to provide a "test bench" for various column curvatures in mechanical keyboards. Potential side effects include: shorter 3d printing times, instant fine-tuning of column height and stagger, [adjustable tenting](https://youtu.be/rMioYSjqEoU), and comfortable computer usage. Interchangable thumb clusters are also a goal of the project, but currently there's only one thumb cluster to choose from.

Dactyl Chimera (DC)'s primary purpose is as a testing and research tool. It is not designed to look stylish, sound spectacular, or increase compactness. If you do not mind a couple (dozen) dangling wires or visible screws, DC should offer adequate reliablility and durability for long-term, even permanent, use.

## How it works (and why it's awesome):

### Dactyl Chimera is comprised of three main components: the arches, the rack, and the tenting foot.

**The Rack** is similar to the bottom plate of a traditional keyboard. It is mostly flat and has a pattern of screw holes to mount the other components.

**The Tenting Foot** mounts to the underside of the rack. Because the foot is entirely responsible for the tenting angle, a DC Rack without any tenting is completely flat and can be modeled parallel to the XY origin plane. The current tenting foot is a simple kickstand. It cannot be typed on when folded flat; it was just easier to model and print this way. It provides a tenting angle of 40 degrees. You can design any type of tenting foot you desire to give Dactyl Chimera your perfect tenting angle.

**The Arches** are the keyboard's switch columns and front/back walls. Each arch contains one column of switches, except for the outer (pinky) arch which contains two columns. Arches mount directly to the rack, not to one another. Because each column can be printed independently, failed prints don't waste your whole day and successful prints don't use a ton of support material. Because arches mount directly to the rack, and the rack is parallel to the CAD software's base plane, there is no need to factor in the keyboard's tenting angle while designing a column. Finally, because arches are not connected to each other, changes in height from one column to the next never cause keycap interference.

## How to participate:

Dactyl Chimera is designed in FreeCAD and will be recreated in SolveSpace once the design is proven to work well. If you prefer a different 3D modeling platform, use the \[sizing chart\] (coming soon) to help fit your arches to the rack. If you don't know anything about 3D modeling, you can download a set of "standard" STL files from releases page, however, if you own a 3D printer, I HIGHLY recommend learning FreeCAD.

You should also join the Dactyl Chimera Center in [Matrix](https://matrix.to/#/!mArixoOlqsCQNWsaFc:matrix.org?via=matrix.org). The Dactyl Chimera Center is a great(?) place to troubleshoot problems, discuss improvements, and share successful builds. You can also use the Issues and Pull request tools in this GitHub repo.

Wiring up a Dactyl Chimera should be similar to wiring up a Squeezebox. Solder wires to the switch pins to make the pins longer before sticking the switches into the keyboard, then solder those wires to each other. I haven't wired mine yet or worked on the software, so this might be terrible advice. Dactyl Chimera is a case first and a keyboard second. (in other words it's not a fully functional keyboard yet.)

## Designing a keymap

Dactyl Chimera is a 5 row, 6 column layout. Having anything bigger than a 40% may be intimidating to some of you, but this section will teach you that it's actually okay to use large keyboards. First, why so many keys? Simply put, Dactyl Chimera needs to be massive so that it can accommodate both large and small layout experiments. Equally importantly, bigger curves provide more space to hide screws.

### But what do I do with all these keys?

First off, you don't need to use all the keys on this keyboard. You can go as small as the asetniop layout; you don't even need to put switches into all the holes. That said, even if you stick with a smaller layout, you may want to fill the top and bottom rows with macros. These "extra keys" can be used to quickly accommodate a strange keyboard shortcut, (for example, "why does Microsoft Excel force me to use F2 as the Edit Cell shortcut?"), to temporarily patch a deficit in your layout, ("I didn't realize I needed an Enter key on my left hand!"), or for actions you often take when your hands aren't settled into a typing rhythm. ("Leave Zoom Meeting" and "mute computer" are among my top picks.)

### But I use a full size keyboard! Where are my arrow keys and function row?

Dactyl Chimera has almost as many keys as a 60% keyboard, depending on your thumb cluster choice. Included with each release is a spreadsheet showcasing the best layouts available. The Traditional-ish layout should appease fans of bigger keyboards. If it doesn't appease you, suggestions are always welcome. 

### Understanding the basic theories of keyboard layout design:

For beginners, I'd recommend reading Thomas Baart's Guide to working with a small keyboard https://blog.splitkb.com/how-to-work-with-small-keyboards

Once you're beyond the basics, you might want to check out:

DreymaR's explanation of "[Extend](https://dreymar.colemak.org/layers-extend.html)", for where to put your arrow keys.

[Precondition's Guide to Home Row Mods](https://precondition.github.io/home-row-mods) **VS** [why you shuold BAN Key Chords](http://xahlee.info/kbd/banish_key_chords.html) for where to put shift, ctrl, and more.

I use Colemak mod-DH and highly recommend it. It helps my fingers rest on the keyboard instead of hovering above it. It's easy to learn using the [Tarmak](https://dreymar.colemak.org/tarmak.html) system!

I challenge someone to combine [Asetniop](http://asetniop.com/) with 50 macro keys. There is no reward.

Finally, start thinking about your layout now! You'll want the software to be ready when the keyboard is done printing. 

### Okay but we need firmware!

Yeah, well, I need firmware too. I have not wired up my own keyboard yet, and will definitely need help getting QMK working. I intend to use my keyboard with Vial (a real-time QMK keymap editor), and I believe "official" ZMK firmware support would also be good.

## History of the Dactyl / Special Thanks:

The original [Dactyl keyboard](https://github.com/adereth/dactyl-keyboard), created by Adareth, is a 3D printable adaptation of the Kinesis Advantage keyboard. The Kinesis Advantage, in turn, bears a striking resemblance to the even older Maltron Keyboard. Dactyl Chimera also takes inspiration from the bezel-free sides of the [Dactyl Manuform](https://github.com/tshort/dactyl-keyboard), the adjustability of the [Squeezebox keyboard](https://peterlyons.com/problog/2021/04/squeezebox-keyboard/), the Tenting Puck of the [Kyria](https://splitkb.com/products/tenting-puck) and the many discussions in the #kb-ergo channel at the [MechKeys Discord](https://discord.gg/mechkeys).
