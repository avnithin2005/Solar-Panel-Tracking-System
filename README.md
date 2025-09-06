# Solarpanel Tracking System

## Project Overview

This project is an automatic solar panel tracking system combined with an IoT-enabled relay switch.
* The Arduino UNO controls the solar panel tracking using LDR sensors and a motor driver.
* The ESP8266 (NodeMCU) is used for Wi-Fi control of a relay, allowing remote switching of connected appliances.

## Features
* Automatic solar tracking using LDRs
* Motorized movement for maximum sunlight capture
* Wi-Fi-based relay control (IoT-enabled)
* Low-cost and easy to implement
* Scalable for larger solar systems
  
## Components Used
* Arduino UNO
* ESP8266 (NodeMCU)
* LDR sensors (2 or 4) with resistors
* L298N Motor Driver
* DC Motor or Servo Motor
* Relay Module
* Solar Panel with Battery
* Wires, Breadboard, Power Supply

## Working Principle
* Solar Tracking
* LDR sensors detect sunlight intensity.
* Arduino compares sensor values.
* The motor rotates the panel toward maximum sunlight.

### IoT Relay Control
* ESP8266 connects to Wi-Fi.
* A simple web server or mobile app is used to control relay switching.
* The relay can turn appliances (fan/light) ON or OFF remotely.

## How to Run
1. Upload the Arduino program to Arduino UNO.
2. Upload the ESP8266 program using Arduino IDE.
3. Connect components as per the setup.
4. Use Serial Monitor or IoT app to test the system.

## Applications
* Renewable energy optimization
* IoT-enabled smart homes
* Solar farms
* Educational and research projects

## License
This project is open-source. You are free to use and modify it
