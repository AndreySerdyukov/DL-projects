# Autoencoder for Dimensionality Reduction and Neural Network Model for Target Prediction

This repository contains a solution for building an autoencoder for dimensionality reduction and using the reduced data to build a neural network model for predicting a target variable.

## Task Breakdown

1. **Data Exploration**:  
   Explore the dataset and identify which features can be discarded or removed to optimize the model.

2. **Autoencoder for Dimensionality Reduction**:  
   Build an autoencoder using **PyTorch** to reduce the dimensionality of the feature set. This will help in compressing the data while preserving the most important features.

3. **Neural Network Model**:  
   Using the reduced-dimension features, build a neural network model in **PyTorch** to predict the target variable. The neural network should have an appropriate number of parameters.  
   - Bonus: Demonstrate knowledge of various layers, activation functions, and optimization strategies in the neural network architecture.

## Results

The final model predicts the target variable based on the reduced-dimensional data, with an autoencoder compressing the features. The performance of the model can be evaluated using standard metrics (e.g., Mean Squared Error, Accuracy).
