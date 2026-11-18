# Reproducible Bimanual Robot Learning Environment for xArm Manipulation

**UC Berkeley | Master of Engineering Capstone | Robotics**

**Bimanual Manipulation • Teleoperation • Robot Simulation • Imitation & Reinforcement Learning**

## Project Overview

This project focuses on building a **reproducible and extensible bimanual robot learning environment** using two xArm robotic manipulators.

The goal is to develop an integrated platform for collecting high-quality human demonstrations, training robot learning policies, and evaluating their performance consistently across simulation and physical hardware.

By standardizing the robot environment, teleoperation interfaces, and evaluation procedures, the project aims to make robotic manipulation research more reproducible and accessible for future students and researchers.

## Project Objectives

The project consists of three primary development areas:

### 1. GELLO-Style Teleoperation

Develop physical teleoperation controllers that allow human operators to manipulate the two xArm robots.

These controllers will be used to collect expert demonstrations of bimanual manipulation tasks, generating datasets for imitation learning.

### 2. GPU-Parallelizable Simulation

Develop a simulation environment that replicates the physical bimanual robot workspace.

The simulation is intended to support parallel experimentation, enabling efficient development and training of robotic manipulation policies before evaluating them on real hardware.

### 3. Standardized Policy Evaluation

Establish a reproducible evaluation pipeline for testing imitation learning and reinforcement learning policies.

The framework aims to support consistent comparisons of policy performance across simulated and real-world manipulation tasks.

## Hardware Setup

The experimental platform includes:

- Two xArm robotic manipulators
- Two GELLO-style teleoperation controllers
- Table-mounted bimanual workspace
- External cameras and camera mounting infrastructure
- Dedicated robot control computers
- Safety enclosure

## My Contributions

My work focuses on the development and integration of the robotic simulation and teleoperation infrastructure.

Key responsibilities include:

- Developing the simulation environment for the dual-arm xArm setup.
- Implementing and integrating teleoperation controllers for robot manipulation.
- Developing the infrastructure for collecting human demonstration data.
- Supporting the integration of simulation and physical robotic systems.

## Software and Technologies

**Core Development:** Python, Linux

**Robotics:** xArm manipulators, bimanual robot control, GELLO-style teleoperation

**Simulation:** GPU-parallelizable robot simulation

**Robot Learning:** Imitation learning, reinforcement learning, learning from demonstrations

**Planned/Considered Tools:** ROS2, xArm SDK, Isaac Sim or MJX, PyTorch or JAX

*The final software stack will be updated as development progresses.*

## Project Status

**Ongoing — UC Berkeley MEng Capstone**

Current development focuses on the robot simulation, teleoperation framework, and infrastructure for demonstration data collection.

Future work includes training learning-based manipulation policies and evaluating their performance in simulation and real-world experiments.

## Demonstrations

Demonstration videos and experimental results will be added as development progresses.

## Acknowledgments

Developed as part of the Master of Engineering capstone program at the University of California, Berkeley.

This repository documents the project objectives, technical development, and my individual contributions. The team's collaborative source-code repository is maintained separately.
