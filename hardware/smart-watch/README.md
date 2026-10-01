Smart Watch

The Smart Watch is the wearable safety unit of the Smart Sea Belt system. It monitors the fisherman's location and physical condition and provides an emergency communication interface.

Main Components

Component| Purpose
ESP32-C3| Main controller and BLE communication
GPS| Location tracking
MAX30102| Heart-rate monitoring
MPU6050| Motion and fall detection
SOS Button| Manual emergency activation
Buzzer / Vibration| Emergency notification
Flotation Mechanism| Emergency flotation support
Battery| Portable power supply

Working Principle

Sensors
   |
   v
ESP32-C3
   |
   +---- GPS Location
   |
   +---- Heart Rate
   |
   +---- Motion Data
   |
   +---- SOS Status
   |
   v
Emergency Detection
   |
   v
BLE Communication
   |
   v
Boat Hub

Functions

- Monitor heart rate
- Monitor movement
- Obtain location
- Allow manual SOS activation
- Provide local emergency alerts
- Send sensor information to the Boat Hub through BLE
- Support emergency flotation deployment

Communication

The Smart Watch communicates with the Boat Hub using Bluetooth Low Energy (BLE).

Development Status

The Smart Watch is part of the Smart Sea Belt prototype. Individual functions should be tested separately before integrated marine testing.
