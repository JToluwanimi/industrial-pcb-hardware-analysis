# Industrial PCB & RS485 Interface Analysis

> **Status:** Analyzed / Documented
> **Author:** Toluwanimi Jesusina

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-Completed-green)]()

---

## 1. What is this?

A technical deep-dive into the control board of an industrial Fire Alarm/Building Management System. This repository documents the terminal interfaces, communication protocols, and hardware architecture of the PCB.

---

## 2. Hardware Analysis

| Terminal | Function |
|----------|----------|
| BUS1, BUS2 | Communication bus |
| FIRE 1, FIRE 2 | Fire alarm inputs |
| PRE | Pre-alarm |
| AUX | Auxiliary |
| FAULT | Fault output |
| SPARE | Spare terminals |
| RS485 1A, 1B, 2A, 2B | RS485 communication |
| SCREEN | Ground/shield |

| Component | Label | Function |
|-----------|-------|----------|
| IC11 | STR-8502 PROMINI | Microcontroller/PROM |

---

## 3. Engineering Significance

- Validates theoretical knowledge from SIWES 2023 (H&O Automation Systems).
- Demonstrates understanding of how physical terminal blocks map to logical system architecture.
- Identifies RS485 communication lines and fire alarm terminals.

---

## 4. Media

*[Insert PCB close-up image]*

---

## 5. Repository Structure

```
industrial-pcb-hardware-analysis/
├── README.md
├── LICENSE
├── docs/
│   ├── RS485_Fire_Alarm_Interface.md
│   └── PCB_Terminal_Analysis.md
└── media/
    └── pcb_closeups/
```

---

## 6. License

MIT License — see [LICENSE](LICENSE) for details.

---

## 7. Contact

**Toluwanimi Jesusina**
- Email: [jesusinatoluwanimi@gmail.com](mailto:jesusinatoluwanimi@gmail.com)
- LinkedIn: [linkedin.com/in/toluwanimi-jesusina](https://linkedin.com/in/your-profile)
```
