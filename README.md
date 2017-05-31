# Euler-Method-Radioactive-Decay
Numerical simulation of radioactive decay using Euler method.

This MATLAB script solves the 1st order differential equation for radioactive decay of uranium using the Euler method, given some intial values, and compares the results with curve obtained from plotting the decay equation:
Uranium Quantity = intial Uranium Quantity * exp(-Time / Decay Constant).

- Derivative of the function is taken at time t to estimate it's value after dt.

- Plots a graph comparing the Anlyitical Solution to the numerical solution.

- The smaller the time increment "dt", the more simillar the numerical result to the analytical becomes.

HarmonicOscillator.m is the main script where you run the simulation. Each numerical method function is seperated in a different .m file.

Reference Used: Computational Physics 2nd Edition - Nicholas J. Giordano and Hisao Nakanishi
