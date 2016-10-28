# Printing a Circuit board workshop

> Based on the notes by [Philipp Eisen](https://twitter.com/phileisn).

all circuit boards are, is layer, insulator, layer, insulator

--> that makes it a capacitor

## Jargon:

  * Trace:  wires on boards are not wires - they are traces
  * Pad Size: margin between sockets?
  * Via: the whole where the cables go trough to change layers - increase cost of board, makes it more compplicated, and makes cam operator grumpy.
  * Wholes: Too mount stuff

Boards are green to resist solder.

Letters are painted on the board (silk screening)

yield --> what percentage of the board works?

## RULES:

RULES to design a Circuit board that will a work:

  * Trace width --> what is the minimum trace with / the thinner the more you can use. The thickness is usually refered to in mills - that's not milimeter but 1/1000 inch
  * Trace space --> minimums distance between two traces
  * Space to Board edge --> usually a lot more than minimum trace spacing
  * Spacing to vias --> often the same as to a trace
  * Spacing to wholes consider screws when designing the spacing
  * Where you can put vias. Some places where you cant put them include: under other parts
  * Maximum layers
  * Maximum board size (in mentorspace biggest possible is a4)

## How to design the board:

  1. Schematic Capture - that's your devices design
  2. Board Layout
  3. Computer Aided Manufacturing (CAM-Tool)
  4. Manufactoring Tool

## Using eagle

Most impartant are the top 4, info, eye, layers, and mark

Group is also important to move or delete large blocks of things

Delete in Schematic capture is not the same as in board layout. You can put down a symbol and delete a logic part in the schematic. On the board DONT'T do delete ever. Deleting on your board will delete it on the schemtic as well!!

Add is obviulsy also very important
Text in schematic is just in schematic. Doesn't go on the board itself.


Disable all libraries.

For the arduino weather station enable

- diods
- descrete   
- frames
- analog-devices
- pin head
- rcl - resistors, capacitors and inductors

First thing you need is a sheet.

go to Add > Frames > E1
