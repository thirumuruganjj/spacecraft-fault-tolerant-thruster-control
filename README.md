# Fault-Tolerant Thruster Control and Detection for Spacecraft

[![MATLAB](https://img.shields.io/badge/MATLAB-R2023b%2B-orange.svg)](https://www.mathworks.com/products/matlab.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Domain: Spacecraft GNC](https://img.shields.io/badge/Domain-Spacecraft%20GNC%20%26%20Attitude%20Control-blue.svg)]()

> **Residual-Based Fault Detection & Isolation (FDI) and Pseudoinverse Reallocation for an 8-Thruster Spacecraft Platform**

---

## 1. Overview

Spacecraft operating in proximity operations or performing critical translational and rotational maneuvers rely on multi-thruster clusters. Thruster anomalies—such as **stuck-off, stuck-on, degraded thrust, or nozzle misalignment**—jeopardize mission safety. 

This repository implements an end-to-end **Fault-Tolerant Control (FTC)** and **Fault Detection and Isolation (FDI)** framework for a $450\text{ kg}$ spacecraft ($I_{zz} = 100\text{ kg}\cdot\text{m}^2$) equipped with 8 body-fixed thrusters in MATLAB.
