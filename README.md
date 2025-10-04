# smart-dustbin
IoT-enabled smart dustbin with automatic lid control
# Smart Dustbin 

An Arduino-powered smart dustbin that automatically opens its lid when a person approaches.  
The system uses an ultrasonic sensor to detect distance and a servo motor to lift the lid.  

## Features
- Automatic lid opening using servo motor
- Ultrasonic distance sensing for user detection
- Hygienic and touch-free design
- Low-cost and easy to build with Arduino

## Components
- Arduino Uno (or compatible board)
- Ultrasonic Sensor (HC-SR04)
- Servo Motor (SG90)
- Jumper wires and power supply

## Working Principle
1. Ultrasonic sensor measures distance continuously.  
2. When an object (hand/person) is detected within a threshold (e.g., 20 cm), the Arduino triggers the servo.  
3. Servo motor rotates to lift the lid.  
4. After a short delay, the lid closes automatically.  


