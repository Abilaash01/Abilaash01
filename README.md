# 👋 Hi, I'm Abilaash

<p align="center">
  <a href="https://www.linkedin.com/in/abilaash01">
    <img src="https://img.shields.io/badge/LinkedIn-Abilaash%20U-blue?style=for-the-badge&logo=linkedin">
  </a>
  <a href="mailto:abilaash.u001@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-red?style=for-the-badge&logo=gmail">
  </a>
  <a href="https://abilaashportfolio.netlify.app">
    <img src="https://img.shields.io/badge/Portfolio-View-green?style=for-the-badge&logo=firefox-browser">
  </a>
  <a href="https://github.com/abilaash01">
    <img src="https://img.shields.io/badge/GitHub-abilaash01-181717?style=for-the-badge&logo=github">
  </a>
</p>

---

### ⚙️ Computer Engineer | RTL Design & Digital Verification

I design and verify digital hardware from the register-transfer level down to the gate — pipelined processors, FSM-based controllers, and FPGA-validated logic. My background spans structural VHDL design, FPGA implementation, and system-level validation on multi-ECU hardware-in-the-loop benches, giving me both the RTL fluency and the debug discipline that pre-silicon validation demands.

I care about correctness at the waveform level: hazard-free pipelines, clean timing closure, and testbenches that actually catch bugs before silicon does.

---

## 🎯 Roles I'm Targeting

- **RTL Design Engineer** — turning architectural specs into synthesizable, hazard-free RTL
- **ASIC Design Engineer** — RTL-to-gate design for custom silicon
- **FPGA Engineer** — synthesis, timing closure, and hardware validation on real boards
- **Design Verification (DV) Engineer** — testbenches, coverage, and pre-silicon bug hunting
- **SoC / CPU Architecture / Physical Design** — longer-term interest as projects push closer to silicon

Open to opportunities at semiconductor and fabless companies building next-gen compute.

---

## 🔩 Core Skills

| Domain | Skills |
|---|---|
| **RTL Design** | VHDL, structural & FSM-based design (Moore/Mealy), pipelining, hazard detection/forwarding, arithmetic unit design |
| **Verification** | ModelSim simulation, waveform debug, gate-level timing/critical-path analysis |
| **Digital Logic** | Combinational/sequential design, ripple-carry adders, shift-and-add multipliers, 2's-complement arithmetic |
| **FPGA** | Quartus II/Prime, Altera DE2 (Cyclone IV) — synthesis through hardware validation |
| **Embedded / RTOS** | STM32 HAL, FreeRTOS multitasking, ESP32 peripheral control (PWM/ADC/I²C) |
| **Systems & Debug** | SSH-based ECU debug, CAN bus tracing, log correlation, SQL-driven regression analysis, Jenkins CI |
| **Languages/Tools** | VHDL, C/C++, Rust, Python, Git, Linux |

---

## 🧪 Featured Hardware Projects

### 🔹 5-Stage Pipelined RISC Processor — Structural VHDL
Cycle-accurate, MIPS-style pipeline (IF/ID/EX/MEM/WB) built entirely at the RTL level with structural VHDL. Custom **hazard detection unit** and **forwarding unit** resolve RAW/load-use dependencies; gate-level critical-path analysis quantifies max clock frequency and throughput gains over a single-cycle baseline.

### 🔹 FPGA Traffic Light Controller — FSM Design, Quartus / ModelSim
Synchronous FSM controller taken through the full formal design flow — state diagram → state table → reduction → encoding → excitation equations → RTL — implemented in both Moore and Mealy forms, no vendor IP, and hardware-validated on an Altera DE2 (Cyclone IV) board.

### 🔹 Fixed-Point Arithmetic Units — Structural VHDL
Ripple-carry adder/subtractor and a shift-and-add signed multiplier built up from a 1-bit full adder, using 2's-complement arithmetic. Synthesized and tested on DE-2 FPGA hardware.

### 🔹 Real-Time Alarm System — STM32 / FreeRTOS
Multi-tasking embedded system on an STM32F446RE running five concurrent FreeRTOS tasks (sensor polling, keypad input, OLED display, dual alarm outputs) over HAL drivers and custom peripheral code — real-time scheduling under hardware constraints.

---

## 💼 Relevant Experience

**V&V Software Engineer in Test — Ford Motor Company R&D**
Pre-submit validation on multi-ECU hardware-in-the-loop benches: triaging regression failures down to test/node/code root cause, SSH-based system debug, CAN trace correlation, and SQL-based regression health tracking across a large-scale HiL test infrastructure.

---

## 🎓 Education

**BASc in Computer Engineering (Co-op)** — University of Ottawa
Computer Architecture · Digital Systems · Embedded Systems · Operating Systems · Real-Time Systems Design

---

⚡ *Building hardware that has to be right the first time — from spec to waveform to silicon.*
