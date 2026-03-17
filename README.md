# 🤖 HAKUHO Hardware

### ⚡ Custom Embedded Electronics for an Autonomous Sumo Robot

<p align="center">
  <img src="docs/Sumo.gif" width="500"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-in%20development-orange"/>
  <img src="https://img.shields.io/badge/MCU-STM32-blue"/>
  <img src="https://img.shields.io/badge/design-PCB-green"/>
  <img src="https://img.shields.io/badge/power-LiPo-red"/>
  <img src="https://img.shields.io/badge/version-Rev%20A-lightgrey"/>
</p>

---

## 📌 Overview

This repository contains the **hardware design** of the HAKUHO sumo robot.
It includes schematic design, PCB layout, power architecture, and integration of sensors and motor control systems.

The goal is to build a **compact, reliable, and high-performance embedded platform** for autonomous robotics competitions.

---

## 🚀 Key Features

* 🧠 STM32-based control system (Blue Pill compatible)
* 🔋 Li-Po battery powered architecture
* ⚡ 3.3V regulated logic rail (AMS1117-based)
* 🔁 Reverse polarity protection (MOSFET-based)
* 🛞 Dual motor driver (tank drive)
* 📡 VL53L0X distance sensors (I2C)
* ⚫ Line sensors for ring detection
* 📺 IR receiver interface
* 🧩 Custom PCB design

---

## 🧠 System Architecture

<p align="center">
  <img src="docs/system_block_diagram.png" width="600"/>
</p>

### Main Blocks:

* **Power Stage**

  * Battery input (Li-Po)
  * Protection (MOSFET)
  * Voltage regulation (5V → 3.3V)

* **Processing**

  * STM32 microcontroller

* **Sensing**

  * VL53L0X (I2C bus)
  * Line detection sensors
  * IR receiver

* **Actuation**

  * Dual motor drivers (left/right)

---

## 📂 Repository Structure

```bash
HAKUHO/
├── docs/              # diagrams, images, GIFs
├── schematics/        # .SchDoc files
├── pcb/               # PCB layout files
├── libraries/         # custom components (symbols + footprints)
├── production/        # Gerbers, BOM
└── README.md
```

---

## 🛠️ Design Tools

* 🧰 Altium Designer
* 🔧 SnapEDA (components)
* 💻 Git & GitHub
* ⚙️ STM32 ecosystem

---

## 📊 Current Status

* [x] System architecture defined
* [x] Component selection
* [x] Power regulation design
* [ ] Final schematic validation
* [ ] PCB routing
* [ ] Prototype fabrication
* [ ] Hardware testing

---

## 🧪 Hardware Specs

| Feature       | Value                       |
| ------------- | --------------------------- |
| MCU           | STM32F103C8T6               |
| Logic Voltage | 3.3V                        |
| Power Source  | Li-Po battery               |
| Motor Driver  | TB6612FNG                   |
| Sensors       | VL53L0X + IR + Line sensors |

---

## 🔮 Roadmap

* Improve power integrity
* Optimize PCB routing (return paths, EMI)
* Validate I2C multi-device architecture
* Build and test prototype
* Iterate to Rev B

---

## 📸 Preview

<p align="center">
  <img src="docs/pcb_preview.png" width="500"/>
</p>

---

## 📜 License

This project is currently under development.
License will be defined after first stable release.

---

## 👤 Author

**Mohamed Reda EZ-ZOUHRY**
Embedded Systems & Control Engineering Student

---
