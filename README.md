# Audio Preamplifier & Tone Corrector PCB 🎛️

![Integrated Circuit Render](Integrated%20Circuit.png)

## 📌 Project Overview
This repository contains the complete hardware design for an audio preamplifier featuring a dual-band tone corrector and an integrated linear power supply. The entire project—from schematic capture and SPICE simulations to PCB layout—was developed using **Cadence OrCAD**.

The circuit is built using discrete components and is designed to provide high-quality audio signal amplification with precise control over low and high frequencies[cite: 309, 313].

## 🚀 Key Features
* **Active Tone Control:** Independent attenuation and amplification (20dB) for bass (<500Hz) and treble (>1kHz) frequencies using an RC feedback network[cite: 311, 314, 327].
* **Discrete Analog Design:** The audio path and power regulation are built around classic Bipolar Junction Transistors (BC109C, BC107, BD135).
* **Integrated Linear Power Supply:** An on-board 25V regulated power supply featuring a series pass transistor and an error amplifier, ensuring a stable and low-noise power delivery for the audio stages.
* **Manufacturing Ready:** Includes full documentation, BOM, and manufacturing tables for immediate PCB fabrication.

## 📂 Repository Structure
The project files are organized to reflect a standard hardware engineering workflow:

* `📂 Bill of materials/` - Comprehensive BOM listing all components required for assembly.
* `📂 Data Sheet/` - Technical datasheets for the active and passive components used in the design.
* `📂 Layout/` - OrCAD PCB Editor files containing the board routing and layout data.
* `📂 Project docs/` - Detailed technical documentation, including mathematical component sizing and design choices.
* `📂 Schematics/` - OrCAD Capture schematic files for the preamplifier and power supply modules.
* `📂 Simulations/` - PSpice simulation results, including:
  * DC Operating Point (Bias) analysis.
  * Transient response analysis.
  * AC Sweep (Frequency response / Bode plots) demonstrating the tone correction curves.
* `📄 PCB_Manufacturing_Table_2026.docx` - Manufacturing specifics and tolerances.

## 💻 Software Stack
* **Cadence OrCAD Capture** (Schematics)
* **Cadence OrCAD PCB Editor** (Layout)
* **OrCAD PSpice** (Analog Circuit Simulation)
