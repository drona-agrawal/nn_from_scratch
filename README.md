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

z1 = w1 x + b1  
a1 = sigmoid(z1)  

z2 = w2 a1 + b2  
a2 = sigmoid(z2)  

Loss:
Binary cross-entropy

---

## Results

- Model learns a step function
- Loss decreases over iterations
