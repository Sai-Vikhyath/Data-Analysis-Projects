# [Project_2: Exploratory Data Analysis with Banking Client Data](https://github.com/Sai-Vikhyath/Exploratory-Data-Analysis-Projects/blob/main/Exploratory%20Data%20Analysis%20of%20Banking%20Client%20Data.ipynb)

## Intro
- This project focuses on performing Exploratory Data Analysis (EDA) on a banking marketing dataset to uncover valuable insights that can aid in designing more effective marketing campaigns.
- The dataset pertains to a direct marketing campaign conducted by a Portuguese bank, where the goal is to predict whether a client will subscribe to a term deposit. Through the use of Pandas, pivot tables, and visualizations, we analyze various client features and their relationship with the target variable (successful subscription).

## Data Source
The data used in this project is a subset of the Bank Marketing Data Set available from the UCI Machine Learning Repository:
- [Bank Marketing Dataset](https://archive.ics.uci.edu/ml/citation_policy.html).
- The dataset was sourced from a real-world telemarketing campaign conducted by a Portuguese bank, as described in the study by Moro et al., 2014. The task is to predict if a client will subscribe to a term deposit based on attributes like age, job, marital status, education, and previous campaign information.

## Features
The dataset includes various features related to clients and their interactions with the bank’s marketing campaigns:
### Client Features:
age, job, marital, education, contact, month, day_of_week, previous (number of contacts before), poutcome (outcome of the previous marketing campaign).
### Campaign Features:
campaign (number of contacts during the current campaign), duration (duration of the last contact in seconds), pdays (number of days since the client was last contacted), and previous (number of contacts before this campaign).
### Target Variable:
y (whether the client subscribed to a term deposit or not).

## Questions to be Answered
1. What is the share of clients attracted to the term deposit?
2. What are the mean values of numerical features (age, duration, calls) among the attracted clients?
3. What is the average call duration for the attracted clients?
4. What is the average age among the attracted and unmarried clients?
5. What is the relationship between client employment types and their average age and call duration?

## Summary of Findings
- Client Response Rate: Approximately 11.3% of clients in the dataset subscribed to a term deposit, which is relatively low for a marketing campaign.
- Client Demographics: The average age of attracted clients was found to be around 40 years, with 2.05 calls required on average to convert them.
- Call Duration: The average call duration for clients who subscribed to the term deposit was approximately 553 seconds (around 9 minutes).
- Age and Marital Status: The average age of unmarried, attracted clients was found to be around 31 years.
- Client Employment Analysis: Pivot tables revealed that clients in different job categories exhibited varying ages and call durations, with some professions requiring longer calls for conversion.

## References
- Moro, S., Cortez, P., & Rita, P. (2014). A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31.
- UCI Machine Learning Repository: Bank Marketing Dataset
- Pandas Documentation: https://pandas.pydata.org/pandas-docs/stable/
- Matplotlib & Seaborn Documentation: https://matplotlib.org/ and https://seaborn.pydata.org/
- https://en.wikipedia.org/wiki/geometric_distribution


