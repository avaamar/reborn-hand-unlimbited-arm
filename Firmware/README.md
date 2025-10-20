# Firmware (Optional)

If the prosthesis includes active control or sensors, this folder should contain the firmware source code.

## Structure
- `main.cpp` or `main.ino`: core firmware logic.
- `config.h`: pin definitions and calibration constants.
- `README.md`: brief build and upload instructions.

## Example upload command (Arduino)
```bash
arduino-cli compile --fqbn arduino:samd:adafruit_metro_m0
arduino-cli upload -p COMx --fqbn arduino:samd:adafruit_metro_m0
