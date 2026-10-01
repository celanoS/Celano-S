# Base Unit Firmware

The Base Unit firmware manages the receiving and monitoring functions of the Smart Sea Belt system.

## Main Functions

- Receive data from the Boat Hub
- Process incoming LoRa messages
- Display safety information
- Generate emergency alerts
- Monitor communication status
- Prepare data for future cloud connectivity

## Main Components

| Component | Function |
|---|---|
| ESP32 / Controller | Data processing |
| LoRa Module | Receives data from Boat Hub |
| Display | Shows system status |
| Buzzer | Emergency notification |
| Power Supply | Provides operating power |

## Firmware Flow

Boat Hub
↓
LoRa
↓
Base Unit
↓
Data Processing
↓
Display / Alert
↓
Monitoring Platform

## Emergency Monitoring

The Base Unit can receive and display:

- Fisherman ID
- Emergency status
- Location information
- Heart-rate alerts
- Motion-related alerts
- SOS alerts
- Communication status

## Future Development

Future versions may support:

- 4G connectivity
- MQTT
- Cloud database
- Web dashboard
- Remote monitoring
- Data analytics
