# 📻 My Electronic Designs

This repository is a personal collection of **custom-designed electronic circuits**, devices, and embedded systems projects.  
Each subproject includes circuit schematics, PCB layouts, and where applicable, microcontroller programming logic.

---

## 💡 About the Author

Although I actively develop software and engage in systems programming, **my true strength lies in electronics and electrical engineering**—especially in circuit design, signal flow optimization, component-level analysis, and embedded systems.  
I'm especially skilled in **analog/digital interfacing**, **power calculation**, and **RF communication circuit design**.

---

## 🔧 Project Overview

| Project Name       | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| `6ChannelRadio`     | A custom 6-channel radio communication unit with modular signal routing     |
| `PocketRadio`       | Compact, battery-efficient radio prototype designed for field testing       |
| `RemoteController`  | An RF-based remote controller with hardware debouncing and address mapping  |

Each folder contains:
- PCB layout files (KiCad or similar)
- Schematic diagrams
- Bill of Materials (BoM)
- Test documentation or performance notes

---

## ⚙️ Capabilities Demonstrated

- 🔩 Circuit-level debugging  
- 📐 Precision in analog signal routing  
- 🔋 Power optimization & consumption modeling  
- 📶 RF transmission and shielding techniques  
- 🧠 Noise reduction, filtering, and hardware logic design  
- 🛠 Manual soldering, breadboard prototyping, and oscilloscope analysis

---

## 🧠 Example: Power Calculation Logic

For example, in `PocketRadio` I applied optimized current draw estimation:

```text
MCU: 3.3V @ 12mA  
RF Module: 3.3V @ 20mA (transmit), 8mA (receive)  
Total peak current: ~32mA → Chose LDO regulator with 100mA margin  
Battery life ≈ 800mAh / 32mA ≈ 25 hours of continuous use
