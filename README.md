# DART - Debris Acquisition and Reconnaissance Telescope

DART is a conceptual optical payload designed for **close-range Space Domain Awareness (SDA)** in Low Earth Orbit (LEO). Unlike traditional systems that focus solely on tracking, DART combines high-rate target tracking with passive spectro-polarimetric material characterization within a single optical architecture.

This repository contains the presentation material developed for the **T-TeC 2025** competition.

## Overview

The proposed payload integrates:

- 30 cm Ritchey–Chrétien telescope
- Off-Axis Parabolic (OAP) relay optics
- Dual Fast Steering Mirror (FSM) stabilization system
- Broadband wire-grid polarimetric analysis
- Multi-band dichroic photometry
- Photon budget and detector sizing analysis

The objective is to characterize nearby orbital debris using reflected sunlight while maintaining closed-loop tracking at high frame rates.

## Main Contributions

- Compact optical architecture for proximity debris inspection
- Closed-loop tracking using dual Fast Steering Mirrors
- Simultaneous spectro-photometric and polarimetric measurements
- Complete photon budget from solar irradiance to detector electrons
- Trade-off analysis for detector technologies (InGaAs / Extended InGaAs)
- Low-cost prototype concept based on commercial off-the-shelf (COTS) components

## Technologies

The analyses presented were developed using:

- COMSOL Multiphysics (Ray Optics)
- Python numerical analysis
- Optical component catalogues from Thorlabs, Edmund Optics and Newport

## Future Work

- Breadboard implementation (TRL 4)
- Experimental validation of the optical throughput
- Closed-loop FSM control implementation
- Characterization of dichroic leakage and polarization performance
- Integration with an automated optical component selection database

## License & Data

This repository is provided for academic, please cite or reference the project if you use any part of this work.
Data and simulation models are available upon request from the contributors.
