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



