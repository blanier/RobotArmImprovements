Initial Theory of Operations
============================

Leaving the mechanicals aside, the electrical operation of the arm is relatively simple. 5 motors and an LED are powered by a six-volt power supply.  The power supply, which is composed of 4 D-Cell batteries connected in series, is split into a +3V and a -3V supply, by placing "ground" in the middle of the batteries (i.e. after batteries 0 and 1, and before batteries 2 and 3), rather than on the negative terminal.  Bidirectional motor control is achieved by feeding either +3V or -3V to the motors. Power switching is achieved by a matrix of 6 SPDT switches.  5 of the switches are 3-position (for forward-off-reverse motor controls) and one is 2-position (for on-off LED control). 

There are 2 PCB's in the system; one located in the base unit and the other in the remote control unit. Both are simply signal routers with passive components like switches and connectors.  Power flows from the batteries, to the base-unit PCB through a cable to the remote control, back to the base-unit PCB and out the the motors or LED.

The cable connecting the base unit and the remote control is an 8-wire flat cable with the following pinout:

pin number | signal     | function
-----------|------------|---------
0          |+3V         | Up/Close/Rotate Right/On
1          | M1 Control | Pincher [ open/close ]
2          | M2 Control | Wrist [ up/down ]
3          | M3 Control | Elbow [ up/down ]
4          | M4 Control | Shoulder [ up/down]
5          | M5 Control | Shoulder [ Rotate left/right ]
6          | LED        | [ on/off ]
7          |-3v

The switches are arranged such that for a given motor, if 

