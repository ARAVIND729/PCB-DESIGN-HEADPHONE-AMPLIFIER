🎧 Headphone Amplifier PCB Design with High-Fidelity Filter

📘 Overview

This project presents the design and PCB implementation of a Headphone Amplifier with a high-fidelity active filter stage, developed using KiCad.
The design combines a low-noise operational amplifier (OPA2134) for signal conditioning and filtering with an LM386 audio power amplifier for driving headphones.

The project covers the complete workflow from schematic design to PCB layout and 3D visualization, focusing on analog signal integrity and layout practices.

🎯 Objectives

Design a compact headphone amplifier with audio filtering

Implement a low-noise pre-amplification and filter stage

Drive headphones using a dedicated audio amplifier IC

Design and route a manufacturable PCB using KiCad

Visualize the final board using KiCad 3D viewer

⚙️ System Description

The circuit is divided into two main functional blocks:

🔹 High-Fidelity Filter Section

Op-Amp: OPA2134 (low noise, audio-grade)

Active filter for signal conditioning

Input coupling and biasing network

Designed to improve audio clarity before amplification

🔹 Headphone Amplifier Section

Audio Amplifier IC: LM386

Adjustable gain using external resistor and capacitor network

Output coupling capacitor for headphone safety

Suitable for low-power headphone driving

🧩 Key Components

OPA2134 – Audio-grade operational amplifier

LM386 – Low-voltage audio power amplifier

Resistors & Capacitors – Gain setting, filtering, coupling

Potentiometer (RV1) – Volume control

Input / Output Headers – Audio signal connections

PCB Tool: KiCad (Schematic, PCB, 3D Viewer)

🖥️ PCB Design Details

Designed using KiCad 6.x

Two-layer PCB (Top & Bottom copper)

Short signal paths for low-noise analog routing

Ground plane for noise reduction

Clear separation between filter and power stages

Compact form factor suitable for enclosure mounting
