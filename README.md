# RP2040 ZERO 4x4 Mechanical Macropad

A custom-built, programmable 16-key mechanical macropad powered by the RP2040 ZERO. This project combines custom PCB design, 3D mechanical modeling, and embedded programming to create a versatile productivity tool.

## Features

* **4x4 Matrix Layout:** 16 fully programmable mechanical switches for shortcuts, macros, or media controls.
* **RP2040 ZERO:** High-performance microcontroller with native USB support.
* **Custom PCB:** Optimized layout for a compact footprint and reliable signal integrity.
* **3D Printed Enclosure:** A custom-designed case tailored specifically for the hardware assembly.
* **Customizable Firmware:** Easily adaptable for various workflows (streaming, coding, gaming).

## Hardware Specifications

| Component | Description |
| :--- | :--- |
| **Microcontroller** | RP2040 ZERO |
| **Switches** | 16x Mechanical Switches (MX-compatible) |
| **PCB** | Custom designed in KiCad |
| **Case** | 3D Printed (ONSHAPE) |
| **Connection** | USB-C |

## Getting Started

### Hardware Assembly
1.  **PCB Fabrication:** Order the PCB using the provided Gerber files in `/hardware/pcb`.
2.  **Soldering:** Solder the RP2040 ZERO and mechanical switches to the PCB.
3.  **Enclosure:** 3D print the top and bottom halves of the enclosure found in `/hardware/enclosure`.
4.  **Final Assembly:** Secure the PCB into the enclosure using M3 screws.

### Firmware Setup
1.  Connect the macropad to your computer via USB-C.
2.  Flash the firmware located in the `/firmware` directory using the Arduino IDE or by copying files if using C++.
3.  Configure your keymaps in the configuration file to match your desired shortcuts. S

### Schematic
<img width="723" height="773" alt="Screenshot 2026-04-26 220612" src="https://github.com/user-attachments/assets/163562a5-db28-47cc-8ffb-9b98b039bd78" />

### PCB  
<img width="1255" height="699" alt="Screenshot 2026-04-26 144108" src="https://github.com/user-attachments/assets/fc066361-cea1-43a6-8a3c-df0db4a030bb" />

### 3D Design
<img width="1253" height="1133" alt="image" src="https://github.com/user-attachments/assets/79a68ef5-7564-45c8-b953-bd5019df22f8" />

