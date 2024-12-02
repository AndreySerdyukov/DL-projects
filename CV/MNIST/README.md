# MNIST Neural Network Classifier

This repository contains a PyTorch-based neural network for classifying handwritten digits from the MNIST dataset.

## Project Overview

The goal of this project is to build and train a neural network model that can recognize digits (0-9) from the MNIST dataset. The dataset contains 60,000 training images and 10,000 test images of handwritten digits, each 28x28 pixels in grayscale.

## Key Steps

1. **Data Preprocessing**:  
   The MNIST dataset is loaded and preprocessed using PyTorch's `torchvision` library. Images are normalized and reshaped for the neural network.

2. **Neural Network Architecture**:  
   A simple fully connected neural network is built using **PyTorch**. The architecture includes:
   - Input layer with 784 nodes (one per pixel in the 28x28 image).
   - Hidden layers with ReLU activation.
   - Output layer with 10 nodes (one per class, representing digits 0-9).

3. **Model Training**:  
   The network is trained using the cross-entropy loss function and the Adam optimizer. The model is evaluated on the MNIST test dataset.

4. **Evaluation**:  
   The trained model's performance is evaluated based on accuracy on the test set. The model aims for high classification accuracy by optimizing weights during training.

## Requirements
- PyTorch
- torchvision
- matplotlib
