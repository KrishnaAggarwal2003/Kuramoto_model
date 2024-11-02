# Kuramoto Model simulation 
The Python implementation of the Kuramoto Model in Jupyter Notebook. The .ipynb contains OOP code of Kuramoto Model and the 3 plots as output.

# Instructions:-
- The model is based on the simple Sinusoidal coupling having a coupling strength K as the coupling strength value

- The synchrony between the oscillators can be observed by the Order parameter r(t) which directly correlates with the degree of synchronisation

- r(t) near to 0 will depict asynchronous behaviour between oscillators whereas r(t) approx. 1 will show a high degree of synchronisation between oscillators. Therefore, the range of r(t) is between 0 to 1.

- In the model, the distribution of omega (natural freq's) is assumed to be a Standard Normal distribution i.e. mean = 0 and std. deviation = 1

- There are N = 100 oscillators and the simulation time is 10 seconds with a time step 0f 0.1 seconds.

- The following code is the OOP code that covers the equations of the Kuramoto Model and uses "solve_ivp" to solve the differential equations.

# There are 3 plots as the output:-
* 1. The plot of r(t) v/s time at different values of K
* 2. The plot of r v/s K where Kc (threshold) is the point at the x-axis where there is a sudden increase in the slope.
* 3. The distribution graph of omega of the oscillators.


# Kuramoto Model Simulation

This document describes a Python implementation of the Kuramoto Model in a Jupyter Notebook. The `.ipynb` file contains object-oriented programming (OOP) code for the Kuramoto Model and produces three output plots.

## Instructions:

- The model is based on simple sinusoidal coupling, with a coupling strength denoted by \( K \).

- The synchrony between the oscillators can be observed through the order parameter \( r(t) \), which correlates directly with the degree of synchronization. An \( r(t) \) value close to 0 indicates asynchronous behavior among the oscillators, while an \( r(t) \) value approximately equal to 1 signifies a high degree of synchronization. Therefore, the range of \( r(t) \) is between 0 and 1.

- In this model, the distribution of natural frequencies (\( \omega \)) is assumed to follow a standard normal distribution, with a mean of 0 and a standard deviation of 1.

- The simulation includes \( N = 100 \) oscillators and runs for a total time of 10 seconds, with a time step of 0.1 seconds.

- The following code implements the OOP structure that encapsulates the equations of the Kuramoto Model and utilizes `solve_ivp` to solve the differential equations.

## Output:

The simulation generates three plots:
1. A plot of \( r(t) \) versus time for different values of \( K \).
2. A plot of \( r \) versus \( K \), where \( K_c \) (the threshold) is indicated on the x-axis, showing where a sudden increase in the slope occurs.
3. A distribution graph of the natural frequencies (\( \omega \)) of the oscillators.
