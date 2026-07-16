**Previous :** [Day 11 – Introduction to Supervised Learning & Logistic Regression](Day11.md)

---

# Day 12 – Machine Learning Model Implementation & Comparison

**Date:** 15 July 2026

## Objective
Today's objective was to understand how different Machine Learning classification algorithms work and apply them to a dataset for prediction.

---

## Topics Covered

- Introduction to Classification Algorithms
- Train-Test Split
- Naive Bayes Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Model Evaluation
- Accuracy Comparison

---

## Theory Learned

### 1. Naive Bayes
- A probability-based supervised learning algorithm.
- Uses Bayes' Theorem to calculate the probability of each class.
- Assumes all input features are independent.
- Fast and suitable for small datasets.

**Advantages**
- Fast training
- Easy to implement
- Performs well on small datasets

**Limitations**
- Assumes feature independence
- Performance may decrease when features are highly correlated

---

### 2. K-Nearest Neighbors (KNN)

- Instance-based learning algorithm.
- Makes predictions based on the majority class of the nearest neighbors.
- Does not build a model during training.

**Advantages**
- Simple to understand
- Effective on small datasets

**Limitations**
- Slow prediction on large datasets
- Sensitive to feature scaling and noise

---

### 3. Support Vector Machine (SVM)

- Finds the optimal decision boundary (hyperplane) between different classes.
- Works well for both linear and non-linear classification problems.

**Advantages**
- High accuracy
- Effective in high-dimensional data
- Robust classifier

**Limitations**
- Computationally expensive for large datasets
- Requires careful parameter selection

---

## Practical Implementation

### Dataset Preparation

- Loaded the dataset.
- Selected important input features.
- Chose the target variable.
- Split the dataset into:
  - 80% Training Data
  - 20% Testing Data

---

### Models Implemented

- Gaussian Naive Bayes
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

For each algorithm:

- Trained the model
- Predicted test data
- Calculated Accuracy
- Generated Classification Report
- Generated Confusion Matrix

---

## Model Comparison

The accuracy of all three models was compared using a summary table.

The comparison helped understand:

- Which algorithm performed better.
- Difference between probability-based, distance-based and boundary-based classifiers.
- Advantages and limitations of each algorithm.

---

## Learning Outcome

Today I learned how classification algorithms are trained and evaluated on real datasets. I understood the working principles of Naive Bayes, KNN and SVM, learned how to split data into training and testing sets, evaluate model performance using accuracy, classification report and confusion matrix, and compare multiple machine learning models to identify the best-performing classifier.
