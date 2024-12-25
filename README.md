# Bluetooth-Controlled-Light

Bluetooth Controlled Light Using Arduino (Register-Level Programming)
This project demonstrates how to control an LED using a Bluetooth module (HC-05) and an Arduino, with register-level programming. The code directly interacts with the microcontroller's registers to set the LED pin as output and receive data from the Bluetooth module via UART, providing fine-grained control over hardware.

# Features
Bluetooth Communication: Sends commands via Bluetooth to control the LED state.
Register-Level Programming: Utilizes direct register manipulation (PORTB, DDRB, UCSR0A, etc.) for configuring pins and UART communication.


# Commands
Send 1 to turn the LED ON, and 0 to turn the LED OFF.


# Components Used

Arduino Uno (or compatible)

HC-05 Bluetooth Module

LED and Resistor

# Connections

HC-05 to Arduino:

TX → RX (Pin 0)

RX → TX (Pin 1)

VCC → 5V

GND → GND

# Potential Enhancement and Future Applications

### Mobile App Integration:
Developing a dedicated mobile app to control multiple devices or lights, enhancing usability.

### Multi-Device Control:
Extending the system to control more than one light or device simultaneously with different Bluetooth-enabled devices.

### Voice Control:
Integrating with voice assistants like Google Assistant or Alexa through Bluetooth-enabled gateways.

### IoT Integration:
Connecting the system to cloud platforms or smart home ecosystems for automation and remote control over the internet.
