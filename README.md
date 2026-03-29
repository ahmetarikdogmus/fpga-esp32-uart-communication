# FPGA–ESP32 UART Communication and Digital Control System

Real-time UART-based communication architecture between Basys 3 FPGA and ESP32,
implemented using hardware-software co-design approach.

## 📌 Overview

This project implements a complete UART communication system between an ESP32-based 
wireless interface and a Basys 3 FPGA. The design covers full RTL-level UART TX/RX 
module implementation with FSM-based command processing and PWM output control.

## 🛠️ Tools & Technologies

- **Language:** VHDL
- **FPGA Board:** Basys 3 (Xilinx Artix-7)
- **Microcontroller:** ESP32
- **Synthesis & Implementation:** Vivado
- **Simulation:** ModelSim

## 🔧 Architecture

### FPGA Side (VHDL)
- RTL-level UART TX/RX module
  - Baud rate generator (clock divider based)
  - Shift register structure
  - Oversampling-based RX architecture
- FSM-based command processing and control unit
- Register-based datapath architecture
- PWM generation and digital output control modules
- Synchronous design with deterministic delay analysis

### ESP32 Side
- Wireless interface for remote command transmission
- UART protocol communication with FPGA

## ✅ Key Skills Demonstrated

- FSM and modular RTL architecture development
- Hardware-software co-design (HW/SW co-design)
- Real-time digital system design
- Protocol implementation at RTL level

## 📁 Project Structure
```
fpga-esp32-uart-communication/
├── src/           # VHDL source files
├── sim/           # Testbench files
├── esp32/         # ESP32 firmware
├── constraints/   # Timing & pin constraints
└── docs/          # Block diagrams, waveforms
```

## 🏆 About

Developed as part of a digital design portfolio.  
