# Wine Quality Classification using Machine Learning

## Overview

This project investigates wine quality prediction using machine learning techniques on the UCI Wine Quality dataset.

The objective is to compare the performance of multiple classification models on an imbalanced multi-class classification problem and identify the most important physicochemical features influencing wine quality.

Models evaluated:

* Support Vector Machine (SVM)
* Artificial Neural Network (ANN)
* Random Forest

---

## Dataset

Source:

UCI Machine Learning Repository – Wine Quality Dataset

The dataset contains 1,599 samples of Portuguese red wine.

Features include:

* Fixed acidity
* Volatile acidity
* Citric acid
* Residual sugar
* Chlorides
* Sulphates
* Alcohol
* Density
* pH
* Sulfur dioxide measurements

Target:

Wine quality score (3–8)

---

## Methods

### Exploratory Data Analysis

* Quality distribution analysis
* Feature distribution visualization
* Correlation analysis
* Outlier investigation

### Support Vector Machine

* StandardScaler preprocessing
* RBF kernel
* Hyperparameter tuning with GridSearchCV

### Artificial Neural Network

* Multi-layer Perceptron
* ReLU activation
* SGD optimization
* Architecture tuning

### Random Forest

* Ensemble learning
* Hyperparameter optimization
* Feature importance analysis

---

## Results

Best Performing Model:

Random Forest

Performance:

* Accuracy: 70.0%
* Weighted F1 Score: 0.684

Most important features:

* Alcohol
* Sulphates
* Sulfur dioxide

---

## Repository Structure

report/
Project report

notebooks/
EDA, SVM, ANN, and Random Forest implementations

---

## Team Project

This project was completed as the final project for ESE4170 Machine Learning.

Team Size: 3

My Contributions:

* Random Forest implementation
* Hyperparameter tuning
* Feature importance analysis
* Experimental evaluation
* Conclusion writing

Other components were implemented collaboratively by team members.
