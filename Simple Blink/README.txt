Simple Blink by Alex Marino
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
This program makes a single LED on the development board flash on and off. 
It uses an infinite for loop which contains a decrementing do-while statement 
which implements a delay. After this countdown reaches zero, the XOR statement 
toggles the state of the LED from off to on or on to off, depending on the previous state. 
All code for this program comes from the TI example. 

The MSP430G2553 and MSP430F5529 both use pin 1.0 for their LED, and so the program sets this pin to output 
and can be used interchangeably between these two boards.  
