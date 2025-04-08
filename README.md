# Project 6 Part 2 – Power Series Approximation and Visualization

**By**: Preston Brownlee  
**Course**: CST-305 – Principles of Modeling & Simulation  
**Instructor**: Professor Citro  
**Date**: April 6, 2025  

---

## Project Overview

This program visualizes a **power series solution** to a second-order linear differential equation using a recurrence relation derived manually. The equation being solved is:

(x^2 + 4)y'' + y = x

After confirming that \( x = 0 \) is an ordinary point, the solution is expressed as a **power series** centered at \( x = 0 \). The recurrence relation is used to compute terms up to \( x^5 \), resulting in the following approximation:

y(x) ≈ a₀(1 - 1/8 x² + 1/128 x⁴) + a₁(x - 1/24 x³ + 7/1920 x⁵)

---

## How to Run the Code

### Prerequisites

Make sure you have **Python 3** installed with the following libraries:

- `numpy`
- `matplotlib`

Running the Script
- Open a terminal or Python IDE
- Save the file as Project6Part2.py, or copy and paste the code into a new script.
- Run the script
