SMART SEA BELT

An Integrated Wearable Marine Safety System for Fishermen

Project Overview

Smart Sea Belt is an integrated wearable marine safety system designed to protect fishermen during emergencies at sea.

The system uses smart watches equipped with GPS, heart-rate and motion sensors, SOS functionality, and automatic flotation deployment. The watches communicate with a central Boat Hub using Bluetooth Low Energy (BLE).

The Boat Hub monitors fishermen, detects emergency conditions and possible man-overboard situations, and communicates critical information through long-range LoRa to a Base Unit and cloud platform.

An AI-enabled mobile application provides real-time tracking, emergency alerts, and safety monitoring. The system also incorporates a rudder-based diversion mechanism to support faster emergency response.

Objectives

- Improve fishermen's safety during emergencies at sea
- Enable real-time monitoring of fishermen
- Detect possible man-overboard and emergency conditions
- Provide rapid emergency alerts
- Support automatic flotation deployment
- Enable long-range communication using LoRa
- Provide location tracking using GPS
- Develop an affordable, lightweight, and scalable safety solution

Key Technologies

- ESP32
- GPS / NavIC
- Bluetooth Low Energy (BLE)
- LoRa
- MAX30102 Heart-Rate Sensor
- MPU6050 Motion Sensor
- IoT
- AI-assisted monitoring
- Mobile Application
- Automatic Flotation Deployment
- Rudder Diversion Mechanism

System Architecture

Smart Watch
     |
     | BLE
     v
Boat Hub
     |
     | LoRa
     v
Base Unit
     |
     v
Cloud Platform
     |
     v
Mobile Application

Main Components

Smart Watch

The wearable unit monitors the fisherman's condition using:

- GPS
- Heart-rate sensor
- Motion sensor
- SOS button
- Buzzer / vibration alert
- Flotation deployment mechanism

Boat Hub

The Boat Hub acts as the central communication and monitoring unit. It receives data from smart watches through BLE and transmits important information using LoRa.

Base Unit

The Base Unit receives long-range data from the Boat Hub and can forward information to the monitoring platform.

Mobile Application

The application provides:

- Real-time location tracking
- Fisherman status
- Emergency alerts
- Safety monitoring
- Data visualization

Emergency Detection

The system can monitor sensor information to identify possible emergency conditions such as:

- SOS activation
- Abnormal motion
- Possible fall or man-overboard condition
- Abnormal heart-rate readings
- Geofence-related alerts

Safety Mechanisms

The system incorporates:

1. Automatic flotation deployment
2. Emergency alerts
3. GPS-based location monitoring
4. Rudder-based diversion mechanism
5. Long-range LoRa communication

Project Status

This repository contains the documentation, design, software, hardware information, prototype details, and testing results of the Smart Sea Belt project.

Features are classified as implemented, tested, or proposed based on the current prototype development stage.

Future Scope

- Improved AI-based anomaly detection
- Cloud-based monitoring
- Mobile application enhancement
- Improved marine communication
- Advanced geofencing
- Integration with emergency response authorities
- Large-scale field testing

Team

Project: Smart Sea Belt
Author: Celano S
Department: MBA
Institution: Rohini College of Engineering and Technology
