![Python](https://img.shields.io/badge/Python-3.11-blue)
![NumPy](https://img.shields.io/badge/NumPy-Framework-orange)
![License](https://img.shields.io/badge/License-MIT-green)
# Deep Learning Framework from Scratch using NumPy

A modular deep learning framework implemented entirely from scratch using **Python** and **NumPy**, without relying on deep learning libraries such as TensorFlow or PyTorch.

The project demonstrates the complete implementation of the fundamental building blocks of modern deep learning, including forward propagation, backpropagation and optimization algorithms. 

## Project Overview

This project implements the core components of a deep learning framework
from scratch using NumPy.

Instead of relying on TensorFlow or PyTorch, every operation including
forward propagation, backpropagation, gradient computation, and parameter
updates was manually implemented to gain a deeper understanding of how
neural networks work internally.

---

## Features

### Core Layers
- Base Layer
- Fully Connected (Dense) Layer

### Activation Functions
- ReLU
- SoftMax

### Loss Functions
- Cross Entropy Loss

### Optimization Algorithms
- Stochastic Gradient Descent (SGD)

### Other Components
- Neural Network Training Pipeline
- Forward & Backward Propagation
- Gradient Checking
- Weight Updates
- Data Handling Utilities

---

## Repository Structure

```text
Neural-Network-from-Scratch/
│
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
│
├── src_to_implement/
│   ├── NeuralNetwork.py
│   └── NeuralNetworkTests.py
│   │
│   ├── Layers/
│   │   ├── __init__.py
│   │   ├── Base.py
│   │   ├── FullyConnected.py
│   │   ├── ReLU.py
│   │   └── SoftMax.py
│   │   └── Helpers.py
│   │
│   ├── Optimization/
│   │   ├── __init__.py
│   │   ├── Loss.py
│   │   └── Optimizers.py
│
├── Output/
│   ├── Loss Function Iris SGD.png

```

---

## Concepts Implemented

This project covers the implementation of:

- Feed Forward Neural Networks
- Backpropagation
- Chain Rule
- Gradient Descent
- Jacobian Computation
- Gradient Checking

---

## Mathematical Foundations

The implementation is based on

- Chain Rule
- Matrix Calculus
- Jacobians
- Gradient Descent
- Numerical Differentiation
- Mini-Batch Learning

## How It Works

Training follows the standard deep learning pipeline:

```text
Input
   │
   ▼
Forward Propagation
   │
   ▼
Loss Computation
   │
   ▼
Backpropagation
   │
   ▼
Gradient Calculation
   │
   ▼
Optimizer Update
   │
   ▼
Updated Parameters
```

---

## Technologies Used

- Python
- NumPy
- SciPy
- Matplotlib
- scikit-learn

---

## Learning Outcomes

Through this project, I developed a strong understanding of:

- Mathematical foundations of deep learning
- Manual implementation of forward and backward propagation
- Gradient computation using the chain rule
- Numerical gradient checking
- Designing a modular deep learning framework

---

## Training Results

The figure below shows the training loss of the neural network on the Iris dataset using Stochastic Gradient Descent (SGD). The steadily decreasing loss demonstrates that the implemented forward propagation, backpropagation, and parameter update pipeline are functioning correctly.

<p align="center">
    <img width="640" height="480" alt="Loss Function Iris SGD" src="https://github.com/user-attachments/assets/e33f01cd-066c-439f-ab3a-738ec2326e01" />
</p>

*Figure 1: Training loss over 4000 iterations on the Iris dataset using SGD.*

### Discussion

- The loss decreases rapidly during the first few hundred iterations.
- As training progresses, the optimization converges to a lower loss.
- This confirms the correctness of the implemented forward pass, backpropagation, and SGD optimizer.

## Future Improvements
- Convolution Operations
- Pooling Operations
- Batch Normalization
- Regularization
- Weight Initialization
- Sequence Modeling using RNNs
- Long Short-Term Memory Networks (LSTMs)
- Attention Mechanisms
- Transformer Architecture
- Multi-Head Attention
- Residual Networks (ResNet)
- GPU Acceleration
- Automatic Mixed Precision
- Additional Optimizers
- Model Serialization
- Support for Custom Datasets

---

## Acknowledgements

This project was developed as part of the **Deep Learning** coursework at **Friedrich-Alexander University Erlangen-Nürnberg (FAU)**. The framework was implemented from scratch for educational purposes to gain an in-depth understanding of modern deep learning algorithms and architectures.

---

## License

This project is licensed under the MIT License.
