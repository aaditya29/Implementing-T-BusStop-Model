# T-BSP: Multi-Trip Bus Stop Model

Implementation of the **Multi-Trip Bus Stop Model (T-BSP)** based on the paper:

> [Towards Fair and Efficient Public Transportation: A Bus Stop Model](https://arxiv.org/abs/2411.08784)
> Bullinger, Elkind, Latifian (AAMAS 2025)

This project extends the original BSP framework to the **multi-trip setting** where each agent performs \(T\) trips instead of a single trip.

---

## Overview

The repository includes:

- Dynamic Programming (DP) implementation for optimal stop placement
- Multi-Trip extension of Algorithm 1 (Density-Proportional Placement)
- Aggregate Justified Representation (A-JR)
- Approximate core violation checking
- Random instance generation
- Experimental evaluation and visualization
