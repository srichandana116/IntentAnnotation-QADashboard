# IntentAnnotation-QADashboard
Advanced Intent Annotation and Quality Assurance Dashboard for Voice Command Data
# Annotation Guidelines – Smart Home Intent Dataset

## Intent Categories

- **TurnOnDevice**: User wants to activate a device.
  - Example: “Turn on the kitchen lights”
- **TurnOffDevice**: User wants to deactivate a device.
  - Example: “Switch off the living room fan”
- **SetTemperature**: User is setting the temperature.
  - Example: “Set the thermostat to 72 degrees”
- **OpenDevice**: User wants to open a physical object.
  - Example: “Open the garage door”
- **CloseDevice**: User wants to close a physical object.
  - Example: “Please close the window”
- **CheckDeviceStatus**: User is checking the status of a device.
  - Example: “Is the front door locked?”

## General Annotation Rules
- Use **only one intent per command**.
- Ignore filler words like “please”, “can you”, etc.
- When in doubt, prefer the **most generic intent** (e.g., `CheckDeviceStatus`).
