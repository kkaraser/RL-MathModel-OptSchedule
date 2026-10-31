# RL-Driven Optimization of R-CHOP Scheduling in DLBCL

## Overview
This repository implements a six-dimensional mechanistic ODE model of Diffuse Large B-Cell Lymphoma (DLBCL) coupled with a tabular Q-learning agent to optimize inter-cycle R-CHOP-21 treatment intervals. 
It includes sequential parameter calibration (`L-BFGS-B`), multi-seed Q-learning, a continuous-state model-based search benchmark, Latin Hypercube Sampling–PRCC sensitivity analysis ($N=250$), 
and closed-loop virtual patient cohort simulations ($N=100$).

## Software Environment & Installation
All simulations were executed using the following environment:
* **Python:** `3.13.16`
* **NumPy:** `2.1.3`
* **SciPy:** `1.16.3`
* **Pandas:** `2.2.3`
* **Matplotlib:** `3.10.0`

Install dependencies via:
```bash
pip install numpy==2.1.3 scipy==1.16.3 pandas==2.2.3 matplotlib==3.10.0 openpyxl
