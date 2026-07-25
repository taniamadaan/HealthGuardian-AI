**Previous :** [Day 17 – Wrapper-Based Feature Selection Techniques](Day17.md)

---

# Day 18 – Hyperparameter Tuning using Grid Search CV & Randomized Search CV

**Date:** 23 July 2026

## Objective

Today's objective was to understand the concept of hyperparameter tuning and learn how selecting appropriate hyperparameter values can improve the performance and reliability of machine learning models.

---

## Theory Learned

The session began with an introduction to **Hyperparameter Tuning**, which is the process of finding the optimal combination of model settings before training a machine learning model. Unlike model parameters that are learned automatically during training, hyperparameters are defined by the user and directly influence how the model learns from the data.

The trainer first explained the difference between **parameters** and **hyperparameters**. Parameters are automatically learned by the model during training, whereas hyperparameters must be selected before training begins. Various important hyperparameters used in different machine learning algorithms were discussed. For **Decision Tree**, hyperparameters such as *max_depth*, *min_samples_split*, *min_samples_leaf*, and *criterion* were explained. Similarly, important hyperparameters of **Random Forest**, **K-Nearest Neighbors (KNN)**, and **Support Vector Machine (SVM)** were also introduced to understand how they affect model complexity, learning behaviour, and prediction accuracy.

The trainer then demonstrated two widely used hyperparameter optimization techniques: **Grid Search Cross Validation (Grid Search CV)** and **Randomized Search Cross Validation (Randomized Search CV)**.

**Grid Search CV** performs an exhaustive search by evaluating every possible combination of predefined hyperparameter values using cross-validation. Although it requires more computational time, it helps identify the best-performing parameter combination.

On the other hand, **Randomized Search CV** selects random combinations of hyperparameters from predefined ranges instead of testing every possible combination. This approach significantly reduces computation time while still providing highly effective results, making it suitable for larger datasets and complex machine learning models.

The concepts were demonstrated using **Decision Tree** and **Random Forest** classifiers, showing how different hyperparameter combinations influence the model's performance and how cross-validation helps in selecting the most suitable configuration.

---

## Learning Outcome

Today's session helped me understand the importance of hyperparameter tuning in machine learning. I learned the difference between parameters and hyperparameters, explored the working principles of Grid Search CV and Randomized Search CV, and understood how selecting appropriate hyperparameter values can improve model accuracy, reduce overfitting, and enhance the overall generalization capability of machine learning models. I also gained insight into choosing suitable optimization techniques based on the complexity of the dataset and the computational resources available.


---


**Next :** [Day 19 – Project Development & Implementation](Day19.md)

