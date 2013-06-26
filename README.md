steppermotor
============

Raspberry Pi stepper motor control script. 

Adapted from adafruit script available:
http://learn.adafruit.com/adafruits-raspberry-pi-lesson-10-stepper-motors/software


Usage:

sudo python stepper.py <delay> <steps> <direction>

delay - in ms
steps - integer
direction - f=forwards b=backwards


eg:

sudo python stepper.py 10 512 f
