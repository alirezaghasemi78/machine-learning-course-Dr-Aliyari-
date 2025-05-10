ML4022 - Mini Project 1
This repository contains my completed solution for the ML4022 Mini Project 1 assignment, part of the Spring 1403 Machine Learning course at K. N. Toosi University of Technology.

Project Overview
The mini-project includes a variety of machine learning tasks aimed at understanding and applying classification techniques, feature extraction, and evaluation metrics. It is divided into three main questions:

Question 1: Synthetic Data Classification
Visualized and explained the training pipeline of a linear classifier using block diagrams.

Generated a synthetic dataset with 3 features and 4 classes using sklearn.datasets.

Trained a linear classifier using sklearn.linear_model, tuning hyperparameters like learning rate and number of epochs.

Visualized decision boundaries and misclassified points.

Repeated the classification pipeline using the drawdata tool.

Question 2: Fault Detection using Bearing Data (CWRU Dataset)
Collected healthy and faulty bearing condition data.

Segmented the time series into labeled windows.

Extracted statistical features (e.g., RMS, Skewness, Kurtosis) to create a new dataset.

Explained the importance of data normalization and data shuffling.

Built a classifier from scratch without using sklearn and evaluated it using loss functions and performance metrics.

Compared results with a Scikit-learn linear classifier.

Optionally explored using Orange data mining software.

Question 3: Weather Data Regression (Szeged Dataset)
Analyzed correlations and distributions of features.

Applied LS (Least Squares) and RLS (Recursive Least Squares) models to estimate temperature.

Compared model performance and visualized errors.

Optionally explored WLS (Weighted Least Squares) and QR-Decomposition-based RLS.
