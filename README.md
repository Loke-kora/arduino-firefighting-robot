# arduino-firefighting-robot
Autonomous robot that detects and extinguishes fires using Arduino UNO and flame sensors
PROPOSED METHOD
This proposed firefighting robot system is designed for rapid fire detection and localized suppression in 
indoor environments. Utilizing an Arduino Uno as its central processing unit, the robot integrates an IR 
sensor array for efficient flame detection. Upon sensing a fire signature, the Arduino triggers a series of 
actions. The robot's mobility is achieved through gear motors, enabling it to navigate towards the fire source. 
A compact water tank, integrated into the robot's main body, supplies the fire suppression system. A servo 
motor, controlled by the Arduino, precisely directs a spray nozzle to target the detected flames. The system 
prioritizes localized suppression, minimizing water usage and potential damage. The Adriano’s programming 
allows for customizable response patterns, including adjustable spray durations and motion algorithms, based 
on the intensity and location of the fire. The robot's compact design and responsive system make it suitable 
for deployment in confined spaces, offering a proactive approach to fire safety. Future iterations will 
incorporate a wireless communication module, allowing for remote monitoring and control via a mobile 
application. Additionally, the integration of a smoke sensor will enhance the robot's ability to detect fires in 
their early stages, and an obstacle avoidance system using ultrasonic sensors will improve navigation in 
complex environments. Finally, the inclusion of a feedback system, reporting water tank levels and fire 
suppression status, will ensure optimal operational awareness.
FIGURE 1. Block diagram of proposed system.
Ashok Reddy.et.al / Journal on Electronic and Automation Engineering, 4(2), June 2025, 94-98.
 Copyright@ REST Publisher 96
Working: The fire-fighting mobile robot operates autonomously to detect and extinguish fires in small to 
medium-sized environments. The robot continuously scans its surroundings using infrared (IR) sensors, 
which detect the infrared radiation emitted by flames. Once a fire source is detected, the robot activates its 
navigation system and begins moving toward the fire using motor-driven wheels controlled by an L298N 
motor driver. The on-board microcontroller (Adriano UNO) processes sensor data and adjusts the robot’s 
path accordingly to avoid obstacles and reach the fire source accurately. When the robot is within range, it 
activates a water pump mechanism mounted on an MG90S servo motor, which directs a stream of water 
toward the flame. After extinguishing the fire, the robot resumes its monitoring mode, ready to respond to 
any further threats. This automated cycle ensures quick response, minimal human intervention, and improved 
safety in environments like homes, offices, and industrial facilities.
