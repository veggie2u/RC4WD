# RC4WD
A remote control 4 wheel drive car with smarts

## What is it?
This is four wheel drive robot like vehicle that can be controlled via a PS2 remote. It has some smarts for object detection and such.

The main parts are an Arduino, a motor controller, some batteries, some cheap motors, and a chasis. The things that make this interesting are a trinket controlling head and tail lights, the wireless control with a PS2 controller, and an ultrasonic sensor for object detection.

## Parts list
TBD

## Arduino Connections
Motor Shield
 - A4/A5 (I2C)

PS2 Interface
 - DATA  12 
 - CMD   10
 - ATT   11
 - CLK   09

Indicator
 - GPIO 13

Tone
 - PWM   03

Wheel Encoders
 - GPIO  02 Left
 - GPIO  04 Right

Ultrasonic
 - Trans 06
 - Rec   05
