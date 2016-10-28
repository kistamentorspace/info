Kista Mentorspace KB
================================================================================

# PCB

The workflow of PCB designing can be divided into three parts

1. Creating a Schematic
2. Creating a Layout
3. Fabricating a PCB

Step 1 and Step 2 are done using various tools, the recommended tools for PCB Designing are:

1. Eagle – A freeware light version, available for Windows as well as mac, recommended for beginners. It’s really easy to learn and there are plenty of resources available online to learn Eagle, it’s easy to find eagle libraries as well.
2. KiCAD – If you are a Linux user, then this is a great tool for PCB designing.
3. Altium – This is a pretty advanced tool and you’ll need to spend quite a lot of time to learn it, however, this is a very powerful tool which can be used to design boards of 6+ layers easily.
4. Cadence Allegro PCB Designer – Another advanced tool and a competitor of Altium, again for advanced users and takes quite a lot of time to learn.

However, in this tutorial, we’ll be concentrating on Part 3, which is Fabrication of Printed circuit boards.

There are many ways of fabricating PCB. In our case, we will be focusing on fabricating a two-layer Printed Circuit board using the LPKF Milling Machine.

If you want to make a printed circuit board, make sure that you have the Gerber files for Board Outline, Top Layer, Bottom Layer and Drill Layer.

For this workflow, we’ll be using two tools, Circuit Cam, which will be used for creating a CAM (Computer aided manufacturing) file, which is then used as an input for Board Master, which is a tool communicating with the Milling Machine.

Further steps:

* [Eagle workshop notes](pcb/eagle_workshop.md)
* [Exporting Gerber files in Eagle](pcb/eagle_gerber.pdf)
* [PCB milling part 1 – CircuitCAM preparation](pcb/lpkf_circuitcam.md)
* [PCB milling part 2 – Boardmaster operation](pcb/lpkf_boardmaster.md)

Links:

* [Eagle tutorials on Sparkfun](https://learn.sparkfun.com/tutorials/tags/eagle)
* [KiCAD video tutorials from ContextualElectronics](https://contextualelectronics.com/learning/getting-to-blinky-4-0/)
