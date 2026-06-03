# OPTCON_Project
Optimal Control's final project. 

This repository contains the implementation of optimal control strategies for an underactuated flexible surface. 

The goal of the project is to control a simulated flexible surface composed of four points, where only two are actuated.  

Key Features:

Trajectory Generation: Computation of optimal trajectories (both smooth and non-smooth) to move the surface between equilibrium points using Newton's method.  

LQR Tracking: Implementation of a Linear Quadratic Regulator for fast, smooth, and robust trajectory tracking.  

MPC Tracking: Implementation of Model Predictive Control to track the trajectory while strictly handling physical input constraints.  

Comparison: Performance analysis highlighting the trade-offs between LQR (faster error convergence) and MPC (better constraint management).  
