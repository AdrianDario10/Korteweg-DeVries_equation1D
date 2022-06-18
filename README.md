# Korteweg-DeVries_equation1D
Physics Informed Neural Network (PINN) for the 1D Korteweg–De Vries equation

This module implements the Physics Informed Neural Network (PINN) model for the 1D Korteweg-De Vries equation. The KdV equation is given by (d/dt + d^3u/dx^3 + u du/dt) = 0. It has an initial condition u(t=0, x) = cos(pi x). Periodic boundary condition is given at x = -1,+1. The PINN model predicts u(t, x) for the input (t, x).

It is based on hysics informed neural network (PINN) for the 1D Wave equation on https://github.com/okada39/pinn_wave
