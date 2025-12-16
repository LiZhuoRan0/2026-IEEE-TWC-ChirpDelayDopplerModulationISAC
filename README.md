# 2025-JSAC-RadiationPatternReconfigurableAntenna

Simulation codes for our paper, titled *Chirp Delay-Doppler Domain Modulation Based Joint Communication and Radar for Autonomous Vehicles*, which has been accepted by **IEEE TWC** and will be available on arXiv and IEEE soon.

<figure>
    <img src="./Scene.png" alt="场景描述">
    <figcaption>Scenario of this paper.
    </figcaption>
</figure>

# Code Repository for Paper Figures

This repository contains the simulation and plotting code, as well as the original figure files, for the figures in our paper.  
All materials are organized by figure index (e.g., `Fig6,7/`, `Fig8/`, `Fig9/`, `Fig10,11/`), and each folder corresponds to one or more figures in the manuscript.

---

## Repository Overview

For each figure (or group of figures), the following resources are provided in the corresponding folder:

- **Simulation code**: scripts/functions used to generate the numerical results.
- **Plotting code**: scripts used to produce the final figures shown in the paper.
- **Original figure files**: e.g., `.fig`, `.pdf`, `.eps`, or high-resolution image files.

Currently included folders:

- `Fig6,7/` – code and data related to Figures 6 and 7. Some results can also be seen in our IEEE Network paper [IEEE Network](https://github.com/LiZhuoRan0/2025-IEEE-Network-ChirpDelayDopplerModulationISAC).
- `Fig8/` – code and data related to Figure 8.
- `Fig9/` – code and data related to Figure 9.
- `Fig10,11/` – code and data related to Figures 10 and 11.

Each of these folders contains its **own `README` file**, which explains:

- The internal directory structure of that folder;
- The purpose and usage of the main scripts and functions;
- How to run the simulations and regenerate the corresponding figures.

Please refer to the specific `README` inside each folder for detailed instructions.

---

## Development Environment

The code in this repository was developed and tested with:

- **MATLAB**: R2024a  
- **Python**: 3.11  
- **GPU acceleration**:  
  - Some parts of the code are implemented with **GPU acceleration** enabled.



# Abstract
This paper introduces a sensing-centric joint communication and millimeter-wave radar paradigm to facilitate collaboration among intelligent vehicles.
We first propose a chirp waveform-based delay-Doppler quadrature amplitude modulation (DD-QAM) that modulates data across delay, Doppler, and amplitude dimensions.
Building upon this modulation scheme, we derive its achievable rate to quantify the communication performance.
We then introduce an extended Kalman filter-based scheme for four-dimensional (4D) parameter estimation in dynamic environments, enabling the active vehicles to accurately estimate orientation and tangential-velocity beyond traditional 4D radar systems.
Furthermore, in terms of communication, we propose a dual-compensation-based demodulation and tracking scheme that allows the passive vehicles to effectively demodulate data without compromising their sensing functions.
Simulation results underscore the feasibility and superior performance of our proposed methods, marking a significant advancement in the field of autonomous vehicles.


