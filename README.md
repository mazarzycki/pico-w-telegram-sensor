# Pico W Telegram Sensor

A MicroPython-based IoT project using a Raspberry Pi Pico W,
Wi-Fi connectivity, and the Telegram Bot API.

The goal is to build a standalone sensor device that detects
physical events and sends notifications through Telegram.

## Project status

### Completed
- [x] Install MicroPython on Raspberry Pi Pico W
- [x] Configure Thonny on Linux Mint
- [x] Control the onboard LED
- [x] Connect to Wi-Fi
- [x] Send Telegram messages

### Planned
- [ ] Read distance measurements from an HC-SR04 sensor
- [ ] Detect movement using sensor readings
- [ ] Implement alert thresholds and cooldowns
- [ ] Send automatic Telegram notifications
- [ ] Run independently using USB power
- [ ] Implement error handling and reconnection logic
- [ ] Add automated tests

## Hardware

- Raspberry Pi Pico W (RP2040)
- HC-SR04 ultrasonic distance sensor
- Breadboard and jumper wires
- USB power supply

## Technologies

- Python / MicroPython
- Raspberry Pi Pico W
- Wi-Fi
- Telegram Bot API
- HTTP/HTTPS
- Linux

## Documentation

See `docs/pico-w-telegram-setup-guide.md` for the complete
setup instructions and troubleshooting walkthrough.
