# PCB-Design-Embedded-Hardware-Projects-Portfolio
# PCB Design & Embedded Hardware Portfolio
### Shangarapu Mahith Kumar — Embedded Hardware Design Engineer

📍 Hyderabad, India &nbsp;|&nbsp; 📧 shangarapumahith@gmail.com &nbsp;|&nbsp; 🔗 [LinkedIn](https://linkedin.com/in/mahith-kumar)

---

## About This Portfolio

Embedded Hardware Design Engineer with hands-on experience in **PCB design, IoT hardware development, and industrial-grade board bring-up**. This portfolio showcases 6 real-world PCB projects designed using **Altium Designer**, covering industrial interfaces, IoT connectivity, power electronics, and embedded control systems.

**Core Skills demonstrated here:**
`Altium Designer` `Schematic Capture` `Multi-layer PCB Layout` `Gerber Generation` `3D PCB Modelling` `Signal Integrity` `EMI/EMC Awareness` `IoT Hardware` `Industrial Interfaces` `Component Selection`

---

## Projects

---

### 1. 555 Timer-Based LED Blinker
> **Keywords:** Analog circuit design · Timer IC · PCB prototyping · Oscillator design

A foundational PCB project demonstrating analog circuit design and PCB layout fundamentals using the classic NE555 timer IC in astable multivibrator mode.

**Key highlights:**
- Designed schematic and PCB layout from scratch in Altium Designer
- Implemented astable oscillator circuit with adjustable frequency via RC network
- Clean single-layer PCB layout with proper component placement and trace routing
- Includes 3D PCB model output and full Gerber files for manufacturing

**Tech stack:** NE555 Timer · Resistor-Capacitor network · Single-layer PCB · Altium Designer

---

### 2. ESP8266 Wi-Fi 4-Channel Home Automation Stack (WIFI-4CH)
> **Keywords:** Multi-board stack PCB · ESP8266 · IoT · Relay control · AC load switching · Power conversion · Home automation

A compact **two-board stacked PCB system** for Wi-Fi-based home automation, designed to control 4 AC loads wirelessly via ESP8266. The project is split into two mating 2-layer PCBs designed as a unified stack assembly in Altium Designer.

**Board 1 — Controller Card (WIFI-4CH_CC) — Top board:**
- ESP8266 Wi-Fi module for wireless communication and IoT connectivity
- Control logic, GPIO routing, and signal interfacing to the main card
- Compact 2-layer layout optimized for stack mating

**Board 2 — Main Card (WIFI-4CH_MC) — Bottom board:**
- 4-channel relay module for switching AC loads
- Fuse protection circuit for overcurrent safety
- AC-to-DC power converter circuit to power the entire stack
- High-current PCB routing with safety clearances for mains voltage

**Key highlights:**
- Full multi-board stack assembly designed and managed in Altium Designer (`.PrjMbd`)
- Schematic, PCB layout, assembly drawing, 3D PDF output, and Gerber files included
- Demonstrates real-world product design skills: power isolation, relay driving, AC safety, and compact form factor
- Assembly outputs include pick-and-place files and test point reports

**Tech stack:** ESP8266 · 4-channel Relay · Fuse · AC-DC Power Conversion · Multi-board Stack · Altium Designer · 2-layer PCB × 2

> 💡 *This is the most complete project in the portfolio — a full product-level design with two mating boards, power electronics, and IoT connectivity.*

---

### 3. ESP8266 Hub Board
> **Keywords:** IoT · Wi-Fi · ESP8266 · Embedded connectivity · Hub PCB

A compact IoT hub board built around the ESP8266 Wi-Fi module, designed for wireless data acquisition and remote device control applications.

**Key highlights:**
- Integrated ESP8266 module with supporting power regulation and decoupling circuitry
- Designed for stable 3.3V operation with proper bypass capacitor placement
- Routed antenna keep-out zone to preserve RF signal integrity
- GPIO breakout headers for peripheral expansion
- Full 3D model and Gerber output included

**Tech stack:** ESP8266 · Wi-Fi · 3.3V LDO · IoT · Altium Designer · 2-layer PCB

---

### 3. Isolated USB-to-UART Converter
> **Keywords:** Galvanic isolation · USB · UART · RS232 · Signal isolation · Industrial PCB

An industrial-grade USB-to-UART converter with **galvanic isolation**, designed to protect host systems from ground loops and voltage spikes in industrial and embedded debug environments.

**Key highlights:**
- Implemented galvanic isolation between USB and UART sides using digital isolator IC
- Isolated power supply design with DC-DC converter for the UART side
- Designed for industrial noise immunity — critical for factory floor and field use
- Compact 2-layer PCB with careful isolation boundary and creepage distance compliance
- Full 3D PCB model, BOM, and Gerber files included

**Tech stack:** USB · UART · Digital Isolator · Isolated DC-DC · 2-layer PCB · Altium Designer

> 💡 *This project directly reflects skills used in IoT smart metering hardware validation at Kritsnam Technologies.*

---

### 4. Industrial PoE Ethernet Interface Module
> **Keywords:** Power over Ethernet · PoE · IEEE 802.3af · Industrial networking · Embedded Ethernet

A professional-grade **Power over Ethernet (PoE) interface module** designed for industrial IoT applications, enabling both data communication and power delivery over a single Ethernet cable.

**Key highlights:**
- Implemented IEEE 802.3af-compatible PoE PD (Powered Device) interface
- Integrated PoE controller IC with signature resistor and classification circuitry
- Designed isolated DC-DC stage for converting PoE input to regulated system voltage
- EMI-conscious layout with proper filtering, ground planes, and differential pair routing for Ethernet signals
- Industrial-grade design with attention to thermal management and component derating
- Full 3D model output and manufacturing-ready Gerber files

**Tech stack:** PoE · IEEE 802.3af · Ethernet · Isolated DC-DC · Differential pair routing · 4-layer PCB · Altium Designer

> 💡 *Demonstrates advanced PCB skills: differential pair routing, power isolation, EMI layout — directly applicable to industrial IoT product development.*

---

### 5. W5500 Ethernet Interface Board
> **Keywords:** W5500 · Hardwired TCP/IP · SPI · Ethernet · Embedded networking

A standalone Ethernet interface board based on the **WIZnet W5500** hardwired TCP/IP controller, enabling SPI-based Ethernet connectivity for microcontroller systems without a software TCP/IP stack.

**Key highlights:**
- Designed W5500 interface board with SPI header for direct MCU integration (STM32, LPC, 8051 compatible)
- Integrated RJ45 connector with integrated magnetics for Ethernet signal conditioning
- Proper differential pair routing for 100BASE-TX signals with controlled impedance
- Decoupling and power filtering network for stable W5500 operation
- Crystal oscillator circuit for W5500 25MHz clock requirement
- Full 3D model, schematic, and Gerber files included

**Tech stack:** W5500 · SPI · TCP/IP · Ethernet · RJ45 · Differential pair routing · Altium Designer

---

## Tools & Skills Demonstrated

| Category | Details |
|---|---|
| **EDA Tool** | Altium Designer |
| **PCB Types** | Single-layer, 2-layer, 4-layer |
| **Interfaces** | USB, UART, SPI, Ethernet (PoE, W5500) |
| **Protocols** | SPI, UART, TCP/IP, IEEE 802.3af |
| **Design practices** | Schematic capture, library creation, differential pair routing, EMI/EMC layout, 3D modelling, Gerber generation |
| **Output files** | Schematic PDF, PCB layout, 3D PDF, Gerber files, BOM |

---

## Professional Experience

**Junior Embedded Hardware Engineer** — Kritsnam Technologies Pvt. Ltd., Hyderabad *(Dec 2024 – Feb 2026)*
- IoT smart metering device hardware validation, PCB testing, and board bring-up
- UART, SPI, I2C interface validation; Li-ion battery validation (D-size, 19,600 mAh)
- Production test procedure development and QC documentation

---

## Contact

Open to **Embedded Hardware Engineer**, **PCB Design Engineer**, and **Hardware Validation Engineer** roles.

📧 shangarapumahith@gmail.com &nbsp;|&nbsp; 📍 Hyderabad, India &nbsp;|&nbsp; [LinkedIn](https://linkedin.com/in/mahith-kumar)
