# ADC_ExtTrigger

Code for TIVA-C Launchpad - ADC using external trigger

Code derived from code samples provided with EdX class - Embedded Systems - shape the world. 

# Important File descriptions 


1. tm4c123gh6pm.h --- Header file contains reusable macros for Register Definitions
2. startup.s --- Startup code for KEIL uvision - edited for the class
3. UART.c --- Implementation of some functions for UART 
4. PLL.c --- A software function to change the bus frequency using the PLL.
5. ADC_ExternalTrigger.c --- Provide functions that initialize ADC0 SS3 to be triggered by External GPIO and trigger a conversion, wait for it to finish, and return the result.
6. ADC_MainUART.c --- Main Program that samples ADC on external trigger and sends the data to UART



