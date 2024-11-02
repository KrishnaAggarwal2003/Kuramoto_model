# Kuramoto Model Simulation

This document describes a Python implementation of the Kuramoto Model in a Jupyter Notebook. The `.ipynb` file contains object-oriented programming (OOP) code for the Kuramoto Model and produces three output plots.

## Instructions:

- The model is based on simple sinusoidal coupling, with a coupling strength denoted by K.

- The synchrony between the oscillators can be observed through the order parameter r(t), which correlates directly with the degree of synchronization. An \( r(t) \) value close to 0 indicates asynchronous behaviour among the oscillators, while an r(t) value approximately equal to 1 signifies a high degree of synchronization. Therefore, the range of \( r(t) \) is between 0 and 1.

- In this model, the distribution of natural frequencies ($$\omega$$  ,, &Omega) is assumed to follow a standard normal distribution, with a mean of 0 and a standard deviation of 1.

- The simulation includes N = 100 oscillators and runs for a total time of 10 seconds, with a time step of 0.1 seconds.

- The following code implements the OOP structure that encapsulates the equations of the Kuramoto Model and utilizes `solve_ivp` to solve the differential equations.

## Output:

The simulation generates three plots:
1. A plot of \( r(t) \) versus time for different values of \( K \).
2. A plot of \( r \) versus \( K \), where \( K_c \) (the threshold) is indicated on the x-axis, showing where a sudden increase in the slope occurs.
3. A distribution graph of the natural frequencies (\( \omega \)) of the oscillators.
