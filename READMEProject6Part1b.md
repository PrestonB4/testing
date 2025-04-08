# Project 6 Part 1(b) – Taylor Polynomial Visualization

**By**: Preston Brownlee  
**Course**: CST-305 – Principles of Modeling & Simulation  
**Instructor**: Professor Citro  
**Date**: April 6, 2025  

---

## Project Overview

This program visualizes a second-degree Taylor polynomial approximation for a second-order linear differential equation. The equation being solved is:
y'' - (x - 2)y' + 2y = 0
Initial conditions: y(3) = 6, y'(3) = 1


Using the Taylor expansion centered at **x = 3**, the program estimates the behavior of \( y(x) \) using the following approximation:

y(x) ≈ 6 + (x - 3) - (11/2)(x - 3)^2


This approximation is then expanded into standard form for plotting:

y(x) = -(11/2)x^2 + 34x - (93/2)


The program generates a graph of this quadratic function and highlights the center point \( x = 3 \), where the Taylor approximation is most accurate.

---

## How to Run the Code

### Prerequisites

Make sure you have **Python 3** installed, along with the following packages:

- `numpy`
- `matplotlib`
  
Running the Script
- Open a terminal or Python IDE
- Save the file as Project6Part1b.py, or copy and paste the code into a new script.
- Run the script
