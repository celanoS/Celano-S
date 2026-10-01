Boat Hub

The Boat Hub is the central monitoring and communication unit of the Smart Sea Belt system. It receives information from the fishermen's Smart Watches through Bluetooth Low Energy (BLE), processes the data, and transmits critical information through long-range LoRa communication.

Main Components

Component.           Purpose
ESP32-S3.            Main controller and data processing
GPS/NavIC.           Location tracking
BLE.                 Communication with Smart Watches
LoRa Module.         Long-range communication
OLED/Display.        Local status information
Buzzer.              Emergency notification
Rudder Actuator.     Supports diversion mechanism
Power Supply.        Provides operating power

Working Principle

Smart Watches
      |
      | BLE
      v
  ESP32-S3
      |
      +---- Sensor Data
      +---- Emergency Status
      +---- GPS Data
      |
      v
 Emergency Processing
      |
      +----------+
      |          |
      v          v
    LoRa      Rudder
      |       Mechanism
      v
  Base Unit

Functions

- Receive Smart Watch data through BLE
- Monitor fishermen's safety status
- Process sensor and emergency information
- Monitor location
- Generate local emergency alerts
- Transmit critical information through LoRa
- Interface with the rudder diversion mechanism

Communication

The Boat Hub acts as the communication bridge between the wearable Smart Watches and the Base Unit.

Smart Watch → BLE → Boat Hub → LoRa → Base Unit

Development Status

The Boat Hub is designed as the central communication and processing unit of the Smart Sea Belt prototype. Communication, emergency detection, and actuator functions should be validated independently before integrated field testing.
