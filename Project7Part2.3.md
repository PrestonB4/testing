# Project 7 Part 2.3 M/M/1 Queue System Scaling

## Overview

This project simulates and visualizes the effect of scaling (λ) and (μ) by a factor of k in an M/M/1 queuing system. We want to observe how performance metrics behave with this scaling.

## Scaling Assumptions

Defining:
- λ = 2
- μ = 5

We scale both:
- λ => k * λ
- μ => k * μ

## Metrics Calculated

For each scaling factor k, the following metrics are evaluated:

1. **Utilization (ρ)**
 
   ρ = λ / μ
   
   Utilization remains constant when both rates are scaled by the same factor.

3. **Throughput (X)**

   X = λ
   
   Throughput scales linearly with k.

6. **Mean Number in System (E[N])**
   
   E[N] = λ / μ - λ
   
   This value remains unchanged after scaling.

8. **Mean Time in System (E[T])**  

   E[T] = 1 / μ - λ
   
   This value is divided by k as the system becomes faster.

## Visualization

The script gives four separate plots, one for each metric, this shows how they behave as k increases from 1 to 10:

- a. Utilization (ρ)
- b. Throughput (X)
- c. Mean Number in System (E[N])
- d. Mean Time in System (E[T])

## What is needed for this Project

- Python 3
- NumPy
- Matplotlib

