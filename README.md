# DigitalAmplifier

High-performance Class-D audio amplifier project based on the TPA3255 platform with Post-Filter Feedback (PFFB), combined with a dedicated DSP subsystem powered by STM32F446.

The project aims to deliver a compact and fully integrated stereo amplifier capable of 2×75 W output power while combining modern digital signal processing with high audio performance and efficient power conversion.
---

# Main Features

## Audio & Electronics

- Class-D topology based on TPA3255
- Post-Filter Feedback (PFFB) architecture
- DSP processing using STM32F446
- 2×75 W RMS output power
- THD+N: TBD after laboratory measurements
- IMD: TBD after laboratory measurements

## Connectivity & User Interface

- USB Type-C input
- S/PDIF input
- RCA line input
- PREOUT output
- 3.83" OLED display
- IR remote control

## Mechanical Design

- Aluminum enclosure
- Glass front panel

---

# Hardware Overview

## Amplifier PCB
![Amplifier PCB](img/mainboard.jpg)

## Front Panel PCB
![Front Panel PCB](img/front_panel.jpg)

## Power Supply PCB
![Power Supply PCB](img/psu.jpg)

---

# Complete Amplifier Assembly

![Complete Amplifier](img/amplifier.jpg)

---

# Project Status

Current development progress:
- [x] First hardware iteration completed
- [ ] CAD model finalization
- [ ] Mechanical integration
- [ ] Firmware and DSP implementation
- [ ] Thermal validation
- [ ] EMC validation
- [ ] ESD robustness testing
- [ ] Full system testing

---

# Technologies Used

- KiCad
- STM32CubeIDE
- LTspice
- ARM Cortex-M4 Embedded C
- DSP simulation in Python
- Autodesk Fusion

---

# Repository Structure

```text
DigitalAmplifier/
├── hardware/
├── firmware/
├── spice/
└── README.md
```

---

# Credits

Special thanks to [@vivadela](https://github.com/vivadela) for valuable support with the CAD design and mechanical development of the project.
---

# Support the Project

If you find this project interesting or useful and would like to support its development, you can make a voluntary donation:

☕ http://buycoffee.to/sskrzypik03

Your support helps cover the costs of PCB manufacturing, prototyping and components.
