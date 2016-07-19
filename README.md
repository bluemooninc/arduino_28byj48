# Stepper Motor 28BYJ-48

https://www.adafruit.com/product/858

## Discription

This Arduino example demonstrates bidirectional operation of a 
28BYJ-48, using a ULN2003 interface board to drive the stepper.
The 28BYJ-48 motor is a 4-phase, 8-beat motor, geared down by
a factor of 68. One bipolar winding is on motor pins 1 & 3 and
the other on motor pins 2 & 4. The step angle is 5.625/64 and the 
operating Frequency is 100pps. Current draw is 92mA. 

## Jumper Pin setting

<table>
    <tr><td>ULN2003</td><td>Arduino UNO</td>  
    <tr><td>IN1</td><td>D8</td>  
    <tr><td>IN2</td><td>D9</td>  
    <tr><td>IN3</td><td>D10</td>  
    <tr><td>IN4</td><td>D11</td>  
    <tr><td>VCC</td><td>5V</td>  
    <tr><td>Gnd</td><td>gnd</td>  
</table>
