# Servo Control

This folder is for code related to servo actuation.

Possible contents:

- Arduino servo test code
- Raspberry Pi servo control scripts
- trigger logic scripts
- elevator angle calibration

Initial goal:

```text
Send a simple command → move servo → set elevator angle → record response
```

Suggested first test:

- neutral elevator: 0 degrees
- small pitch-up command: +10 degrees
- maximum test command: +15 degrees

The exact elevator angle should be adjusted based on flight testing and structural limits.
