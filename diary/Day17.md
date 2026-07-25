**Previous :** [Day 16 – Feature Selection Techniques](Day16.md)

---

# Day 17 – Wrapper-Based Feature Selection Techniques

**Date:** 22 July 2026

## Objective

Today's objective was to understand Wrapper-based Feature Selection techniques and learn how machine learning models can be used to identify the most relevant subset of features for improving prediction performance.

---

## Theory Learned

The session began with an introduction to **Wrapper Methods**, one of the major categories of feature selection techniques. Unlike filter methods, wrapper methods evaluate different combinations of features by repeatedly training a machine learning model and selecting the subset that produces the best performance. Since the selection process depends on the learning algorithm, wrapper methods generally provide better feature subsets but require more computational time.

The trainer explained that wrapper methods are capable of capturing feature interactions and often produce higher prediction accuracy because the selected features are evaluated based on the actual model performance rather than only statistical measures.

Several commonly used wrapper techniques were discussed during the session:

### Forward Selection

Forward Selection begins with an empty feature set and gradually adds one feature at a time. At each step, the feature that improves the model performance the most is selected. The process continues until adding more features no longer provides significant improvement.

### Backward Elimination

Backward Elimination follows the opposite approach. It starts with all available features and removes the least important feature one by one. Features whose removal does not negatively affect the model performance are discarded until only the most significant features remain.

### Recursive Feature Elimination (RFE)

Recursive Feature Elimination (RFE) repeatedly trains a machine learning model, ranks all features according to their importance, and removes the least important feature in every iteration until the required number of features is obtained. This technique helps identify the optimal subset of features while maintaining good model performance.

### Recursive Feature Elimination with Cross Validation (RFECV)

RFECV is an extension of RFE that automatically determines the optimal number of features by combining Recursive Feature Elimination with Cross Validation. Instead of manually specifying how many features should be retained, RFECV evaluates different feature subsets and selects the one that provides the best cross-validation performance.

---

## Practical Implementation

The practical session focused on implementing wrapper-based feature selection techniques using Python and the **Scikit-learn** library.

The dataset was first prepared by separating the input features and target variable. Categorical attributes were encoded before applying the feature selection algorithms.

The trainer demonstrated the implementation of **Forward Selection** and **Backward Elimination** using Sequential Feature Selector. Different subsets of important features were generated and compared based on model accuracy.

Next, **Recursive Feature Elimination (RFE)** was implemented to rank the importance of each feature and identify the best-performing feature subset. Finally, **RFECV** was used to automatically determine the optimal number of features through cross-validation.

The results obtained from all wrapper methods were compared to observe how each technique selected different feature combinations while aiming to improve model performance and reduce unnecessary features.

---

## Learning Outcome

Today's session provided a comprehensive understanding of Wrapper-based Feature Selection techniques and their role in building efficient machine learning models. I learned the working principles of Forward Selection, Backward Elimination, Recursive Feature Elimination (RFE), and RFECV, along with their advantages and practical applications. The practical implementation helped me understand how different wrapper methods evaluate feature importance based on model performance and how selecting an optimal feature subset can improve prediction accuracy while reducing model complexity.


---

**Next :** [](Day18.md)
