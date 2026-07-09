# ST-Reconstruction
A robust ST-space feasible region reconstruction and QP-based speed planning framework for autonomous driving with DP-QP optimization and CarSim-Simulink closed-loop simulation.
# Continuous Bidirectional ST Feasible Region Reconstruction for Autonomous Driving Speed Planning

## Overview

This repository provides an implementation of a continuous bidirectional ST (Space-Time) feasible region reconstruction method and robust speed planning framework for autonomous driving.

The proposed method focuses on improving the instability problems caused by traditional DP-QP speed planning frameworks, including:

- Discontinuous ST boundaries
- One-sided feasible constraints
- Local feasible region degeneration
- QP infeasibility caused by dynamic obstacle constraints
- Velocity oscillation and poor smoothness

The framework reconstructs the original discrete ST feasible region into a finite, continuous, and bidirectional feasible corridor, and then performs relaxed QP optimization to generate smooth and executable velocity trajectories.

The method is validated through a closed-loop CarSim-Simulink co-simulation platform.

---

## Paper

**Title**

Continuous Bidirectional ST Feasible Region Reconstruction and Closed-loop Speed Planning Method

**Keywords**

Autonomous Driving · Speed Planning · ST Graph · Feasible Region Reconstruction · Dynamic Programming · Quadratic Programming

---

## Framework

The overall framework is composed of four major modules:
