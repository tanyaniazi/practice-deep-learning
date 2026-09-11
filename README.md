# Practice Deep Learning from Scratch

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Math-013243.svg?logo=numpy&logoColor=white)](https://numpy.org/)
[![DeepLearning.AI](https://img.shields.io/badge/Course-DeepLearning.AI-orange.svg)](https://www.deeplearning.ai/)
[![Deep Learning Certificate](certificate.png)](certificate.png)

This repository contains implementations of deep neural network architectures built entirely **from scratch using Python and NumPy**, without relying on high-level deep learning frameworks like TensorFlow or PyTorch. The code and exercises were implemented as part of the renowned **DeepLearning.AI** specialization instructed by **Andrew Ng**.

---

## 📌 Core Concepts & Implementations

* **Neural Network Fundamentals:**
  * Implementing forward propagation and vectorization from scratch.
  * Backward propagation (backprop) calculating gradients for weights and biases.
* **Activation Functions:**
  * Sigmoid and ReLU activation functions alongside their respective backward derivatives (`sigmoid_backward`, `relu_backward`).
* **Parameter Initialization:**
  * Random initialization and He/Xavier scaling initialization for deep networks.
* **Model Evaluation & Diagnostics:**
  * Cross-entropy cost computation, gradient descent optimization updates, accuracy checking, and mislabeled image visualization.

---

## 📁 Repository Structure

```text
├── datasets/                 # Training and testing HDF5 datasets (e.g., Cat vs. Non-Cat classification)
├── images/                   # Sample image assets for evaluation
├── dnn_app_utils_v3.py       # Modular backend functions (forward/backward passes, parameters, helpers)
├── building_model.ipynb      # Main Jupyter notebook executing the deep neural network pipeline
└── README.md                 # Project overview and course attribution
