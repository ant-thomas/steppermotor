steppermotor
============

**Raspberry Pi stepper motor control script.** 

Adapted from adafruit script available here:<br>
http://learn.adafruit.com/adafruits-raspberry-pi-lesson-10-stepper-motors/software

Allows the use of user defined parameters from the command line.


**Usage:**

sudo python stepper.py &lt;delay&gt; &lt;steps&gt; &lt;direction&gt;

delay - in ms<br>
steps - integer<br>
direction - f=forwards b=backwards<br>

**eg:**

sudo python stepper.py 10 512 f
