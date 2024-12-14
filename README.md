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

# Simulation of Kuramoto Model with Watts-Strogratz Small World Network

## Instructions:
This module attempts to simulate the Kuramoto Model but adds a small world network between models using the principles of Watts-Strogatz network rules.
### Kuramoto Oscillator
- The number of oscillators chosen is 100
- The simulation time is 10 seconds with a time step of 0.1
- Distribution of omega is a standard normal distribution
### Small World Network
- The Number of Nodes is equivalent to the number of oscillators
- Both the Regular and Randomized Networks are used and results are used to compare the two
- The probability (p) for Regular is 0.95 whereas for the Randomized portion is 0.05
### Results
The following plots are used for visualizing the dynamics of the Network system:-
- The Circular and Default layout network of both the Regular and Randomized Watts-Strogatz network model
![output](https://github.com/user-attachments/assets/80fae36d-7466-4a96-8ef8-9799140537ea)
![output02](https://github.com/user-attachments/assets/d60445cd-e2da-45a7-93a0-305b8238fcf9)
- The omega frequency distribution between two networks
![output01](https://github.com/user-attachments/assets/397e24f4-1f0a-4532-988b-0389960d35bb)
- The order parameter(r) v/s Coupling strength(K) plot in both cases of Regular and Randomized Network
![rvsk](https://github.com/user-attachments/assets/071747c2-3f14-405d-90a1-ad6858fbf2e8)
- The order parameter(r) v/s Time (t) plot in both cases of Regular and Randomized Network
![rvst](https://github.com/user-attachments/assets/b641dd43-4bba-4051-896b-93f81f5e62ad)
- The degree distribution plots i.e. Bar graph between Fraction of nodes v/s Degree of nodes for both Regular and Random Networks.
![nodal](https://github.com/user-attachments/assets/f4da6605-7b14-41fc-8b1c-c0aea8eaf8dd)
- The Clustering Coefficient Distribution histogram along with the value of the Average Clustering Coefficient for both Regular and Random Networks.
![cluster](https://github.com/user-attachments/assets/701ec292-6a4f-4cc3-ba05-ad03bd3a2d83)



   
