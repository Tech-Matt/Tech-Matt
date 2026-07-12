<div align="center">

# ⚡ Hi, I'm Mattia Rizzo

### I build and study computing systems from digital logic to software.

`FPGA & RTL` · `Embedded C` · `Computer Architecture` · `Edge AI` · `Linux`

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mattia_Rizzo-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rizzo-mattia/)
[![Blog](https://img.shields.io/badge/Blog-TechMatt-222222?style=flat-square&logo=readme&logoColor=white)](https://techmatt.bearblog.dev/)
[![YouTube](https://img.shields.io/badge/YouTube-TechMatt-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@TechMatt01)
[![Email](https://img.shields.io/badge/Email-Contact_Me-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mattia.rizzo.un@gmail.com)

</div>

---

## About me

I am an **Embedded Systems MSc student** who enjoys exploring what happens beneath software abstractions.

Most of my projects begin with the same question:

> **How does this system actually work?**

That curiosity has led me to work on FPGA processors, low-level firmware, real-time systems, hardware measurement architectures, Linux utilities, TinyML applications, and, more recently, a Transformer inference engine written from scratch in C.

I am especially interested in the boundary between **digital hardware and low-level software**: how architecture, memory, timing, and implementation choices shape the behaviour and performance of a system.

> [!NOTE]
> **Currently working on:** a Transformer inference engine in C for resource-constrained systems, while studying efficient AI inference, computer architecture, and FPGA-based acceleration.

---

## Featured project

<table>
<tr>
<td valign="top">

### Transformer Inference Engine

A from-scratch Transformer inference engine written in C.

The goal is not only to reproduce the model mathematically, but to understand how inference behaves when abstractions are removed: tensor layouts, memory allocation, numerical operations, execution order, and performance trade-offs.

The project is being developed with constrained and embedded systems in mind, with a longer-term interest in hardware-aware optimisation and acceleration.

**What it involves**

- Transformer inference implemented without a high-level ML framework
- Explicit tensor and memory management
- Attention, masking, normalisation, and feed-forward layers
- Focus on clarity, correctness, and eventual optimisation
- Exploration of embedded deployment constraints

**Technologies:** `C` `Machine Learning` `Embedded Inference` `Computer Architecture`

[View repository →](https://github.com/Tech-Matt/transformer-inference-engine)

</td>
</tr>
</table>

---

## Digital hardware and computer architecture

<table>
<tr>
<td width="50%" valign="top">

### FPGA RISC-V CPU

A non-pipelined **RV32I processor** implemented in VHDL.

The project covers the main components of a basic processor, including the datapath, control logic, register file, ALU, instruction decoding, and memory interface.

It was built as a practical way to connect ISA-level concepts with their hardware implementation on an FPGA.

**Technologies:** `VHDL` `FPGA` `RISC-V` `Computer Architecture`

[View repository →](https://github.com/Tech-Matt/riscv-cpu)

</td>
<td width="50%" valign="top">

### FPGA Time-to-Digital Converter

My bachelor thesis and internship work focused on the design and characterisation of a **Time-to-Digital Converter on a Xilinx Artix-7 FPGA**.

The system used a 200 MHz clock and approximately 800 timing bins, with automated delay sweeps and statistical analysis of the measured timing distribution.

I also worked on host-side acquisition and analysis software for calibration, centroid estimation, and DNL evaluation.

**Technologies:** `FPGA` `Digital Design` `Timing Measurement` `MATLAB` `.NET`

> The implementation is not public, but the project represents one of my main hardware-design experiences.

</td>
</tr>
</table>

---

## Embedded software and real-time systems

<table>
<tr>
<td width="50%" valign="top">

### RTOS for the TI MSP432

A small real-time operating system written in C for the TI MSP432.

I built it to better understand how scheduling, task management, interrupts, timing, and context handling work below the level of a commercial RTOS.

**Technologies:** `C` `MSP432` `RTOS` `Bare Metal`

[View repository →](https://github.com/Tech-Matt/rtos)

</td>
<td width="50%" valign="top">

### Embedded Display Driver and HAL

During an internship, I worked on a C driver and hardware abstraction layer for a proprietary embedded display.

The work involved register-level interaction, hardware communication, interface design, debugging, and integration with the surrounding firmware stack.

**Technologies:** `C` `Firmware` `Device Drivers` `HAL`

> The source code is proprietary and cannot be published.

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">

### Arduino TinyML Gesture Recognition

A TinyML pipeline for recognising hand gestures using the Arduino Nano 33 BLE Sense Lite.

The project covers data collection, preprocessing, model training, and deployment on a constrained embedded target.

**Technologies:** `TinyML` `Arduino` `Embedded AI` `Sensors`

[View repository →](https://github.com/Tech-Matt/arduino-tiny-ml)

</td>
<td width="50%" valign="top">

### Embedded and Bare-Metal Experiments

A collection of smaller experiments involving microcontrollers, low-level C, hardware interfaces, interrupts, timers, and system-level behaviour.

These projects are where I test concepts before integrating them into larger systems.

**Topics:** `Bare Metal` `Interrupts` `Peripherals` `Low-Level C`

[Browse repositories →](https://github.com/Tech-Matt?tab=repositories)

</td>
</tr>
</table>

---

## Systems, tools, and experiments

<table>
<tr>
<td width="50%" valign="top">

### Lecture Shortener

A terminal-based tool that analyses recorded lectures and removes low-information segments.

The project combines speech-to-text, local language-model processing, timestamp analysis, and FFmpeg-based video reconstruction.

I am developing it as both a practical tool and a way to study local AI workflows and systems programming.

**Technologies:** `Zig` `Speech-to-Text` `Local LLMs` `FFmpeg`

</td>
<td width="50%" valign="top">

### bright-rs

A lightweight Linux backlight controller written in Rust.

I built it as a small systems-programming project to learn Rust while interacting directly with Linux system interfaces.

**Technologies:** `Rust` `Linux` `CLI`

[View repository →](https://github.com/Tech-Matt/bright-rs)

</td>
</tr>
</table>

---

## Technical interests

<div align="center">

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![VHDL](https://img.shields.io/badge/VHDL-543978?style=flat-square)
![Verilog](https://img.shields.io/badge/Verilog-ED1C24?style=flat-square)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=flat-square&logo=riscv&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-E16737?style=flat-square)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

### Main areas

- **Digital hardware:** FPGA, RTL design, VHDL, Verilog, RISC-V, Vivado
- **Embedded software:** C, C++, Rust, bare metal, RTOS, device drivers
- **Systems:** Linux, operating systems, computer architecture, performance analysis
- **AI:** Transformer inference, TinyML, embedded AI, hardware-aware inference
- **Tools:** Python, MATLAB, Git, Docker, QEMU

---

## What I am looking for

I am continuing my MSc in **Embedded Systems at Tampere University** and I am interested in opportunities involving:

- FPGA and RTL design
- Firmware and embedded software
- Computer architecture and SoC development
- Edge AI and efficient inference
- Low-level systems programming

I am particularly interested in **internship, thesis, and junior roles in Tampere or fully remote within the EU**.

---

## Elsewhere

I use GitHub to document projects, experiments, and what I learn while trying to understand computing systems a little more deeply.

You can also find me here:

- [Blog](https://techmatt.bearblog.dev/)
- [LinkedIn](https://www.linkedin.com/in/rizzo-mattia/)
- [YouTube](https://www.youtube.com/@TechMatt01)
- [Email](mailto:mattia.rizzo.un@gmail.com)

---

<div align="center">

### Always learning, always building — one abstraction layer lower.

</div>
