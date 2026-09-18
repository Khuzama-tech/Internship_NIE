# Internship_NIE
# 🚀 STM32 Multi-Layer Development Board 

Welcome to the repository for my technical internship project at the **National Institute of Electronics (NIE)**. This project focuses on professional multi-layer Printed Circuit Board (PCB) design using **Altium Designer**, resulting in a fully custom STM32 development board.

---

## 📌 Project Overview

During my remote internship at NIE, I explored advanced hardware design principles, high-speed multi-layer stackups, and industrial manufacturing standards. To apply these concepts hands-on, I designed a custom four-layer development board centered around the **STM32F411CEU6** microcontroller, integrated with an **MPU-6050 IMU sensor**.

### Key Highlights:
* **Architecture**: 4-Layer PCB Stackup designed from scratch.
* **Microcontroller**: STM32F411CEU6 (ARM Cortex-M4 core).
* **Sensor Integration**: MPU-6050 6-axis MotionTracking (Accelerometer + Gyroscope).
* **Software Tool**: Altium Designer (Schematic Capture & PCB Layout).
* **Validation**: Zero Design Rule Check (DRC) errors prior to fabrication handoff.

---

## 🛠️ Design & Technical Specifications

* **Layer Stackup**: 
  * *Top Layer*: Component placement and high-speed signal routing.
  * *Internal Plane 1*: Dedicated Ground (GND) plane for EMI/EMC reduction and signal integrity.
  * *Internal Plane 2*: Dedicated Ground (GND) plane for low-impedance return paths and shielding.
  * *Bottom Layer*: Secondary signal routing and power routing.
* **Libraries Created**: Custom schematic symbols and land patterns/footprints built according to IPC standards.
* **Design Verification**: Rigorous execution of Design Rule Checks (DRC) to ensure clearance, creepage, and manufacturing tolerances were fully met.

---

## 📂 Repository Structure

```text
├── 📄 INTERNSHIP TECHNICAL REPORT.docx # Detailed internship documentation
├── 📁 Schematics/                      # Altium schematic sheets (.SchDoc)
├── 📁 PCB_Layout/                      # PCB document files and layer plans (.PcbDoc)
└── 📄 README.md                        # Project documentation
