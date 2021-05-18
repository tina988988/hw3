# HW3
## About
We need to use RPC loop to choose a mode(gesture UI or tilt angle). In gesture UI, we use different gestures to select different angles(30 35 40)shown on uLCD, and press
user button to confirm. In tilt angle(after finish choosing in gesture UI), we tilt B_L4S5I_IOT01A, and if the number of the tilt angle over the selected threshold angle 
reach 10 times, it stops the tilt mode.

## Build with
C++ Python

## Equipment
hotspot
B_L4S5I_IOT01A
uLCD display

## Display
Create a display on uLCD that can show the current selection of angle(when gesturing) and tilt angle.

## Input
User button as InterruptIn to confirm the angle. 

## Output
Three leds as DigitalOut to indicate the mode and situation.

## Sample
TF Lite model from mbed lab 8.

