**Previous:** [Day 2 – Python Fundamentals & Project Finalization](Day02.md)

---

#  Day 3 – Data Cleaning, Preprocessing and Dataset Analysis

**Date:** 2 July 2026

---

##  Objective

To understand the importance of data cleaning in Machine Learning, learn various data preprocessing techniques, identify common data quality issues, and implement these techniques using Python and Pandas.

---

##  Session Summary

Today's session focused on **Data Cleaning and Data Preprocessing**, one of the most important phases of the Machine Learning pipeline. The trainer explained how real-world datasets often contain incomplete, inconsistent, or incorrect information, making preprocessing an essential step before building any Machine Learning model.

We first understood the concept of **Data Cleaning** and discussed why it is necessary to improve the quality, consistency, and reliability of data.

The following common data quality issues were covered in detail:

- Missing values
- Duplicate records
- Incorrect data types
- Inconsistent text formatting
- Outliers
- Invalid values
- Extra spaces in text data

Each topic was explained theoretically with practical examples before implementing it in Python.

---

##  Hands-on Practice

After understanding the concepts, I implemented the following preprocessing operations using Python and the Pandas library:

### Dataset Inspection

- Loaded the dataset into Python using Pandas.
- Displayed the first few records using `head()`.
- Examined dataset information using `info()`.
- Generated descriptive statistics using `describe()`.

### Missing Value Analysis

- Identified missing values using `isnull()`.
- Counted missing values in each column using `isnull().sum()`.
- Displayed records containing missing values.
- Learned different techniques to handle missing values:
  - Removing rows using `dropna()`
  - Filling numerical values using Mean
  - Filling numerical values using Median
  - Filling categorical values using Mode
- Verified the dataset after handling missing values.

### Duplicate Record Handling

- Checked duplicate records using `duplicated()`.
- Counted duplicate entries.
- Removed duplicate rows using `drop_duplicates()`.

### Text Data Cleaning

- Standardized text formatting using `str.title()`.
- Removed unwanted spaces using `str.strip()`.
- Converted text values into uppercase using `str.upper()`.

### Outlier Detection

- Visualized outliers using a Boxplot.
- Understood the concept of Interquartile Range (IQR).
- Calculated Q1, Q3, and IQR.
- Identified outliers using lower and upper limits.
- Created a cleaned dataset after removing outliers.

### Exporting the Cleaned Dataset

- Saved the cleaned dataset as a new CSV file for future use.

---

##  Project Progress

After learning each preprocessing technique through the trainer's examples, I applied the same workflow to my own **HealthGuardian-AI** diabetes dataset using Jupyter Notebook.

The following tasks were performed on my project dataset:

- Loaded the diabetes dataset using Pandas.
- Inspected the dataset using `head()`, `info()`, and `describe()`.
- Analyzed missing values using Pandas functions.
- Counted missing values in every feature.
- Visualized missing values using a heatmap.
- Practiced different techniques for handling missing values.
- Understood duplicate record detection and removal.
- Performed text data cleaning operations.
- Implemented outlier detection using Boxplots and the IQR method.
- Saved the cleaned dataset for future Machine Learning tasks.

---

##  Key Takeaway

Today's session helped me understand that data preprocessing is a crucial step before training any Machine Learning model. Techniques such as handling missing values, removing duplicate records, cleaning textual data, and detecting outliers improve the quality of the dataset and contribute to building more accurate and reliable predictive models.

---

##  Reflection

Today's session was highly practical and interactive. Every preprocessing concept was first explained theoretically and then implemented step by step using Python. Applying the same techniques to my own project dataset helped me understand how data preprocessing is performed in real-world Machine Learning projects. This session strengthened my confidence in working with datasets and prepared me for the next stages of the Machine Learning pipeline.

---

---

##  Continue Learning

**Next:** [Day 4 – Exploratory Data Analysis (EDA) & Feature Engineering](Day04.md)
