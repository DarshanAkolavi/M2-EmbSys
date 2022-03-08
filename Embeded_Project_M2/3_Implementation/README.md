# Implementation 

## Testplan 

## High Level Requirements

HLR1 : The LDR sensor Detects the light intensity and give input to the MCU - Implemented.

HLR2 : The system take the input from the MCU and servo motor start rotating - Implemented.

HLR3 : As the servo motor start rotating the solar panels also start rotating in the direction of sun - Implemented.

## Low Level Requirements

LLR1: when sensor detects the light,as the direction of the light changes servo motor also changes the position -Implemented.

LLR2: LDR senser takes the value of intensity and give it to the muc to change the position of solar panel - Implemented.

LLR3: LDR sensor should sence the light and helps to get the electricity fronm the solar irradiations- Implemented.

## Pin Diagram of ATMega328

![atmega328 pin diagram](https://user-images.githubusercontent.com/98837660/157010100-89440b48-4998-435a-933b-ff39f487562e.jpg)

## design

![solartrack](https://user-images.githubusercontent.com/98837660/157010129-1a3f7abb-8a54-4ade-bdbd-6daad4dd5ee4.png)

## program

#include <Servo.h>

Servo myservo;                  
int ldr1 = 4;                       
int ldr2 = 5;                       
int val1;                             
int val2;                             
int pos=90;                               

void setup()                              
{
  myservo.attach(11);                                   
  Serial.begin(9600);                                     
  myservo.write(pos);                                            
}                                 

void loop()                                         
{                                       
  val1 = analogRead(ldr1);                                               
  val2 = analogRead(ldr2);                                      
  val1 = map(val1, 0, 1023, 0, 180);                                    
  val2 = map(val2, 0, 1023, 0, 180);                                         
  if(val1 > (val2+50))                                
  {                                       
    if(pos<180)                             
     pos=pos+1;                             
    myservo.write(pos);                               
    Serial.println("backward");                                             
    delay(10);                                        
  }                           
  else if(val2 > (val1+50))                               
  {                           
    if(pos>0)                           
     pos=pos-1;                           
    myservo.write(pos);                                 
    Serial.println("forward");                                             
    delay(10);                            
  }                             
                                                    
}                      
  
## circute diagram               
                    
![ckt of solar tracker](https://user-images.githubusercontent.com/98837660/157009248-4bdf6a07-4255-431e-9513-176396304979.jpg)
