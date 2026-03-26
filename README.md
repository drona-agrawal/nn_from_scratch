# Neural Network from Scratch (1-1-1 Architecture)

## Overview
This project implements a simple neural network from scratch using only NumPy.

Architecture:
- 1 input
- 1 hidden neuron
- 1 output neuron

The goal is to demonstrate:
- Forward propagation
- Backpropagation (fully derived)
- Gradient descent

---

## Model

Equations:

z_1 = w_1 x + b_1  
a_1 = sigmoid(z1)  

z_2 = w_2 a_1 + b_2  
a_2 = sigmoid(z2)  

Loss:
Binary cross-entropy

---

## Results

- Model learns a step function
- Loss decreases over iterations
