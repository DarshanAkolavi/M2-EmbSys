
## Report on Sun tracking solar panal uning microcontroller.
 
## Table of Contents

 1.0 Introduction.  
	
 2.0 Requirements 
	
  2.1 Swot Analysis 
		 
  2.2 Components Used In Solar Tracker	
		 
  2.3 5w's And 1H	
		 
  2.4 Table Of Requirements.	
		 
 3.0 Architecture.
	
 4.0 Simulation and Output.
	
 5.0 Advantages and Usage.		
	
 6.0 Applications and Scope.		
	
 7.0 Conclusion.					


# SUN TRACKING SOLAR PANEL
 
 ##
* To track the sun's position and rotate the panel according to the sun's position and receive the
    sunlight at its fullest potential during the daytime.
 * Solar panel absorbs the energy from the Sun, converts it into electrical energy, and stores the energy in a battery.            
 * The position of the Sun with respect to the solar panel is not fixed due to the rotation of the Earth. 
 * For efficient usage of solar energy, the Solar panels should absorb energy to a maximum extent.           
 * This can be done only if the panels are continuously placed towards the direction of the Sun. So, the solar panels should continuously rotate in the direction of the Sun.
 
 -----------------------------------------------------------------------------------------------------------------------------------
 # Block Diagram
 
 ![suntrack](https://user-images.githubusercontent.com/98837660/155653661-4c425b43-ac22-444f-9317-290a224b35e2.png)
--------------------------------------------------------------------------------------
 
 # Working Of Solar panel Tracker 
 
 * The Sun tracking solar panel consists of two LDRs, a solar panel, a servo motor, and an ATmega328 Microcontroller.
 * Two light-dependent resistors are arranged on the edges of the solar panel. 
 * Light-dependent resistors produce low resistance when light falls on them. The servo motor connected to the panel rotates the panel in the direction of the Sun. 
 * Panel is arranged in such a way that light on two LDRs is compared and the panel is rotated towards LDR which have high intensity i.e. low resistance compared to other. 
 * Servo motor rotates the panel at a certain angle.
 * When the intensity of the light falling on the right LDR is more, the panel slowly moves towards the right and if intensity on the left LDR is more, 
   the panel slowly moves  towards the left. 
 * In the noontime, Sun is ahead and the intensity of light on both the panels is the same. In such cases, the panel is constant and there is no rotation.
-------------------------------------------------------------------------------

 ## High Level Requirement : 
  * ATMEGA328
  * LDR Sensers
  * Servo Motor And DC Motor
  * Solar Panel
 
 ## Low Level Requirements :
  * transistors
  * Spectrum Analyzer
  * resistrors
  * Push Button
  ------------------------------------------------------------------------------
 
 ## Components Required :

 ## ATMEGA328
   * ATmega328 is an AVR family microcontroller. It is based on advanced RISC architecture.
   * It is an 8-bit controller. It has 32K Bytes of Programmable Flash memory, 1K Bytes of EEPROM, and 2K Bytes of SRAM.
   * It has 23 programmable I/O pins. It supports peripheral features like two 8-bit timers, one 16-bit timer, 6 channel ADC with 10-bit resolution, programmable USART, Serial      Peripheral Interface, 2 wire serial interface (I2C), etc.
  
 ## Sensors:
  * Light Dependent Resistors or LDRs are the resistors whose resistance values depend on the intensity of the light.
  *  As the intensity of light falling on the LDR increases, the resistance value decreases. In dark, LDR will have maximum resistance. 
  *  LDR will output an analog value which should be converted to digital. This can be done using analog to digital converter.
 
 ## Solar Panel
 
 * Solar panel is placed on a piece of cardboard (just for demonstration) and the bottom of the cardboard is connected to Servo motor. 
 * Solar panel consists of photovoltaic cells arranged in an order. A photovoltaic cell is nothing but a solar cell.
 *  Solar cell is made up of semiconductor material silicon.

 ## switch or gate for electronic signals.
 
 * transistor, semiconductor device for amplifying, controlling, and generating electrical signals.
 * we think that BC547 is a normal NPN (Negative-Positive-Negative) junction transistor. 
   
## Servo Motor
* Servo motor is used to rotate the panel. To drive the servo motor, a PWM Signal must be provided to its control pin, and hence Pin 17 (which has PWM) is connected to the control pin of the servo motor.
* By connecting a battery to the solar panel, you can store the energy generated by the solar cells and this energy can be used when required.
*  There are separate charge controller circuits dedicated to efficiently controlling the charge acquired from solar panels and charging the batteries.

## Resistors.
  
 * A resistor is a passive two-terminal electrical component that implements electrical resistance as a circuit element.
 * In electronic circuits, resistors are used to reduce current flow, adjust signal levels, divide voltages, bias active elements, and terminate transmission lines,             among other uses.
* Resistors are common elements of electrical networks and electronic circuits and are ubiquitous in electronic equipment. 
* Practical resistors as discrete components can be composed of various compounds and forms.
*  Resistors are also implemented within integrated circuits.

----------------------------------------------------------------------------------------

## 5W and 1H :
--------------------------------------------
 ## WHAT 
 * Sun tracking solar panel works on the sensing of the solar radiations which are detected by the LDR sensors, To track the sun's position and rotate the panel according to the sun's position and receive the sunlight at its fullest potential during the daytime.
 ------------------------------------------
 ## WHY
 * This can be done only if the panels are continuously placed towards the direction of the Sun. So, the solar panels should continuously rotate in the direction of the Sun.
 * so that the Solar trackers generate additional electricity in roughly an equivalent quantity of area required for fixed-tilt systems, creating them ideal for optimizing land usage.
 ------------------------------------------
 ## WHERE  
 * The sun-tracking solar panel can be used in  Hotels, Home apartments, Commercial complexes, Factories.
 * by the Advancements in technology and responsibility in natural philosophy and mechanics have drastically reduced long-run maintenance issues for pursuit systems.
 ---------------------------------------------
 ## WHEN
  * The Purpose of the sun-tracking solar panel is that the solar energy can be reused as it is a non-renewable resource.
  * This also saves money as there is no need to pay for energy used (excluding the initial setup cost).
  * Helps in maximizing solar energy absorption by continuously tracking the sun.
 -----------------------------------------------
 ## WHO
 * These panels can be used to power the traffic lights and streetlights
 * These can be used in the home to power the appliances using solar power.
 * These can be used in industries as more energy can be saved by rotating the panel.
  ------------------------------------------------     
 ## HOW
 * Panel is arranged in such a way that light on two LDRs is compared and the panel is rotated towards LDR which have high intensity i.e. low resistance compared to other. 
 * Servo motor rotates the panel at a certain angle.
 * When the intensity of the light falling on the right LDR is more, the panel slowly moves towards the right and if the intensity on the left LDR is more, the panel slowly moves towards the left. 
 * In the noontime, Sun is ahead and the intensity of light on both the panels is the same. In such cases, the panel is constant and there is no rotation.
------------------------------------------------------------------

## SWOT Analysis :
![image](https://user-images.githubusercontent.com/98837660/157150119-98e9dbfd-e010-4a4e-a427-d65b1fd4230a.png)

## STRENGTH
 * Easy installation.
 * Low maintenance.
 * Fully automatic, saves manpower.
 * Consume very little energy, ideal for continuous operation.

## WEAKNESS
  * Light Induced Degradation.
  * Degradation By Components.
  * Natural Degradation.
  * Poor Durability of The Panels.
  
## OPPORTUNITIES
 * Helps in maximizing solar energy absorption by continuously tracking the sun.
 * saving in electricity consumption.
 * long-term economic benefits.
 * Though solar energy can be utilized to the maximum extent this may create problems in the rainy season.
 *  solar energy can be saved to batteries, they are heavy and occupy more space, and are required to change from time to time.

## THREATS
  * change of solar panel.
  * Environmental Damages.
  * lack of maintenance 
  * lack of supply and replacement.
------------------------------------------------------------------
## Flow Chart
![image](https://user-images.githubusercontent.com/98837660/157151212-7f04c1a2-f553-4603-b915-f646cef09ec6.png)

------------------------------------------------------------------
## Algorithm

Step1: start

step2: LDR Sensor sense the solar irradiations and gives the input to the MCU.

Step3: we are going to connect the LDR one pin to five potential units of every LDR

step4: another pin of LDR will go to the four analog pins of the microcontroller.

Step5: The microcontroller can calculate the typical voltage to LDR of every section such top to Bottom to left and right.

Step6: From there microcontroller can commit to rotating the servo in step with the difference of 2 averages such prime and bottom average distinction and left right average distinction.

Step7: in step with the difference the position of servo is going to be

step8: Stop

-------------------------------------------------
## Testplan and Output

## High Level Requirements

HLR1 : The LDR sensor Detects the light intensity and give input to the MCU - Implemented.

HLR2 : The system take the input from the MCU and servo motor start rotating - 	Implemented.

HLR3 : As the servo motor start rotating the solar panels also start rotating in the direction of sun -	Implemented.

## Low Level Requirements

LLR1: when sensor detects the light,as the direction of the light changes servo motor also changes the position -Implemented. 

LLR2: LDR senser takes the value of intensity and give it to the muc to change the position of solar panel -	Implemented.

LLR3: LDR sensor should sence the light and helps to get the electricity fronm the solar irradiations-	Implemented.

------------------------------------------------
## 4.0 SIMULATION :

 Pin Diagram OF ATMega328
	
![atmega328 pin diagram](https://user-images.githubusercontent.com/98837660/157150659-bb306769-dd2a-4a20-8620-c8adaebde40b.jpg)

Simulation Model

![image](https://user-images.githubusercontent.com/98837660/157150863-5815d1df-d328-4af2-bbaf-46f71d268774.png)

Sample Model

![image](https://user-images.githubusercontent.com/98837660/157150933-5c0888c6-795f-4aec-8f82-03d62468fe2b.png)

-------------------------------------------------------


## Advantages :- 
##
 * solar energy can be reused as it is a non-renewable resource.
 * This also saves money as there is no need to pay for energy used (excluding the initial setup cost).
 * Helps in maximizing solar energy absorption by continuously tracking the sun.
 * Solar trackers generate additional electricity in roughly an equivalent quantity of area required for fixed-tilt systems, creating them ideal for optimizing land usage.
 * Advancements in technology and responsibility in natural philosophy and mechanics have drastically reduced long-run maintenance issues for pursuit systems. 
 1. Power Saver: Living in an age where we need to be more conscious of the energy that we use, a sun-tracking solar panel controller is ideal for saving power.
    However, with automatic controllers, electricity usage is also minimized.
 2. Money Saver: These devices accurately regulate how much energy is used to protect against any unnecessary electricity usage. Over time, the money saved is quite substantial.
 3. Automatic: Another notable advantage of these devices is that they regulate on their own.
 4. Reliable Electronic Design.    
 5. Easy Installation with LDR Monitoring.

## Disadvantages :

   ##
   1 They are a bit expensive.
   2 Though solar energy can be utilized to the maximum extent this may create problems in the rainy season.                
   3 Although solar energy can be saved to batteries, they are heavy and occupy more space, and are required changing time to time.               
   
---------------------------------------------------------------------
## Benefits:- 
 1. Easy installation.
 2. Minimal maintenance.
 3. Compact design.
 4. Save money by using less electricity and water.

## Applications:- 
 ##
* Hotels, Home apartments, Commercial complexes, Factories, etc.
* These panels can be used to power the traffic lights and streetlights.
* These can be used in the home to power the appliances using solar power.
* These can be used in industries as more energy can be saved by rotating the panel.
-------------------------------------
## Conclusion

The solar energy can be reused as it is a non-renewable resource. This also saves money as there is no need to pay for energy used (excluding the initial setup cost). Helps in maximizing solar energy absorption by continuously tracking the sun. Solar trackers generate additional electricity in roughly an equivalent quantity of area required for fixed-tilt systems, creating them ideal for optimizing land usage. Advancements in technology and responsibility in natural philosophy and mechanics have drastically reduced long-run maintenance issues for pursuit systems.



