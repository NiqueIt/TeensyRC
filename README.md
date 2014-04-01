TeensyRC
========

An Open Source RC Transmitter implementation for Teensy 3.1, used with FrSky TX (XJT) and RX (X8R)


HW-Setup
--------
- Connect gimbal to A0 (Pin14) and A1 (Pin15)
- Connect XJT to PWM (Pin5)

Make sure, Teensy is powered by USB or 3.3V!!!
Make sure, XJT is powerd with 6-15V!!! 

Later, all hw will be stored in a Turnigy 5x, powered with 4x 1.5V. So you need probably
- Step Down Regulater (Pololu D24V6F3) --> 3.3V
- Step Up Regulater (Pololu U3V12F9) --> 9V


First run
---------
Make sure, you bind TX (XJT) and RX (X8R) properly.
Make sure, servos are connected properly to RX
