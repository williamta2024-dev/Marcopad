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
## Bill of Materials (BOM)

Here is the list of components, hardware, and materials required to build this project:


| Item | Component / Part | Description | Qty | Est. Cost | Source / Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **1** | MACROPAD PCB-PTH_Y3 | The PCB | 3 | $\$7.80$ | [Link](https://cart.jlcpcb.com/shopcart/cartEdit/?id=4c4162048d664ba7a7ae664a28d13e49&type=1&changeType=1&achieveDate=48) |
| **2** | Estardyn RP2040-Zero RP2040 for Raspberry Pi Microcontroller PICO Development Board Module Dual-Core 2MB Flash |A raspberry pi for my macropad. | 1 | $\$6.71$ | [Link](https://www.aliexpress.us/item/3256811972442631.html) |
| **3** |20-100pc Mechanical Keyboard Switches Blue Red Brown Switch Customizable Hot-Swappable 3 Pins Cross Stem for Mechanical Keyboard |Keyswitches for the Macropad | 1 | $\$0.99$ | [Link](https://www.aliexpress.us/item/3256811652574937.html) |
| **4** | 10Pcs/lot M2 M2.5 M3 M3.5 M4 M5 M6 TM Screws Phillips Truss Mushroom Head Screw Black Plated Electronic Carbon Steel Screws| For the PCB to hold in place.| 1 | $\$1.57$ | [Link](https://www.aliexpress.us/item/32568019372843219.html) |
| **5** | 100PCS/LOT D0-35 1N4148 High-speed Switching Diodes | For the PCB | 1 | $\$1.14$ | [Link](https://www.aliexpress.us/item/3256802153601411.html) |
| **6** | N3UD 20Pcs PBT Blank Keycap 1U 1X XDA Profile No Print Keycap Set for DIY Mechanical Keyboard Installation MX Switches | Keycaps for the switches | 2 | $\$0.99$ | [Link](https://www.aliexpress.us/item/3256802153601411.html) |





