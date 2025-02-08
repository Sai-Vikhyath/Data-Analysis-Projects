# Project-1: Exploratory Data Analysis for Data Science and Machine Learning 

## Introduction:
This project focuses on performing Exploratory Data Analysis (EDA) using Python for both regression and classification tasks. The goal is to analyze and preprocess the diabetes and iris datasets, uncover valuable insights through statistical analysis and visualizations, and apply these findings to improve predictive models. Techniques such as handling missing data, feature engineering, and visualization are emphasized to help make informed decisions during the data science process.

## Data Source
- [Diabetes Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html): The diabetes dataset is a regression problem aimed at predicting diabetes progression one year after baseline. It contains several features such as blood pressure, body mass index, and blood sugar levels.
- [Iris Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html): A classification problem that classifies iris flowers into three species based on features like petal and sepal length and width.

## Features
 - Diabetes Dataset:
    age, sex, bmi (Body Mass Index), bp (Blood Pressure), and s1, s2, s3, s4, s5, s6 (representing various blood serum measurements).
    The target variable is the diabetes progression score after one year.
 - Iris Dataset:
    sepal_length, sepal_width, petal_length, petal_width.
    The target variable is the species of the iris flowers (Setosa, Versicolor, Virginica).

## Question to be Answered
 - Diabetes Dataset: How can we predict the progression of diabetes based on a patient's baseline health metrics, and how do the features correlate with the progression score?
 - Iris Dataset: What are the distinguishing features that allow us to classify iris species, and which features have the strongest correlation with species type?

## Summary of Findings
 - Data Preprocessing: Missing values were identified and handled using median imputation. One-hot encoding was applied to categorical variables to prevent models from misinterpreting them as ordinal data.
 - Correlation Insights: For the diabetes dataset, certain features like bmi and bp showed strong correlations with the target variable. In the iris dataset, petal measurements were found to be the most informative features for classification.
 - Visualizations: Boxplots and histograms were used to visualize distributions, and pair plots helped identify relationships between features. The missingno package helped visualize the extent of missing data.
 - Model Enhancement: By utilizing the insights gained from EDA, regression models for diabetes progression and classification models for the iris dataset were improved, leading to better predictive performance.

## Python Libraries:
 - pandas (for data manipulation)
 - NumPy (for numerical operations)
 - Matplotlib & Seaborn (for visualization)
 - MissingNo (for missing data analysis)
 - scikit-learn (for machine learning tasks)
 - fasteda (for fast, automated EDA)

## References
 - Diabetes Dataset: Pima Indians Diabetes Database, available from the UCI Machine Learning Repository.
 - Iris Dataset: Fisher's Iris Dataset, available from the UCI Machine Learning Repository.
 - https://www.geeksforgeeks.org/what-is-regression-analysis/
 - https://en.wikipedia.org/wiki/One-hot
 - https://www.geeksforgeeks.org/ml-linear-regression/
 - https://www.geeksforgeeks.org/rmse-root-mean-square-error-in-matlab/
 - https://www.geeksforgeeks.org/box-plot-and-histogram-exploration-on-iris-data/
 - https://en.wikipedia.org/wiki/Interquartile_range
 - https://en.wikipedia.org/wiki/Shapiro%E2%80%93Wilk_test
 - https://en.wikipedia.org/wiki/Correlation_coefficient#Pearson
