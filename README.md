# Genetic-Disorder-Prediction-Using-Machine-Learning
# Early-Age Genetic Disorder Prediction Using Machine Learning

A Machine Learning-based system for predicting genetic disorders at an early age using medical features, feature selection, and multiple classification algorithms.

## Overview

This project focuses on the early prediction of genetic disorders in individuals below 20 years using Machine Learning. The system processes medical data, selects relevant features, and applies different classification algorithms to predict genetic disorders.

The project also investigates feature reduction to determine whether a smaller set of relevant features can achieve effective prediction while reducing the amount of data required.

> **Note:** This project is developed for academic purposes and is not intended to provide medical diagnosis or treatment recommendations.

## Objectives

- Predict genetic disorders using Machine Learning.
- Support early-age prediction for individuals below 20 years.
- Process and select relevant medical features.
- Compare different classification algorithms.
- Evaluate model performance using multiple metrics.
- Reduce the number of features required for prediction.

## Methodology

Medical Dataset  
↓  
Data Processing  
↓  
Feature Selection using SelectKBest  
↓  
Classification Models  
↓  
Disease Prediction  
↓  
Performance Evaluation

## Machine Learning Algorithms

The following classification algorithms are evaluated:

- Random Forest
- Decision Tree
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Multi-Layer Perceptron (MLP)
- Naive Bayes
- Logistic Regression

## Feature Selection

The project uses **SelectKBest** for feature selection.

A key focus of the project is reducing the number of features used for prediction. The proposed approach uses **10 features** compared with approximately **20–25 features** referenced in previous studies.

## Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

### Reported Results

| Model | Testing Accuracy | F1-Score |
|---|---:|---:|
| Random Forest | 98.16% | 98.16% |
| Decision Tree | 98.22% | 98.22% |
| KNN | 78.93% | 76.32% |
| SVM | 78.26% | 70.99% |
| Logistic Regression | 75.58% | 71.05% |
| MLP | 82.57% | 82.07% |
| Naive Bayes | 78.18% | 73.65% |

## Key Contribution

The main contribution of this project is **feature reduction for efficient genetic-disorder prediction**.

The project reports achieving **99% accuracy using 10 selected features**, compared with the 20–25 features referenced for previous studies.

Reducing the number of features can help simplify the prediction process and reduce the amount of data required.

## Technologies Used

- Python
- Machine Learning
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- SelectKBest
- Medical Dataset

