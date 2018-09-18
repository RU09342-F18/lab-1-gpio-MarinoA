Button Blink by Alex Marino
Embedded Systems Section 3
Due by September 21, 2018
Created September 17, 2018
Version 1.0 - Lasted updated September 17, 2018
###############################################
Included files:
main.c
README.txt
Also required: msp430.h
###############################################
The program uses a button to turn an LED on. The LED is off while 
the button is not pressed and the LED is on while the button is held. 
Releasing the button turns it back off. This requires the LED pin to 
be set as an output, and the button pin to be set as an input. The 
pullup resistor also needs to be enabled. For the G2553, the pullup 
resistor did not require any additional configuration. For the F5529, 
line 73 is required to set the resistor as a pull down. The body of 
the program features an infinite while loop with a single nested if 
else statement. An integer j is created which is the result of ANDing 
the button input with the corresponding bit. The if statement checks 
the result of the AND to determine whether the button is currently 
being pressed, and enables or disables the LED as described above. 
On the G2553 the LED is pin 1.0 and the button is pin 1.3. On the 
F5529 the LED is on pin 1.0 and the button is on pin 1.1. 
