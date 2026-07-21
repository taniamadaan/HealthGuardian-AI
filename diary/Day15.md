**Previous :** [Day 14 – Decision Tree & Random Forest Classification](Day14.md)

---

# Day 15 – Regression Models & Regularization Techniques

**Date:** 20 July 2026

## Objective

Today's objective was to understand the concept of regression in machine learning and learn how regularization techniques help improve model performance by reducing overfitting. The session also focused on implementing different regression models and comparing their behaviour.

---

## Theory Learned

The session started with the introduction to **Linear Regression**, one of the fundamental supervised machine learning algorithms used for predicting continuous numerical values. The trainer explained how Linear Regression establishes a relationship between input features and the target variable by fitting a best-fit line through the data.

The limitations of Linear Regression were also discussed, particularly its tendency to overfit when the dataset contains many irrelevant or highly correlated features. To overcome this problem, the concept of **Regularization** was introduced.

Two popular regularization techniques were covered:

### Ridge Regression

Ridge Regression applies **L2 Regularization**, which reduces the magnitude of feature coefficients without removing any feature from the model. It helps in reducing overfitting and produces a more stable model while retaining all the available features.

### Lasso Regression

Lasso Regression applies **L1 Regularization**, which not only reduces coefficient values but can also make some coefficients exactly zero. This allows the model to automatically remove less important features, making it simpler and easier to interpret.

The trainer also explained the major differences between Linear Regression, Ridge Regression, and Lasso Regression based on regularization technique, feature selection, model complexity, and suitable use cases.

---

## Practical Implementation

The practical session focused on implementing all three regression models using Python and the Scikit-learn library.

The dataset was loaded, appropriate input features and target variables were selected, and the data was divided into training and testing sets. Separate models were then trained using Linear Regression, Ridge Regression, and Lasso Regression.

After training, the performance of each model was evaluated using suitable evaluation metrics. Predictions were also generated for sample input values to understand how regression models make predictions on unseen data.

Finally, the performance of all three algorithms was compared to observe how regularization affects prediction behaviour and model performance. The trainer also demonstrated how Ridge Regression preserves all features while reducing their influence, whereas Lasso Regression performs feature selection by eliminating less significant features.

---

## Learning Outcome

Today's session provided a clear understanding of regression models and the importance of regularization in machine learning. I learned the working principles of Linear Regression, Ridge Regression, and Lasso Regression, along with their advantages, limitations, and practical applications. I also understood how different regularization techniques help improve model generalization and how the choice of regression model depends on the characteristics of the dataset and the problem being solved.
