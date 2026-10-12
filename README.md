# ESP32 IR Remote Controller | Custom PCB Design

## Project Overview

This project focuses on developing an ESP32-based infrared remote controller capable of receiving, decoding, storing, and transmitting infrared signals.

I initially developed and tested the circuit using a breadboard before transitioning to a custom PCB design using KiCad.

The goal of this project is to gain hands-on experience with electronics, microcontrollers, PCB layout, and hardware development.

## Components and Software

- ESP32 Development Board
- Infrared Receiver and Transmitter
- Tactile Push Buttons
- Resistors and Breadboard
- KiCad PCB Design Software
- Arduino IDE
- Arduino IRremote Library

## Project Development

### Phase 1: Breadboard Prototyping

Developed a working ESP32-based circuit capable of receiving and decoding infrared signals using the Arduino IRremote library.

Implemented functionality for storing received infrared commands and transmitting them through an infrared LED.

### Phase 2: Custom PCB Design

Designed a custom PCB using KiCad to transition the project from a breadboard prototype to a more permanent hardware platform.

The PCB design includes:

- ESP32 development board connections
- Infrared receiver and transmitter connections
- Four tactile push buttons
- Copper trace routing and ground planes
- Component footprints and placement
- Design Rule Check (DRC) verification

### Phase 3: Manufacturing and Assembly

The PCB design has been prepared for manufacturing. The next stage involves assembling the physical components and testing the completed board.

## Skills Demonstrated

- Printed Circuit Board (PCB) Design
- KiCad
- Circuit Prototyping
- Electronic Troubleshooting
- ESP32 Microcontroller Development
- Hardware Design and Verification

## Future Improvements

- Assemble and test the manufactured PCB
- Verify button functionality and infrared transmission
- Improve the PCB layout based on physical testing
- Explore a more compact handheld enclosure



### Circuit Schematic

The schematic shows the ESP32 GPIO connections, IR receiver and transmitter connections, and four tactile push buttons.

![ESP32 Circuit Schematic](Screenshot%202026-10-12%20172210.png)

### PCB Layout and Routing

The PCB was designed in KiCad using front and back copper layers, component placement, copper trace routing, and ground planes.

![KiCad PCB Layout](Screenshot%202026-10-12%20170654.png)

### PCB 3D Visualization

The 3D model shows the physical PCB design and component placement.

![ESP32 PCB 3D View](Screenshot%202026-10-08%20183120.png)

