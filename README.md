# 🔥 Arduino-Based Firefighting Robot

## 📋 Project Overview

An autonomous firefighting robot built using Arduino UNO that can detect fires using flame sensors and extinguish them automatically. The robot navigates autonomously, detects fire sources, and activates a water pump or fan to extinguish the flames.

**Project Duration:** February 2025 - April 2025  
**Status:** ✅ Completed

## 🎯 Objectives

- Design an autonomous robot capable of detecting and responding to fire
- Implement flame detection using IR flame sensors
- Program navigation logic for obstacle avoidance
- Integrate fire extinguishing mechanism with relay control
- Achieve fast response time (<2 seconds from detection to action)

## ✨ Features

- ✅ Autonomous fire detection using multiple flame sensors
- ✅ Obstacle avoidance using ultrasonic sensors
- ✅ Automatic navigation toward fire source
- ✅ Water pump activation for fire extinguishing

## 🛠️ Hardware Components

| Component | Quantity | Specification | Purpose |
|-----------|----------|---------------|---------|
| Arduino UNO | 1 | ATmega328P | Main controller |
| Flame Sensor | 3 | IR-based | Fire detection (left, center, right) |
| Ultrasonic Sensor | 1 | HC-SR04 | Obstacle detection |
| DC Motors | 2-4 | 100-200 RPM | Wheel drive |
| Motor Driver | 1 | L298N / L293D | Motor control |
| Water Pump | 1 | 5V/12V DC | Fire extinguishing |
| Relay Module | 1 | 5V, 1 channel | Pump control |
| Chassis | 1 | Robot base | Mounting platform |
| Wheels | 4 | - | Movement |
| Battery | 1 | 9V or 12V Li-ion | Power supply |
| Jumper Wires | - | Male-Male, Male-Female | Connections |


 ## Working 
The fire-fighting mobile robot operates autonomously to detect and extinguish fires in small to 
medium-sized environments. The robot continuously scans its surroundings using infrared (IR) sensors, 
which detect the infrared radiation emitted by flames. Once a fire source is detected, the robot activates its 
navigation system and begins moving toward the fire using motor-driven wheels controlled by an L298N 
motor driver. The on-board microcontroller (Adriano UNO) processes sensor data and adjusts the robot’s 
path accordingly to avoid obstacles and reach the fire source accurately. When the robot is within range, it 
activates a water pump mechanism mounted on an MG90S servo motor, which directs a stream of water 
toward the flame. After extinguishing the fire, the robot resumes its monitoring mode, ready to respond to 
any further threats. This automated cycle ensures quick response, minimal human intervention, and improved 
safety in environments like homes, offices, and industrial facilities.
