# Physics-Informed Neural Networks (PINNs): Optimization and Ablation Study using DeepXDE

## Overview

This project investigates the performance of Physics-Informed Neural Networks (PINNs) for solving partial differential equations using the DeepXDE framework. The study focuses on Burgers' and Diffusion-Reaction equations and evaluates how architectural choices and training strategies affect model accuracy and convergence.

## Key Contributions

* Implemented PINN models for Burgers' and Diffusion-Reaction equations using DeepXDE.
* Conducted systematic ablation studies on network architecture, activation functions, and optimization strategies.
* Compared Adam and L-BFGS optimizers for PINN training.
* Evaluated the impact of learning-rate scheduling and output transformations.
* Analyzed convergence behavior and solution accuracy using relative error metrics.

## Experiments

### Burgers' Equation

* Adam optimizer baseline
* Adam + L-BFGS fine-tuning
* Network width and depth analysis

### Diffusion-Reaction Equation

* Output transformation techniques
* Swish activation function
* Learning-rate decay scheduling
* Deeper network architectures
* Combined optimization strategies

## Technologies

* Python
* DeepXDE
* TensorFlow
* NumPy
* Matplotlib

## Results

Experimental results showed that optimizer selection, network architecture, and training strategies significantly influence PINN performance. The combination of Adam, learning-rate scheduling, and L-BFGS refinement produced the most accurate solutions.

## Acknowledgements

This work builds upon benchmark examples provided by the DeepXDE framework and extends them through optimization experiments and comparative analysis.
