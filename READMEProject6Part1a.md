# Project 6 Part 1(a) – Taylor Polynomial Visualization

**By**: Preston Brownlee  
**Course**: CST-305 – Principles of Modeling & Simulation  
**Instructor**: Professor Citro  
**Date**: April 6, 2025  

---

## Project Overview

This project visualizes a Taylor polynomial approximation for a second-order nonlinear differential equation used to model system performance. The equation being solved is:
y'' - 2x y' + x² y = 0
Initial conditions: y(0) = 1, y'(0) = -1


We use a 4th-degree Taylor polynomial centered at **x = 0** to estimate the value of **y(3.5)**. The resulting polynomial is:

y(x) ≈ 1 - x - (1/3)x³ - (1/12)x⁴


The program generates a graph of the polynomial and marks the value at **x = 3.5**, showing how Taylor methods can be used to approximate solutions to differential equations numerically.

## How to Run the Code

### Prerequisites

Make sure you have Python 3 installed, along with the following Python packages:

- `numpy`
- `matplotlib`

Running the Script

- Open a terminal or Python IDE

- Save the file as Project6Part1a.py or copy and paste to a new python script

- Run the script:

