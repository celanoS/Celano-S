# Smart Watch Firmware

The Smart Watch firmware controls the wearable safety unit of the Smart Sea Belt system.

## Main Functions

- GPS location monitoring
- Heart-rate monitoring
- Motion detection
- Fall detection
- SOS button monitoring
- Emergency alert generation
- BLE communication with the Boat Hub
- Buzzer and vibration alerts

## Sensors and Modules

| Module | Function |
|---|---|
| ESP32-C3 | Main controller and BLE communication |
| GPS | Location tracking |
| MAX30102 | Heart-rate monitoring |
| MPU6050 | Motion and fall detection |
| SOS Button | Manual emergency activation |
| Buzzer | Audible alert |
| Vibration Motor | Silent emergency alert |

## Firmware Flow

Sensors
↓
ESP32-C3
↓
Data Processing
↓
Emergency Detection
↓
BLE
↓
Boat Hub

## Emergency Conditions

The firmware monitors for:

- Manual SOS activation
- Abnormal heart-rate conditions
- Sudden fall or unusual motion
- Loss of communication

When an emergency condition is detected, the watch activates local alerts and sends the relevant information to the Boat Hub.

## Communication

The Smart Watch communicates with the Boat Hub using Bluetooth Low Energy (BLE).
