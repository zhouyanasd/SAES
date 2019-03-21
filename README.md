# SAES
This repository offers an approach to combine the Covariance Matrix Adaptive Evolution Strategy (CMA-ES) and Bayesian Optimization (BO). 

## Bayesian optimization assisted by CMA-ES 
This part mainly focusses on searching the approximate best solution to the surrogate model built by gaussian processes. CMA-ES is adopting on the acquisition function as the optimization method 

## Evolution Strategies assisted by Gaussian Processes with Pre-selection
This part mainly focuses on Surrogate model assisted evolutionary Strategies (SAES). The fitness approximation with gaussian processes firstly used for the pre-selection of the offspring which can reduce the computational cost of the expensive fitness function.
