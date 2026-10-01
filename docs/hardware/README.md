Hardware

This folder contains the hardware design and component information for the Smart Sea Belt system.

Hardware Modules

1. Smart Watch

The wearable unit is designed to monitor the fisherman's condition and provide emergency assistance.

Main components:

- ESP32-C3
- GPS module
- MAX30102 heart-rate sensor
- MPU6050 motion sensor
- SOS button
- Buzzer / vibration alert
- Flotation deployment mechanism
- Rechargeable battery

2. Boat Hub

The Boat Hub acts as the central communication and monitoring unit on the boat.

Main components:

- ESP32-S3
- GPS / NavIC
- Bluetooth Low Energy (BLE)
- LoRa communication module
- OLED / display
- Buzzer
- Rudder actuator interface
- Power supply

3. Base Unit

The Base Unit receives information from the Boat Hub through long-range communication.

Main components:

- ESP32 / compatible controller
- LoRa receiver
- Display
- Alert system
- Power supply

Communication

Smart Watch
     |
     | BLE
     v
Boat Hub
     |
     | LoRa
     v
Base Unit

Note

Component specifications and quantities may vary according to the prototype version and future development.
