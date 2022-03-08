## Testplan and Output
----------------------
## simulation design

![solartrack](https://user-images.githubusercontent.com/98837660/157019194-e54dbdc0-db66-4cb2-86a2-28d5c52855d4.png)

----------------------------
## simulation output 

## High Level Requirements

HLR1 : The LDR sensor Detects the light intensity and give input to the MCU - Implemented.

HLR2 : The system take the input from the MCU and servo motor start rotating - 	Implemented.

HLR3 : As the servo motor start rotating the solar panels also start rotating in the direction of sun -	Implemented.

## Low Level Requirements

LLR1: when sensor detects the light,as the direction of the light changes servo motor also changes the position -Implemented. 

LLR2: LDR senser takes the value of intensity and give it to the muc to change the position of solar panel -	Implemented.

LLR3: LDR sensor should sence the light and helps to get the electricity fronm the solar irradiations-	Implemented.

-----------------------------

   ### simulation Sample module.

![solar](https://user-images.githubusercontent.com/98837660/157020611-2a4a2400-b782-4b6d-aeba-aa8885e7a35b.png)

## Flow chart
  
  ![image](https://user-images.githubusercontent.com/98837660/157019990-1d54e69b-4094-40c4-8ff5-736f7e62114e.png)


  
 ## Algorithm
 
Step1:start

step2: LDR Sesnser sense the solar irradiations and gives the input to the MCU.

Step3: we are going to connect the LDR one pin to five potential units of every LDR

step4: another pin of LDR will go to the four analog pins of the microcontroller.

Step5:The microcontroller can calculate the typical voltage to LDR of every section such top to Bottom to left and Right.

Step6: From there microcontroller can commit to rotating the servo in step with the difference of 2 averages such prime and bottom average distinction and left right average distinction.

Step7: in step with the difference the position of servo are going to be

step8: Stop

  
