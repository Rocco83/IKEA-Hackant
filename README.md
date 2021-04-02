# IKEA Hackant

A simple LIN slave attached to the stock controller board adds two memory buttons.
If you are interested in how this was developed check out my YouTube Tutorial

[![YouTube Tutorial](http://img.youtube.com/vi/AB75AxprXqQ/0.jpg)](https://www.youtube.com/watch?v=AB75AxprXqQ "IKEA Bekant Table Hacking")

## Schematics

IKEA circuit, from left, top looking:
4th pin: GND
5th pin: UP
6th pin: DOWN

i2c address 0x31 for the touch

Simple schematics created with [Fritzing](http://fritzing.org/home/ "Fritzing").

![Schematics](https://github.com/robin7331/IKEA-Hackant/raw/master/Schematics_schem.png)
![Board](https://github.com/robin7331/IKEA-Hackant/raw/master/Board.png)

D2 hardcoded in lin libs as LIN input pin
