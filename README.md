# RIS-Aided Secure Sensing for Industry 5.0 Smart Factories

## Overview

This project presents a physically calibrated simulation framework for **Reconfigurable Intelligent Surface (RIS)** assisted secure sensing and communication in Industry 5.0 smart factory environments.

The system models a realistic mmWave communication scenario where severe Non-Line-of-Sight (NLoS) blockage caused by industrial machinery is mitigated using a low-cost **1-bit RIS**. The RIS creates a virtual Line-of-Sight (vLoS) communication path to restore connectivity and improve signal strength.

The project focuses on realistic hardware-aware modeling instead of ideal theoretical assumptions by incorporating:

* 1-bit phase quantization
* Resonance-induced amplitude loss
* Frequency-selective behavior
* Cascaded RIS path loss
* Beamforming constraints

---

## Key Features

* 32.8 GHz mmWave communication model
* 8×8 RIS metasurface array
* Realistic 1-bit RIS hardware modeling
* Beamforming and virtual LoS generation
* Smart factory blockage simulation
* RSRP heatmap visualization
* Frequency-selective resonance modeling
* Physically calibrated offline simulation
* 5G NR Release 16/17 aligned framework

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

* 1-bit phase control (0° / 180°)
* State-dependent reflection efficiency
* Amplitude-phase coupling
* Resonance dip at 32.8 GHz

### Beamforming

* 14° narrow pencil beam generation
* Passive coherent reflection gain
* Cascaded RIS channel modeling

### Simulation Results

* Successful NLoS blockage mitigation
* +35 dB to +40 dB RSRP improvement
* Signal restoration from noise floor to usable communication levels

---

## Mathematical Modeling

The project implements:

* Friis transmission equation
* RIS cascaded link-budget equations
* Lorentzian resonance model
* Quantized phase reflection matrices

---

## Future Work

* Mobility-aware beam tracking
* Doppler analysis
* ML-based localization
* Secure beamforming
* Reinforcement learning based RIS control

---

## Applications

* Industry 5.0
* Industrial IoT (IIoT)
* Smart factories
* RIS-assisted localization
* Secure wireless sensing
* 6G communication systems

---

## Authors

* **Siddhant Deore**
* **Pratham Shetty**

International Institute of Information Technology, Bangalore (IIITB)

---

## License

This project is intended for academic and research purposes.
