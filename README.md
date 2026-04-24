# PPG Watch PCB Design 

## Project Overview

This project presents the design and routing of a **Photoplethysmography (PPG) based wearable watch PCB**, developed using **KiCad 9.0**.
The PCB is designed to acquire pulse signals using an optical PPG sensor and support wearable health monitoring applications.
---
## Key Features
* Compact **wearable watch-size PCB layout**
* Designed using **KiCad 9.0**
* **Single-layer component placement**
* **Multi-layer routing** for optimized signal flow
* Clear **reference designators** (U1, R1, C1, etc.)
* Dedicated **power management section**
* Sensor integration for **PPG signal acquisition**
* Optimized routing for **noise reduction**
* Organized schematic hierarchy
---
## System Description
The PPG watch system includes the following major functional blocks:
### 1. PPG Sensor Module

* Optical PPG sensor detects blood volume changes.
* Uses LED light reflection technique.
* Generates analog signals corresponding to pulse rate.

### 2. Power Management Circuit

* Provides regulated voltage to all modules.
* Includes filtering capacitors for noise reduction.
* Ensures stable operation of sensor and processing units.

### 3. Processing Unit

* Microcontroller interface for signal acquisition.
* Processes raw PPG signals.
* Enables communication with external systems.

### 4. PCB Layout Design

* Compact layout suitable for wearable form factor.
* Optimized component placement for shorter routing paths.
* Ground routing designed to reduce noise interference.

---

## Design Tools Used

* **EDA Tool:** KiCad 9.0
* **PCB Design:** Schematic + Layout
* **Library Management:** Custom and standard KiCad libraries

---

## PCB Design Specifications

| Parameter           | Value                  |
| ------------------- | ---------------------- |
| PCB Tool            | KiCad 9.0              |
| Layers Used         | Multi-layer routing    |
| Component Placement | Single-layer placement |
| Design Type         | Wearable PCB           |
| Application         | Pulse Monitoring (PPG) |

---

## Files Included in Repository

* `.kicad_pro` — Project file
* `.kicad_sch` — Schematic design
* `.kicad_pcb` — PCB layout
* `.pretty` — Custom footprints
* Backup schematic references
* Supporting design files

---

## Design Considerations

The following engineering practices were followed during PCB development:

* Short routing paths to reduce signal delay
* Proper decoupling capacitor placement
* Organized power distribution
* Clear component labeling
* Noise-sensitive routing considerations
* Manufacturable PCB layout structure

---

## Applications

This PCB design can be used in:

* Wearable health monitoring devices
* Heart rate monitoring systems
* Biomedical signal acquisition systems
* Smart wearable electronics
* Embedded biomedical devices

---

## Learning Outcomes

Through this project, the following skills were developed:

* PCB schematic design
* Multi-layer PCB routing
* Component placement optimization
* Power and signal integrity considerations
* Wearable PCB design techniques
* KiCad professional workflow
* Hardware documentation practices

---

## Future Improvements

Possible future enhancements include:

* Integration with wireless communication (BLE)
* Battery charging circuit addition
* Sensor accuracy improvements
* Miniaturized PCB version
* Enclosure design for wearable deployment

---

## Author

**Harish Bawin**
Electronics and Communication Engineering (ECE)
PCB Design | Embedded Systems | Hardware Development

---

## License

This project is intended for educational and learning purposes.
