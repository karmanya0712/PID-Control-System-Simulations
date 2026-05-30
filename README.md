# PID Control System Simulations using MATLAB Simulink

## Overview

This repository contains MATLAB Simulink simulations exploring PID controller tuning, feedback control systems, damping behavior, overshoot reduction, and system response analysis using second-order systems.

The project focuses on developing practical control systems intuition through experimentation with proportional (P), integral (I), and derivative (D) controller gains.

---

## Topics Covered

* Transfer Functions
* Closed Loop Feedback Systems
* PID Controller Tuning
* Overshoot and Damping Analysis
* Error Signal Analysis
* Controller Output Analysis
* MATLAB Simulink Modeling

---

# Project 1 — PID Control of a Second-Order System

## Objective

To study how PID controller gains affect:

* overshoot
* oscillation
* damping
* settling time
* steady-state behavior

using MATLAB Simulink.

---

## System Used

Transfer Function:

G(s) = 1 / (s^2 + 2s + 1)

The system was tested using different PID gain combinations to observe various response characteristics.

---

## Simulations Performed

### Underdamped Response

* High proportional and integral gain
* Large overshoot and oscillation observed

### Overdamped Response

* Large derivative gain used
* Smoother but slower response observed

### Balanced Response

* Tuned proportional and derivative values
* Stable response with reduced oscillation and overshoot

---

## Key Observations

* Increasing proportional gain improved response speed but increased overshoot.
* Large derivative gain introduced oscillatory behavior in this system.
* Reducing derivative gain improved damping and stabilized the response.
* Integral action altered transient behavior and introduced slight overshoot.
* PD control produced smoother behavior for this plant compared to the tested PID configurations.

---

# Files Included

* PID CONTROLLER.pdf
* DC motor with PID controller.pdf
* MATLAB Simulink simulation files

Note: Simulation screenshots and response graphs are included inside the PDF reports.

---

## Tools Used

* MATLAB
* Simulink
* Git
* GitHub

---

## Learning Outcome

This project helped develop intuition for:

* feedback systems
* PID tuning
* controller aggressiveness
* damping behavior
* oscillation analysis
* control system stability

through iterative experimentation and response analysis in Simulink.
