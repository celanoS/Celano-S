# Base Unit

The Base Unit is the shore-side monitoring and control unit of the Smart Sea Belt system. It receives critical information from the Boat Hub through long-range LoRa communication and provides monitoring and alert functions.

## Main Components

| Component | Purpose |
|---|---|
| ESP32 | Main controller and data processing |
| LoRa Module | Long-range communication with Boat Hub |
| LoRa Antenna | Improves communication range |
| Display | Shows system and emergency information |
| Buzzer | Provides audible emergency alerts |
| Power Supply | Provides electrical power to the unit |

## Working Principle

The Boat Hub collects information from the fishermen's Smart Watches and transmits important information to the Base Unit through LoRa communication.

The Base Unit receives the data, processes the information, and provides alerts when an emergency condition is detected.

## Communication

Boat Hub → LoRa → Base Unit

## Emergency Monitoring

The Base Unit can be used to monitor:

- Fishermen emergency alerts
- Location information
- Health-related alerts
- Communication status
- System status

## Future Development

Future versions may include:

- 4G connectivity
- MQTT communication
- Cloud monitoring
- Web dashboard
- Remote data logging
