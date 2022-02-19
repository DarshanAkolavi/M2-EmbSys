# 1) simple Embeded System 

  ## Microwave Oven
  ## Block Diagram 
  ![Microwave oven-Page-1 drawio (1)](https://user-images.githubusercontent.com/98837660/154812572-7f47224f-7f55-4053-b34e-b7bd8315715b.png)

## Components

## Microcontroller Unit
Microcontrollers are used in automatically controlled products and devices, such as automobile engine control systems, implantable medical devices.
An 8-bit AVR microcontroller is used as the processing unit.It also has programmable general purpose input/output (GPIO) lines, Timers.

## Curent Limiter( Thyristore)
   Thyristor are current operated devices, a small Gate current controls a larger Anode current. Conducts current only when forward biased and triggering current applied to the Gate. The thyristor acts like a rectifying diode once it is triggered “ON”. 
## Power Converters
A converter is an electrical circuit which accepts a DC input and generates a DC output of a different voltage, usually achieved by high frequency switching action employing inductive and capacitive filter elements.
## Touchless and Proximity Sensors
Proximity Sensors detect an object without touching it, and they therefore do not cause abrasion or damage to the object. Devices such as limit switches detect an object by contacting it, but Proximity Sensors are able to detect the presence of the object electrically, without having to touch it
# wireless Connectivity
A wireless network is a computer network that uses wireless data connections between network nodes.Examples of wireless networks include cell phone networks, wireless local area networks (WLANs), wireless sensor networks, satellite communication networks, and terrestrial microwave networks.
## Sensing Unit
### Temparature Sensor And Humidity Sensor
This sensor gives temperature value to microcontroller and A humidity sensor is an electronic device that measures the humidity in its environment and converts its findings into a corresponding electrical signal. 
## Signal Conditioning
* Signal conditioning is the manipulation of a signal in a way that prepares it for the next stage of processing. Many applications involve environmental or structural measurement, such as temperature and vibration, from sensors.
* These sensors, in turn, require signal conditioning before a data acquisition device can effectively and accurately measure the signal.
# power Switches
A Power Switch provides an electrical connection from a voltage source or ground to a load. It saves
power across multiple voltage rails and protects subsystems from damage. It also provides enhanced
component protection, inrush current protection, and minimizes printed-circuit board (PCB) size.
### Switch 
There are two switches one switch is connected to the GPIO pin of the microcontroller so that it reads the status of the door.The other door switch is connected to the path of the AC circuit so that current can flow to the magnetron circuit when the door is closed.
### Relay and Buzzer
It is used to turn on/off the magnetron circuit and the motor is conneted to the relay.
When the food is warmed the buzzer will indicate in the form of sound.

## High Level Requirements
  1.Touchless and Proximity Sensors.  
  2.Power input to the sysytem.     
  3.Weaight of the Micro-owen.             
  4.Temperature sensor and Humidity Sensors to check temperature of the food(Sensing Unit).             
  5.Wireless connectivity for sensing and aoperating the sysytem.                
  6.Curent Limiter(THyristore)for controlling the input current for the device.

## Low Level Requirements  
  1.plate lamp ,Fan,Door locker.              
  2.at the desired temperature we get the Buzzer sound and led display from The Device.            
  3.A microcontroller inside the microwave monitors what button we pushed and updates the display.                
  4.safety look and user friendly.

# 2) A mid level to Complex Embeded System
 ## Washing Machine
 
 ## Block Diagram
![washing machine](https://user-images.githubusercontent.com/98837660/154815299-a135a932-55d6-47f7-8be0-3731eded1294.png)

 # components
 
 ## Water pump.
* This circulates the water through the machine, rotating in two directions. 
 * It’s used for circulating the water through the wash cycle and also for draining the water during the spin cycle. 

## Water inlet control valve. 
This is located near the water inlet point, which is opens and closes automatically when you load the clothes, depending on how much water is required. 

## Drum. 
* the clothes are loaded is the inner drum, which moves around the washing machine and is perforated with holes to allow the water in and out.
*  The outer tub contains the inner drum and the water, stopping it from leaking into the rest of the machine and supports the inner drum. 

## Agitator or paddles.
* This is located inside the tub of the washing machine and helps perform the cleaning of the clothes.
*  Most fully-automatic washing machines have these paddles on the rotating inner drum which is controlled by a rotating disc, whereas semi-automatic washing machines use an       agitator that rotates within the machine to produce a current in the machine.
*  Either way, these are designed to move the clothes around during the wash to allow the detergent to work and remove dirt particles and soiling from your clothes, helping the clothes rub together while washing. 

## Washing machine motor. 
This is combined with the agitator or the disc that turns the drum, it produces a rotator motion. This is basically the mechanism that gets your machine going. 

## Drain pipe.
All the dirty water from your washing is expelled from the machine via the drain pipe. 

## Printed circuit board (PCB).
This is where you’ll find mainly the electronics that operate the machine from electrical components to circuits. These can be programmed and help operate the machine, acting as the artificial intelligence for the washing machine, sometimes even deciding on the time needed for rinsing or washing. 

## Timer. 
This helps set the wash time for your clothes, which can be set manually or automatically. 

## Heating element.
This heats the water up in the washing machine to the desired temperature. 

## High Level Requirements
  1.washing machine processes are electrically controlled, such as the drum, valves, pump, motor and heating           
  2.Touchless and Proximity Sensors.             
  3.The thermostat measures the water coming into your washing machine and may heat up the water using the heating element to the required temperature.               
  4.The programmer in the machine opens the valves to let the hot and cold water into the machine, this then fills both drums up .                   
  5.Wireless connectivity for sensing and operating the sysytem.                 

## Low Level Requirements             
  1. Detergent for removing the dirt from the clothes, and pulls it into the water.                     
  2. The inner drum begins to rotate back and forth, mixing the clothes up in the warm, soapy water, agitating them to help remove stains and soiling                     
  3. safety look and user friendly.


