**Previous Day:** [Day 6 - Feature Engineering](Day06.md)

---

#  Day 7 - Principal Component Analysis (PCA)

**Date:** 08 July 2026

---

#  Introduction

Today, I learned **Principal Component Analysis (PCA)**, a dimensionality reduction technique used in Machine Learning. PCA helps reduce the number of features in a dataset while preserving most of the important information (variance). Instead of selecting existing features, PCA creates new features called **Principal Components**, which are combinations of the original features.

---

#  Why Do We Need PCA?

Many real-world datasets contain a large number of features. While more features may seem useful, they often introduce several challenges:

- Increased computational cost
- Higher memory consumption
- Longer model training time
- More complex models
- Presence of redundant or highly correlated features

This problem is known as **High Dimensional Data**.

PCA helps solve this problem by reducing the number of features while retaining most of the useful information.

---

#  Example Explained During Training

During today's session, PCA was explained using a **Student Placement Dataset**.

The dataset contained features such as:

- Age
- Gender
- CGPA
- Attendance
- Study Hours
- Family Income
- Hostel Status
- Internet Usage
- Assignments
- Projects
- Sports Participation
- Programming Score
- Communication Skills
- Backlogs
- Lab Marks
- Seminar Score

The question discussed was:

> **Do we really need every feature to predict whether a student will get placed?**

The answer is **No**.

Many features provide similar information or are highly correlated. Instead of using every feature, PCA combines the important information into a smaller number of Principal Components.

---

#  Relation to My Diabetes Prediction Project

The same concept can be applied to my **Diabetes Prediction Project**.

My dataset contains medical features such as:

- Age
- BMI
- HbA1C
- Fasting Blood Sugar
- Postprandial Blood Sugar
- Heart Rate
- Cholesterol Level
- Waist-Hip Ratio
- Glucose Tolerance Test Result
- Vitamin D Level
- C-Reactive Protein
- Thyroid Condition

Many of these medical features are related to each other. PCA can summarize their information into fewer Principal Components, making the machine learning model faster, more efficient, and easier to train while preserving most of the important information.

---

#  Understanding PCA with a Real-Life Example

Imagine carrying five separate bags while travelling:

-  Laptop Bag
-  Book Bag
-  Clothes Bag
-  Shoe Bag
-  Snack Bag

Carrying five different bags is inconvenient.

Instead, you pack everything into **one large suitcase**.

Nothing important is removed.

Everything is simply organized into one place.

Principal Component Analysis works in the same way. Instead of working with many individual features, it compresses the important information into a smaller number of new features called **Principal Components**.

---

#  Principal Components

The new features created by PCA are called **Principal Components (PCs).**

Examples:

- Principal Component 1 (PC1)
- Principal Component 2 (PC2)

These are **not original features**.

Each Principal Component is a mathematical combination of all the original features.

For example:

**PC1 = 0.6(CGPA) + 0.3(Attendance) + 0.1(Study Hours)**

Similarly, every Principal Component combines information from multiple original features.

---

#  Variance in PCA

Variance represents the amount of information present in the dataset.

PCA identifies the directions where the data varies the most.

- **PC1** captures the maximum variance.
- **PC2** captures the second highest variance.
- **PC3** captures the next highest variance.

The higher the variance captured by a Principal Component, the more useful information it preserves.

---

#  Explained Variance Ratio

After applying PCA, each Principal Component is assigned an **Explained Variance Ratio**, which tells us how much information is preserved by that component.

For example:

| Principal Component | Information Retained |
|---------------------|---------------------:|
| PC1 | 72% |
| PC2 | 18% |

Together,

**PC1 + PC2 = 90%**

This means only two Principal Components preserve approximately **90%** of the original information.

---

#  PCA Workflow

```text
Dataset
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
Feature Scaling
      ↓
Principal Component Analysis (PCA)
      ↓
Reduced Feature Dataset
      ↓
Machine Learning Model
```

Feature Scaling is performed before PCA because features with larger numerical values may dominate the Principal Components.

---

#  PCA Visualization

After dimensionality reduction, the transformed dataset can be visualized using a scatter plot.

- Each point represents one observation.
- Nearby points indicate similar observations.
- Distant points indicate different observations.

This makes high-dimensional data easier to understand visually.

---

#  Applications of PCA

###  Healthcare

Hospitals collect hundreds of medical measurements for patients. PCA helps reduce these variables before training disease prediction models.

###  Face Recognition

High-resolution images contain thousands of pixels. PCA compresses the image while preserving important facial features.

###  Finance

Banks analyze multiple financial indicators. PCA summarizes them into fewer components for credit risk analysis.

###  Recommendation Systems

Streaming platforms and e-commerce websites use PCA to compress user preferences and product characteristics, making recommendations faster.

###  Machine Learning

PCA is widely used before model training to reduce dimensionality, improve efficiency, and sometimes enhance model performance.

---

#  Key Learnings

- Learned the concept of Dimensionality Reduction.
- Understood the problem of High Dimensional Data.
- Learned how PCA creates new features called Principal Components.
- Understood that Principal Components are combinations of original features.
- Learned the importance of Feature Scaling before applying PCA.
- Studied Explained Variance Ratio and information retention.
- Visualized reduced-dimensional data using PCA scatter plots.
- Explored real-world applications of PCA in Healthcare, Finance, Face Recognition, and Recommendation Systems.

---

**Next Day:**[Day 8 - Handling Class Imbalance in Machine Learning](Day08.md)
