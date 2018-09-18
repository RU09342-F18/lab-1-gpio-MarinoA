Multiple Blink by Alex Marino
Embedded Systems Section 3
Due by September 21, 2018
Created September 12, 2018
Version 1.0 - Lasted updated September 12, 2018
###############################################
Included files:
main.c
README.txt
Also required: msp430.h
###############################################
This program blinks two LEDs on the development board with two different frequencies. 
It uses an infinite while loop with two nested if-else statements. The first counts 
down the variable i, which can be changed by setting the RED_SPEED parameter. Changing 
this value changes the delay for the green LED and therefore makes it blink at a 
different rate. Once the variable i is decremented to zero in the if statement, the else 
will toggle the green LED and the program will move onto the second if-else, which does 
the same process but is controlled by the variable j which is set by changing RED_SPEED. 
The program sets the pins connected to the LEDs to the output direction. For the G2553 
these pins are 1.6 and 1.0, and for the F5529 they are 1.0 and 4.7. 
