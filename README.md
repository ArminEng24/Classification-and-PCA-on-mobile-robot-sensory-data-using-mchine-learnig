# Classification-and-PCA-on-mobile-robot-sensory-data-using-mchine-learning

## Description
This project involves classification and Principal Component Analysis (PCA) on mobile robot sensory data. The goal is to explore the effects of different hyperparameters and PCA dimensions on the classification accuracy.

## Table of Contents  
- [Dataset](#dataset)  
- [Code Structure](#codestructure)
  - [Classification-with-MLPClassifier](#classification-with-mlpclassifier)
  - [Applying-PCA-and-Perform-Classification-on-Reduced-Datasets](#applying-pca-and-perform-classification-on-reduced-datasets)
- [Experiments](#experiments)
- [Results](#results)
- [Conclusion](#conclusion)

## Dataset
The dataset used in this project can be downloaded from Kaggle.

## Code Structure
The code is organized into two main sections:

### Classification-with-MLPClassifier

- Import necessary libraries and load the dataset
- Split the data into training and testing sets
- Define hyperparameters for MLPClassifier
- Train and evaluate the classifier with different hyperparameters
- Plot the accuracy over training time


### Applying-PCA-and-Perform-Classification-on-Reduced-Datasets

- Load the dataset
- Define the range of n_components to try
- Split the data into training and testing sets
- Initialize PCA and transform the data
- Train and evaluate the classifier on the PCA-transformed data
- Plot the accuracy vs number of components

## Experiments
The following experiments were conducted:

- Changing hidden layer sizes
- Trying different activation functions
- Adjusting learning rates
- Exploring different solvers
- Varying max iterations

## Results
The results of the experiments are presented in the form of plots and accuracy scores.

## Conclusion
This project demonstrates the importance of hyperparameter tuning and dimensionality reduction in classification tasks. The results show that the choice of hyperparameters and PCA dimensions can significantly impact the classification accuracy.
