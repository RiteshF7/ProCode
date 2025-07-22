# ProCode
# USB Microcontroller for Elgorithm: Rapid Prototyping with Block-Based Programming

![Alt text](https://raw.githubusercontent.com/RiteshF7/ProCode/refs/heads/master/pro2.png)

![Alt text](https://raw.githubusercontent.com/RiteshF7/ProCode/refs/heads/master/pro1.jpg)


This project introduces a custom-designed USB-enabled microcontroller that seamlessly connects to the Elgorithm platform for rapid hardware prototyping. Designed with ease-of-use in mind, it supports serial communication, custom block extensions, and requires no external wiring—ideal for educational environments, makers, and quick iteration cycles.

## Overview

This microcontroller was designed from the ground up using:
- **Fusion 360** for 3D enclosure modeling
- **EasyEDA** for PCB schematics and layout
- **EasyPCB** for final PCB fabrication

It features:
- Native **USB support** for plug-and-play connectivity  
- **Serial communication** for controlling and programming through Elgorithm  
- **Custom Blockly blocks** mapped to each USB-connected module  
- Compact form factor with sleek, printable enclosure  
- Future-ready support for **magnet wire-based connection extensions**

## Features

- No jumper wires required — direct USB plug-in for instant prototyping  
- Fully integrated with Elgorithm block code via serial triggers  
- Supports NeoPixels, Servo motors, LEDs, and more via virtual-to-physical linkage  
- Enables low-latency hardware response through modular firmware design  
- Enclosure designed for efficient airflow and modular stacking  

## Getting Started

1. Connect the microcontroller via USB
2. Launch Elgorithm and enable USB communication blocks
3. Drag relevant blocks for hardware interaction (LEDs, Servo, etc.)
4. Upload sketch or firmware via Arduino IDE if needed (supports serial trigger mapping)
5. Begin prototyping immediately with live hardware response

## Supported Components

- NeoPixel LED strips  
- Servo motors  
- Single/dual LEDs  
- Push buttons (via block simulation)  
- More peripherals to be added

## Serial Communication

All block triggers in Elgorithm send serial commands over USB.
The microcontroller uses ESP8266 internally and micropython framwork.


## Enclosure and PCB

![Alt text](https://raw.githubusercontent.com/RiteshF7/ProCode/refs/heads/master/Schematic.png)

![Alt text](https://raw.githubusercontent.com/RiteshF7/ProCode/refs/heads/master/pcb.png)

- PCB designed using EasyEDA and fabricated by EasyPCB  
- 3D enclosure modeled in Fusion 360  
- Snap-fit casing with USB clearance and ventilation grid  
- Expansion slots designed for future magnetic connections

## Future Enhancements

- Add magnet wire integration for minimal-contact prototyping  
- Extend support for I2C and SPI peripherals  
- Develop visual debugger for real-time block-to-hardware tracing  
- Wi-Fi or BLE extensions for wireless Elgorithm blocks

## License

Open Hardware / MIT Software License  
Use and modify freely. Contributions welcome!
