# Four-Stage Audio Amplifier

A discrete transistor-based four-stage audio amplifier designed to amplify low-amplitude audio signals while maintaining low distortion and a flat frequency response across the audible spectrum (20 Hz – 20 kHz).

## Overview

This project implements a complete analog audio amplification chain consisting of:

- Differential Amplifier (Pre-Amplifier)
- Common-Emitter Voltage Gain Stage
- Active Band-Pass Filter
- Class-AB Power Amplifier

The amplifier is designed to drive a **10 Ω speaker** with approximately **0.7 W** output power while minimizing Total Harmonic Distortion (THD).

---

## Features

- Differential input stage with high CMRR for noise rejection
- High-gain common-emitter voltage amplifier
- Active band-pass filter covering the audible range (20 Hz – 20 kHz)
- Class-AB push-pull output stage with reduced crossover distortion
- LTspice simulation and hardware validation
- Complete small-signal analysis and mathematical derivations

---

## System Architecture

```
Audio Input
      │
      ▼
Differential Amplifier
      │
      ▼
Common-Emitter Gain Stage
      │
      ▼
Active Band-Pass Filter
      │
      ▼
Class-AB Power Amplifier
      │
      ▼
     Speaker
```

---

## Key Specifications

| Parameter | Value |
|-----------|-------|
| Supply Voltage | ±5 V |
| Frequency Range | 20 Hz – 20 kHz |
| Speaker Load | 10 Ω |
| Output Power | ~0.7 W |
| Architecture | Four-stage analog amplifier |
| Simulation Tool | LTspice |

---

## Design Highlights

- Designed each stage using transistor small-signal analysis.
- Derived gain, input/output impedance, and transfer functions analytically.
- Validated theoretical results through LTspice simulations.
- Implemented and tested the complete amplifier on hardware.
- Optimized for low distortion and stable frequency response.

---

## Repository Structure

```
├── LTspice/            # Simulation files
├── Hardware/           # Circuit images and implementation
├── Report/             # Detailed design report
└── README.md
```

---

## Tools Used

- LTspice
- Analog Circuit Design
- BJT Small-Signal Analysis
- Breadboard Prototyping

---

## Results

- Successful amplification of low-level audio signals.
- Stable operation across the audible frequency range.
- Hardware performance closely matched simulation results.
- Low-noise operation with effective common-mode rejection.

---

## Authors

- Vedant Zope
- Kavya Pandey
