<p align="center">
  <h1 align="center">RIS-Aided Secure Sensing for Industry 5.0 Smart Factories</h1>
</p>

<p align="center">
  <strong>Physically Calibrated RIS-Assisted mmWave Communication Framework</strong><br>
  International Institute of Information Technology, Bangalore (IIIT-B)
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Frequency-32.8GHz-blue?style=flat-square" alt="Frequency">
  <img src="https://img.shields.io/badge/RIS-1--Bit_Metasurface-critical?style=flat-square" alt="RIS">
  <img src="https://img.shields.io/badge/Application-Industry_5.0-informational?style=flat-square" alt="Application">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square" alt="Status">
</p>

---

## Table of Contents

* [Overview](#overview)
* [Motivation](#motivation)
* [Key Features](#key-features)
* [System Architecture](#system-architecture)
* [Technical Highlights](#technical-highlights)
* [Mathematical Modeling](#mathematical-modeling)
* [Simulation Results](#simulation-results)
* [Applications](#applications)
* [Future Work](#future-work)
* [Repository Structure](#repository-structure)
* [Authors](#authors)
* [License](#license)

---

## Overview

This project presents a physically calibrated simulation framework for **Reconfigurable Intelligent Surface (RIS)** assisted secure sensing and communication in Industry 5.0 smart factory environments.

The system models a realistic mmWave communication scenario where severe Non-Line-of-Sight (NLoS) blockage caused by industrial machinery is mitigated using a low-cost **1-bit RIS**. The RIS creates a virtual Line-of-Sight (vLoS) communication path to restore connectivity and improve signal strength.

Unlike ideal theoretical RIS models, this work incorporates practical hardware constraints such as:

* 1-bit phase quantization
* Resonance-induced amplitude loss
* Frequency-selective behavior
* Cascaded RIS path loss
* Beamforming limitations

---

## Motivation

Industrial smart factory environments suffer from severe mmWave blockage due to metallic machinery, moving robots, and dense indoor layouts. Traditional communication systems struggle to maintain reliable high-frequency links under these conditions.

This project explores the use of low-cost RIS technology to:

* Restore blocked communication paths
* Improve signal coverage
* Enable secure sensing
* Enhance reliability for Industry 5.0 applications

---

## Key Features

| Feature                   | Description                                |
| :------------------------ | :----------------------------------------- |
| **32.8 GHz mmWave Model** | Ka-band industrial communication framework |
| **8×8 RIS Metasurface**   | Passive beam steering array                |
| **1-Bit RIS Hardware**    | Realistic quantized phase control          |
| **Beamforming**           | Virtual LoS generation and signal steering |
| **RSRP Heatmaps**         | Coverage visualization and analysis        |
| **5G NR Alignment**       | Compatible with Release 16/17 concepts     |

---

## System Architecture

The simulation environment consists of:

* **5G NR gNodeB Transmitter**
* **8×8 Reconfigurable Intelligent Surface**
* **Industrial Metallic Blocker (PEC)**
* **Mobile Robot Receiver (AMR/AGV)**

The RIS dynamically redirects mmWave signals around obstacles to restore communication links in blocked industrial environments.

---

## Technical Highlights

### Hardware Constraints Modeled

| Constraint               | Description                               |
| :----------------------- | :---------------------------------------- |
| 1-Bit Phase Control      | 0° / 180° quantized phase shifting        |
| Amplitude-Phase Coupling | State-dependent reflection efficiency     |
| Resonance Effects        | Lorentzian resonance behavior at 32.8 GHz |
| Cascaded Channel Loss    | Realistic RIS path-loss modeling          |

### Beamforming Features

* 14° narrow pencil beam generation
* Passive coherent reflection gain
* RIS-assisted virtual LoS communication
* Frequency-selective reflection analysis

---

## Mathematical Modeling

The project implements:

* Friis transmission equation
* RIS cascaded link-budget equations
* Lorentzian resonance modeling
* Quantized phase reflection matrices

---

## Simulation Results

| Metric               | Result                     |
| :------------------- | :------------------------- |
| RIS Configuration    | 8×8 Metasurface            |
| Operating Frequency  | 32.8 GHz                   |
| Beam Width           | ~14°                       |
| Signal Improvement   | +35 dB to +40 dB           |
| Communication Status | Successful NLoS mitigation |

The proposed RIS framework successfully restores communication from near-noise-floor conditions to usable signal levels.

---

## Applications

* Industry 5.0
* Industrial IoT (IIoT)
* Smart factories
* RIS-assisted localization
* Secure wireless sensing
* Future 6G communication systems

---

## Future Work

* Mobility-aware beam tracking
* Doppler-aware beamforming
* ML-based localization
* Secure beamforming against eavesdroppers
* Reinforcement learning based RIS optimization

---

## Repository Structure

```text
.
├── Simulation/
├── Beamforming/
├── Channel_Model/
├── Heatmaps/
├── Results/
├── Documentation/
├── Figures/
├── Reports/
└── README.md
```

---

## Authors

| Name           | Affiliation    |
| :------------- | :------------- |
| Siddhant Deore | IIIT Bangalore |
| Pratham Shetty | IIIT Bangalore |

---

## License

This project is intended for academic and research purposes.

---

<p align="center">
  <sub>© 2026 · IIIT Bangalore · RIS-Assisted Secure Sensing Project</sub>
</p>
