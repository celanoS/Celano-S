# Boat Hub Firmware

The Boat Hub firmware controls the central communication and monitoring unit installed on the fishing boat.

## Main Functions

- Receive data from Smart Watches
- Process sensor and emergency information
- Monitor communication status
- Transmit critical information to the Base Unit
- Generate local emergency alerts
- Manage BLE and LoRa communication

## Main Components

| Component | Function |
|---|---|
| ESP32-S3 | Main controller and data processing |
| BLE | Communication with Smart Watches |
| LoRa Module | Long-range communication with Base Unit |
| GPS | Boat location monitoring |
| Display | System and emergency status |
| Buzzer | Emergency notification |

## Firmware Flow

Smart Watches
↓
BLE
↓
ESP32-S3
↓
Data Processing
↓
Emergency Detection
↓
LoRa
↓
Base Unit

## Communication

### Smart Watch → Boat Hub
Uses Bluetooth Low Energy (BLE) for short-range communication.

### Boat Hub → Base Unit
Uses LoRa for long-range communication.

## Emergency Handling

The Boat Hub processes information received from the Smart Watches and identifies emergency conditions such as:

- SOS activation
- Abnormal heart-rate alerts
- Fall detection
- Communication failure

When an emergency is detected, the Boat Hub transmits the relevant information to the Base Unit.

## Future Development

Future firmware versions may support:

- 4G connectivity
- MQTT communication
- Cloud integration
- Remote monitoring
- Data logging
