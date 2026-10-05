# Fuente de alimentación para protoboard con dos salidas programables a 5V y 3V3

Este proyecto es una fuente de alimentación programable para protoboard basada en los reguladores lineales **LM7805** y el **LM317** con dos salidas independientes que se pueden programar para sumistrar dos tensiones, 5V o 3.3V.

Su factor de forma y conectores permiten acoplarla con facilidad a la protoboard a través de sus rieles de alimentación superior e inferior.
La fuente hace uso de dos conectores que se pueden ajustar para que cada salida suministre ya sea una tensión de 5V o de 3.3V de forma independiente para cada salida. 

---
![Module Preview](https://raw.githubusercontent.com/electgpl/DCDCsyncBuckFSS/refs/heads/main/Resources/541955125_18524312182045902_4678174790925630173_n.jpg)
---

## 🔑 Key Features

- **Synchronous buck regulator (AP64501)**
  - Higher efficiency compared to asynchronous regulators.
  - Reduced heat generation under load.
- **Fixed Spread Spectrum (FSS)**
  - Lower EMI and more predictable spectral content.
- **Soft-Start (SS)**
  - Controlled inrush current during power-up.
- **Protections included**
  - Overcurrent protection (OCP).
  - Overvoltage protection (OVP).
  - Thermal shutdown (TSD).
- **Output filtering**
  - Additional **LC filter stage** for significantly reduced ripple.
- **PCB design**
  - **4-layer PCB** for improved heat spreading and ground integrity.
  - Optimized layout for EMI and thermal performance.
- **Thermal analysis**
  - Finite Element Analysis (FEA) performed.
  - Effective thermal resistance: **55 °C/W** (with 1 oz copper).

---

## 📐 Form Factor

- Pinout, size, and footprint are **drop-in compatible** with standard LM2596-based modules.  
- This allows easy replacement in existing designs, providing an **immediate upgrade** without redesigning the host PCB.

---

## 📊 Performance Advantages over LM2596 Modules

- ✅ Higher efficiency → less power loss.  
- ✅ Lower EMI thanks to fixed-frequency operation and optimized layout.  
- ✅ Lower output ripple due to additional LC stage.  
- ✅ Improved thermal performance with 4-layer PCB and synchronous design.  
- ✅ Built-in protections increase reliability and robustness.

---

## 🛠 Applications

- Embedded systems.  
- IoT devices.  
- RF front-ends (low-ripple supply requirement).  
- General-purpose regulated DC power supply.  
- Replacement for LM2596 modules in existing projects.

---

## 📄 Documentation

- [AP64501 Datasheet (Diodes Incorporated)](https://www.diodes.com/assets/Datasheets/AP64501.pdf)  
- Thermal FEA analysis results included in `/docs`.  
- PCB design files in `/hardware`.

---

## 🚀 Status

- ✅ Schematic design complete.  
- ✅ PCB layout (4-layer) completed.  
- ✅ Thermal simulation results validated.  
- 🔜 Hardware prototyping and testing in progress.

---

## 📷 Preview

*(Add photos, renderings, or thermal plots here when available.)*

---

## 📜 License

This project is released under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.
