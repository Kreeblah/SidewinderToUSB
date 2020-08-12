# SidewinderToUSB
A PCB layout for the 3DP-Vert R3 Sidewinder adaptor code, using Fritzing.

The circuit itself is an implementation of adapt-ffb-joy (minus the trim pots) from https://code.google.com/archive/p/adapt-ffb-joy/downloads

The compiled code to use with this project is available at https://code.google.com/archive/p/sw3dprousb/downloads

Gameport part taken from https://github.com/shadwork/Arduino-PC-Gameport-HID/blob/master/Schematic/DB15%20Connector.fzpz

I've never laid out a PCB before, so this may have issues (the layout is also extremely amateurish).  I'm currently waiting on my boards and parts in order to be able to test.

Component list for building:
- 1x Teensy 2.0
- 1x DA-15 port (the gameport) with a right-angle connector
- 2x 2.2k ohm resistors
- 1x 220 ohm resistor
- 2x 1000pF capacitors
