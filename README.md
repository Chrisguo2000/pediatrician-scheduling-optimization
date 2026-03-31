# Pediatrician Scheduling Optimization

This project solves a **Pediatrician Scheduling Problem** using mathematical optimization with **Gurobi**.  
The objective is to generate a feasible and efficient four-week work schedule for pediatricians while satisfying operational constraints.

## Project Background

Hospitals must schedule doctors while balancing multiple constraints such as:

- minimum staffing requirements
- working hour limits
- shift continuity
- fairness among physicians

Manually creating schedules is difficult and time-consuming.  
This project formulates the scheduling task as an **optimization problem** and uses **integer programming** to automatically generate a feasible schedule.

## Methodology

The scheduling problem is modeled as a **Mixed Integer Programming (MIP)** problem.

### Decision Variables
- Assignment of pediatricians to shifts and days

### Constraints
Examples include:

- minimum number of doctors required per shift
- limits on consecutive working days
- rest requirements between shifts
- coverage requirements for the entire planning horizon

### Objective
The optimization model aims to:

- generate a feasible schedule
- minimize soft constraint violations
- maintain fairness among physicians

The model is implemented in **Python using Gurobi**.

## Project Structure
