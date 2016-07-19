* Discription

This Arduino example demonstrates bidirectional operation of a 
28BYJ-48, using a ULN2003 interface board to drive the stepper.
The 28BYJ-48 motor is a 4-phase, 8-beat motor, geared down by
a factor of 68. One bipolar winding is on motor pins 1 & 3 and
the other on motor pins 2 & 4. The step angle is 5.625/64 and the 
operating Frequency is 100pps. Current draw is 92mA. 

* Jumper Pin setting

ULN2003 : Arduino UNO
IN1 - D8
IN2 - D9
IN3 - D10
IN4 - D11
VCC - 5V 
Gnd - gnd
