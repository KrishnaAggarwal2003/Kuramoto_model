# Kuramoto Model Simulation

This [code.ipynb](https://github.com/KrishnaAggarwal2003/Kuramoto_model/blob/main/code.ipynb) describes a Python implementation of the Kuramoto Model in a Jupyter Notebook. The `.ipynb` file contains object-oriented programming (OOP) code for the Kuramoto Model and produces three output plots.

## Instructions:

- The model is based on simple sinusoidal coupling, with a coupling strength denoted by K.

- The synchrony between the oscillators can be observed through the order parameter r(t), which correlates directly with the degree of synchronization. An \( r(t) \) value close to 0 indicates asynchronous behaviour among the oscillators, while an r(t) value approximately equal to 1 signifies a high degree of synchronization. Therefore, the range of \( r(t) \) is between 0 and 1.

- In this model, the distribution of natural frequencies ($$\omega$$) is assumed to follow a standard normal distribution, with a mean of 0 and a standard deviation of 1.

- The simulation includes N = 100 oscillators and runs for 10 seconds, with a time step of 0.1 seconds.

- The following code implements the OOP structure that encapsulates the equations of the Kuramoto Model and utilizes `solve_ivp` to solve the differential equations.

## Output:

The simulation generates three plots:
1. A plot of r(t) versus time for different values of K.
![Plot of r(t) v/s Time](https://github.com/user-attachments/assets/490c1d44-f640-4129-9697-ca94812b5b5d)
- For K > Kc, the r(t) shows a increase with time, whereas for K < Kc r(t) will remain closer to 0.
   

3. A plot of order_parameter(r) versus K, where K_c (the threshold) is indicated on the x-axis, showing where a sudden increase in the slope occurs.
![Plot for r(t) v/s K (coupling strength)](https://github.com/user-attachments/assets/bc86f259-80c5-406a-9272-a7565a4fa964)
- At a certain point on the x-axis (Kc) there will be a sudden increase in the slope of the graph.


4. A distribution graph of the natural frequencies ($$\omega$$) of the oscillators.
![The distribution of $$/omega$$_](https://github.com/user-attachments/assets/c3568f36-6d2d-4e38-b7d5-08e9f74b881a)
- For this simulation, I have assumed it to be a Standard Gaussian Distribution.

   
