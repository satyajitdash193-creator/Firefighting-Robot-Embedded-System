#  Firefighting Robot (Arduino Based)

## Overview
This project is an autonomous firefighting robot designed to detect fire using IR flame sensors and extinguish it using a water pump system.

##  Working Principle
The robot uses three flame sensors (left, front, right) to detect fire. Based on sensor input:
- It navigates toward the fire source
- Stops near the fire
- Activates a water pump
- Uses a servo motor to spray water in different directions

##  Components Used
- Arduino UNO
- L298 Motor Driver
- Flame Sensors (3)
- Servo Motor
- Water Pump
- DC Motors
- Battery

##  Code Explanation
- Sensor values are read using analog inputs
- Based on threshold values, movement decisions are made
- Servo motor controls water direction
- Pump activates when fire is detected

##  Demo Video
https://youtu.be/KxWK_hUpbQ8
##  Features
- Autonomous navigation
- Real-time fire detection
- Automatic extinguishing system

##  Future Improvements
- ESP32 + IoT monitoring
- AI-based fire detection
- Custom PCB design
