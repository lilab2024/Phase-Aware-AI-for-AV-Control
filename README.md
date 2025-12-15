# Phase-Aware AI for Autonomous Vehicle Control

This repository contains the source code for the paper **"Phase-Aware AI for Socially Compliant Autonomous Vehicle Control"** (under submission, IEEE Transactions, 2025). The code implements the Phase-Aware AI (PAAI) model integrated with car-following (CF) models, specifically Optimized Velocity Relative Velocity (OVRV) and Intelligent Driver Model (IDM), to enhance autonomous vehicle (AV) control. It includes scripts for model training, evaluation, and generating metrics such as RMSE and jerk statistics, as presented in the paper.

## Paper Overview
The paper proposes the PAAI model, which enhances traditional CF models by incorporating phase-aware attention mechanisms to improve AV responsiveness and safety. Key contributions include:
- Integration of PAAI with OVRV and IDM for adaptive acceleration control.
- Evaluation of RMSE for acceleration, speed, and spacing across models (OVRV, OVRV PAAI, IDM, IDM PAAI, Baseline AI).
- Analysis of jerk statistics for internal combustion engine (ICE) vehicles and electric vehicles (EVs) under various gap settings.

The code supports replication of experiments, including model training, metric computation, and visualization of results (e.g., spacing box plots, density distributions, KS-CDF plots).

