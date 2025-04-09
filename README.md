# Sentiment Feedback System Documentation

## Project Overview
This project implements a Raspberry Pi-based sentiment feedback system that dispenses rewards and prints messages using a servo motor and Bluetooth printer.

## Hardware Components
- Raspberry Pi 4 (Central Controller)
- SG90/MG996R Servo Motor
- Bluetooth Thermal Printer

For a detailed list of components with prices and links, see [Components List](components.md).

## Circuit Documentation
The circuit diagram and detailed wiring instructions can be found in the [Circuit Documentation](circuit_documentation.pdf).

## Setup Instructions
1. Connect the servo motor to the Raspberry Pi:
   - Signal wire to GPIO18
   - Power wire to 5V
   - Ground wire to GND

2. Configure the Bluetooth printer:
   - Pair with Raspberry Pi
   - Set up wireless communication

## Software Requirements
- Python 3.x
- RPi.GPIO library
- Bluetooth communication libraries

## Additional Resources
- [Circuit Diagram](circuit_documentation.pdf)
- [Wiring Guide](circuit_documentation.pdf#page=2)
- [Component Specifications](circuit_documentation.pdf#page=3) 