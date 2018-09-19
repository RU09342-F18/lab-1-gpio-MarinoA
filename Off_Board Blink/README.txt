Offboard Blink by Alex Marino
Embedded Systems Section 3
Due by September 21, 2018
Created September 19, 2018
Version 1.0 - Lasted updated September 19, 2018
###############################################
Included files:
main.c
README.txt
Also required: msp430.h
###############################################
This program is the same as the multiblink program, but is flashed to the MSP430 and implemented on a breadboard. Pin 1 is connected to power, Pin 2 is connected through a 500 ohm resistor to the green LED which is connected to ground (pin 1.0 in the program). Pin 14 is connected through a 1kOhm resistor to a red LED which is connected to ground. Pin 16 is connected directly to power because it is the reset pin, which has negative logic. Pin 20 is connected to ground. Having these connections allows the MSP430 to have proper power and output the correct signal to each LED. 

A video of the program working on a bread board is shown below: 
https://drive.google.com/open?id=1YkXIC43hrym9XJxpTgGkBnuaH739pt2h
