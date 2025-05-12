# Control and Implementation of ABB IRB 140 Industrial Robot

This repository contains the simulation and control code for the project:  
**"Control and Implementation of ABB IRB 140 Industrial Robot in Cartesian Space."**

## Overview

This project focuses on the **modeling, control, and simulation** of the 6-DOF **ABB IRB 140 industrial robot**. The primary goal is to implement and evaluate different control strategies in **Cartesian space**, using the full dynamic model of the robot.

## Objectives

- ✅ Derive the **dynamic equations** of the ABB IRB 140 using the Euler-Lagrange formulation.
- ⚙️ Implement and compare various controllers:
  - **PD Control**
  - **PD + Gravity Compensation**
  - **Inverse Dynamics Control**
  - **Robust Inverse Dynamics Control**
- 🧪 Simulate all controllers using MATLAB/Simulink and assess performance in terms of tracking accuracy, control effort, and robustness.

## Control Strategies

1. **PD Control**  
   Simple position control with proportional and derivative gains.

2. **PD + Gravity Compensation**  
   Enhances PD by adding a gravity torque term derived from the dynamic model.

3. **Inverse Dynamics Control**  
   Uses full robot dynamics to linearize the system and decouple joint interactions.

4. **Robust Inverse Dynamics**  
   Enhances inverse dynamics by adding robustness to model uncertainties and external disturbances.
