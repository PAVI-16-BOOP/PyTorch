**PyTorch Training Pipeline from Scratch**

This project was built as a learning exercise to understand what happens inside a typical PyTorch training workflow rather than relying on high-level APIs.

# Using the Breast Cancer dataset, I implemented a simple binary classification neural network and manually worked through the core stages of the training process:

Data loading and preprocessing
Train-test splitting
Feature scaling
Label encoding
Converting data to PyTorch tensors
Forward propagation
Binary Cross-Entropy loss computation
Backpropagation using Autograd
Manual gradient descent updates
Model evaluation using classification metrics
Purpose

# The main goal of this project was to gain a deeper understanding of how PyTorch handles:

Computational graphs
Gradient calculation (loss.backward())
Parameter updates
Training loops
Binary classification pipelines

Instead of using torch.nn.Module and built-in optimizers, most components were implemented manually to better understand the mechanics behind PyTorch's training process.

# Dataset
Breast Cancer Classification Dataset
Binary classification task: predicting whether a tumor is benign or malignant

#Key Learnings
  -How tensors and gradients flow through a neural network
  -How Binary Cross-Entropy loss is calculated
  -How Autograd computes gradients
  -How model parameters are updated during training
