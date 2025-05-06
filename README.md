#### Supply_Chain_Models
This project provides an end-to-end, modular solution for demand forecasting and facility location optimization in supply chain management. It is designed to be generic, scalable, and interactive — suitable for academic, research, and industry applications.

##### Demand Forecasting
Implements four time-series forecasting models from scratch:
1. Moving Average
2. Exponential Smoothing
3. Holt’s Linear Trend Model
4. Winters’ Additive Seasonal Model

Each method includes:
- Dynamic parameter input (e.g., alpha, beta, season length)
- Forecast visualization in tabular format
- Forecast accuracy metrics: Bias, MAD, MAPE, MSE, Tracking Signal
- Automated feedback and method recommendations

##### Facility Location Optimization
Solves the capacitated facility location problem using Mixed-Integer Linear Programming (MILP) via the PuLP solver:
- Optimizes which facilities to open
- Minimizes total cost (fixed + shipping)
- Determines optimal shipment plan from facilities to demand points
- Includes utilization insights, load imbalance detection, and actionable suggestions
