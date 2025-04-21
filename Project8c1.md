# Riemann Sum vs Exact Integral of ln(x)

This Python script approximates the definite integral of the function, ln(x), over the interval [1, e] using the midpoint Riemann sum method. It then compares the result to the exact value computed analytically.

## Context

- **Function**: f(x) = ln(x)
- **Interval**: [1, e]
- **Technique**: Midpoint Riemann Sum with n = 1000 subintervals
- **Exact Value**: Computed using scipy.integrate.quad

## Visualization

A plot is generated using matplotlib:
- Blue curve represents f(x) = ln(x)
- Shaded region represents the area under the curve

## Libraries

Make sure the following libraries are installed:

numpy, 
matplotlib, 
scipy
