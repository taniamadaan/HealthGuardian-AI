**Previous :** [Day 13 – Project Evaluation & Progress Review](Day13.md)

---

# Day 14 – Decision Tree & Random Forest Classification

**Date:** 17 July 2026

## Objective

Today's objective was to understand tree-based machine learning algorithms, implement Decision Tree and Random Forest classifiers, evaluate their performance, and compare their results for classification tasks.

---

## Theory Learned

### 1. Decision Tree

A Decision Tree is a supervised machine learning algorithm that predicts outcomes by splitting the dataset into smaller subsets using a tree-like structure. It makes decisions based on a sequence of conditions and can be used for both classification and regression problems.

**Important Concepts**

- **Gini Impurity:** Measures how pure a node is after splitting the data.
- **Entropy:** Measures the randomness or disorder present in a node.
- **Information Gain:** Determines the best feature for splitting by measuring the reduction in entropy.

**Advantages**

- Easy to understand and interpret.
- Requires minimal data preprocessing.
- Works with both numerical and categorical data.
- Fast prediction after training.
- Easy to visualize.

**Disadvantages**

- Can easily overfit the training data.
- Sensitive to noisy datasets.
- Small changes in data may produce different tree structures.

---

### 2. Random Forest

Random Forest is an ensemble learning algorithm that combines multiple Decision Trees to improve prediction accuracy and reduce overfitting. Each tree is trained on a different subset of the data, and the final prediction is made using majority voting.

**Advantages**

- Higher accuracy than a single Decision Tree.
- Reduces overfitting.
- Handles large datasets efficiently.
- More robust to noisy data.

**Disadvantages**

- Slower than a single Decision Tree.
- Uses more memory.
- More difficult to interpret.

---

## Practical Implementation

The practical session included the implementation of both Decision Tree and Random Forest classifiers using Scikit-learn.

The following steps were performed:

- Loaded the dataset using Pandas.
- Selected input features and target variable.
- Split the dataset into training and testing sets.
- Trained a **Decision Tree Classifier** using the Gini criterion.
- Evaluated the model using:
  - Accuracy Score
  - Classification Report
  - Confusion Matrix
- Visualized the complete Decision Tree structure.
- Tested the model using sample input values for prediction.

After implementing the Decision Tree model, a **Random Forest Classifier** was trained and evaluated using the same dataset.

Additional tasks included:

- Predicting outcomes for new sample records.
- Calculating **Feature Importance** using Random Forest.
- Visualizing feature importance with a bar graph.
- Comparing the performance of Decision Tree and Random Forest models based on accuracy, overfitting, speed, interpretability, and prediction capability.

---

## Learning Outcome

Today's session helped me understand how tree-based machine learning algorithms make decisions and perform classification tasks. I learned the concepts of Gini Impurity, Entropy, and Information Gain, implemented Decision Tree and Random Forest classifiers, evaluated their performance using different metrics, visualized the decision-making process, and analyzed feature importance. I also understood why Random Forest generally provides more reliable predictions than a single Decision Tree by combining the outputs of multiple trees.
