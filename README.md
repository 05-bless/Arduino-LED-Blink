Arduino-LED-Blink :
My first embedded systems project using Arduino to blink an LED.

Overview :
This project demonstrates basic embedded programming using Arduino to blink an LED.

Components Used :
 Arduino UNO
 LED
 Jumper wires
 Resistor(220Ω)

Working :
The Arduino sends HIGH and LOW signals to blink the LED at 1-second intervals.

Done by ;
BLESSIE M

Project Demonstration :
Watch video - https://drive.google.com/file/d/1CQujqaavrZ8QDy7qRy1vAtNZa6pED7nj/view?usp=drivesdk

Code :
int led1=7;

void setup()
{
//pinMode(pin,mode);
pinMode(7,OUTPUT);
 

}

void loop() 
{
digitalWrite(led1,HIGH);
delay(1000);
digitalWrite(led1,LOW);
delay(1000);


  
}

Learning Outcome :

Through this project, I learned:

 Basic microcontroller programming
 Digital output control
 Circuit connections and debugging
 Using GitHub for project documentation


