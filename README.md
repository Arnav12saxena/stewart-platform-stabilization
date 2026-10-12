# Intelligent Stewart Platform for Payload Stabilization

**Project context:** Student robotics project at IIT Mandi  
**Stage:** Early development — CAD design, MATLAB simulation, and control-system validation are planned/in progress.

## Overview

We are exploring a six-degree-of-freedom (6-DOF) Stewart platform for stabilizing a payload using six actuators, IMU-based orientation sensing, inverse kinematics, and feedback control.

Potential applications include camera mounts, sensor platforms, and other payloads that need orientation stabilization.

## Objectives

- Develop a dimensionally consistent mechanical CAD assembly.
- Derive and validate inverse kinematics for the platform geometry.
- Build a MATLAB simulation of platform motion and actuator lengths.
- Explore IMU-based orientation estimation and feedback control.
- Evaluate performance under disturbances using orientation error, settling time, and overshoot.

## Proposed system architecture

1. **Mechanical platform:** Fixed base, moving platform, six actuators, and joints.
2. **Sensing:** IMU measurements for platform orientation.
3. **Kinematics:** Map desired platform pose to actuator lengths.
4. **Control:** Compute corrective commands from pose/orientation error.
5. **Simulation and evaluation:** Test motion profiles and disturbances before hardware trials.

## Repository structure

- `docs/` — project overview, milestones, and technical notes
- `website/` — simple project landing page suitable for GitHub Pages
- `matlab/` — reserved for MATLAB scripts and simulations
- `cad/` — reserved for CAD exports and assembly notes

## Current status

This repository is a project starter. It does not yet contain validated CAD models, simulation results, or tested controller code. Add only files and results that the team has permission to publish.

## Team

Student project team at IIT Mandi.

## License

No license has been selected yet. Add a license only after the team agrees on the terms.
