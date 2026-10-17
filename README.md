# Brownian Motion Particle Escape Simulation

Simulates the Brownian motion of a particle in a 2D circular domain with an absorbing exit segment, and investigates the **mean exit time** as a function of the segment's angular width θ.

## Overview

The problem models an intracellular particle trying to escape through a small opening on the boundary of a circular region — a biophysically relevant problem in cellular transport.

Key questions explored:
- How does mean exit time scale with the angular width of the exit θ?
- How does the particle's diffusion coefficient affect escape dynamics?

## Contents

| File | Description |
|---|---|
| `Stochastic_Brownian_Motion.ipynb` | Full simulation and analysis |

## Methods

- Monte Carlo simulation of 2D Brownian motion
- Analytical comparison using narrow escape theory
- Sweep over θ to characterize the exit time distribution

## Stack

Python · NumPy · matplotlib
