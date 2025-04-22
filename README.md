# Task 2: Bluetooth-Controlled Home Automation

## Description
This project allows users to control home appliances like lights or fans using Bluetooth communication via a mobile app. The system uses a microcontroller and a Bluetooth module (HC-05) to switch devices on or off remotely. Developed as part of my Embedded Systems Internship at Elite Tech Intern.

## Components Used
- PIC16F877A Microcontroller
- HC-05 Bluetooth Module
- Relay Module
- LEDs / Loads
- MPLAB X IDE

## Circuit Diagram
![Circuit](circuit.png)

## Code
See [main.c](main.c)

## Working
- Connect your phone to HC-05 via Bluetooth
- Send commands like ‘1’ to turn ON and ‘0’ to turn OFF
- The microcontroller receives the signal and controls the output

## Author
Rajesh
