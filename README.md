# Satellite Attitude Control System Design and Implementation

This repository contains the design and implementation of control techniques for a satellite attitude control system. It covers both classical control techniques (PD Controller) and adaptive control techniques. The primary focus is on addressing the challenges introduced by non-cooperative objects attaching to the satellite, leading to unknown inertia and changes in system momentum.

## Table of Contents
- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Proposed Solution](#proposed-solution)
- [PD Controller Design](#pd-controller-design)
- [Spacecraft Dynamics](#spacecraft-dynamics)
- [Simulink Models and Simulations](#simulink-models-and-simulations)
- [Conclusion](#conclusion)
- [References](#references)

## Introduction
This document details the design and implementation of control techniques for a satellite attitude control system. It includes both classical control methods, such as the PD controller, and modern adaptive control techniques. The document provides a comprehensive framework for control system design by discussing the necessary mathematical formulations and presenting simulation results.

## Problem Statement
When a non-cooperative object (such as space debris or an unintended attachment) attaches to a satellite, it introduces unknown inertia and changes in the system’s momentum. This can lead to instability in the satellite’s attitude control system.

## Proposed Solution
To address this issue, an adaptive control scheme is proposed that estimates the inertia of the new combined system (satellite + attached object). This adaptive control method helps the system reach a stable state quickly and accurately. The stability of the adaptive control scheme is proven using a Lyapunov function.

## PD Controller Design
The PD controller’s design equations are derived, and the controller’s effectiveness is demonstrated by computing the gains (Kp and Kd) for specified system dynamics.

## Spacecraft Dynamics
The Euler’s moment equations and the state-space representation of spacecraft dynamics are discussed, providing a comprehensive framework for control system design.

## Simulink Models and Simulations
Simulink models for three-axis attitude control systems are presented, along with their simulation results. These models demonstrate the effectiveness of the proposed control techniques in maintaining the satellite's stability.

## Conclusion
The proposed adaptive control scheme is robust, effective, and capable of handling the uncertainties introduced by the attachment of non-cooperative objects to satellites.

## References
- [Insert references or sources used in the project here]
