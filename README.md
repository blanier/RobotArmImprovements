RobotArmImprovements
====================

Make a cheap robotic arm even cooler

I recently got one of [these off of Amazon] (http://www.amazon.com/gp/product/B0017OFRCY/ref=oh_aui_detailpage_o00_s00?ie=UTF8&psc=1): 

![Robot Arm Pic](http://ecx.images-amazon.com/images/I/51LAkVypvAL.jpg)

and I want to make it cooler.  

For starters, the remote control is wired, and it really should be wireless.  Additionally, there's no feedback on position and/or travel limiters.  This project is my attempt to fix that.  Yes; I know that I could just buy a better robot arm, but where's the fun in that? :-)  This is also a learning exercise (for me, at least) in using github for presentation of tutorial content and project logging.

I'm starting with the wireless control.  Then I'll move on to limit switches and then positional feedback.

Table Of Contents
=================

1. [Initial Theory of Operations] (InitialTheory.md)
2. Transmitter/Remote Control design 
3. Receiver/Base Control design
4. Limit Switch design
5. positional control design

Silly Requirements
==================
- No Arduino, Teensy, etc. (we'll see if I live up to that :-) )
- Non-destructive changes to the robot and controler

TODO
====

- [ ] fritzing diagrams for base receiver
- [ ] fritzing diagrams for controller transmitter
