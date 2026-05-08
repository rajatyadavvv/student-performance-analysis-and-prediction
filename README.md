# Student Performance Analysis and Prediction

## Overview

This project analyzes a real world student performance dataset to identify factors that influence academic scores and evaluate the impact of test preparation courses on student performance. The project also includes statistical hypothesis testing and a machine learning regression model for score prediction.

## Dataset

The dataset contains records of **1,000 students** with demographic, socio economic, and academic information.

### Features

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch Type
* Test Preparation Course
* Math Score
* Reading Score
* Writing Score

A new feature, `avg_score`, was created to represent overall academic performance.

## Objectives

* Analyze patterns affecting student academic performance
* Study the impact of test preparation courses
* Perform statistical hypothesis testing
* Build a regression model to predict average scores
* Visualize trends and correlations in the dataset

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit learn
* SciPy

## Project Workflow

### 1. Data Cleaning & Preparation

* Checked for missing values
* Removed duplicate entries
* Cleaned categorical columns
* Applied Label Encoding and One Hot Encoding
* Created `avg_score` feature

### 2. Exploratory Data Analysis (EDA)

Generated **9 visualizations** including:

* Histograms
* Boxplots
* Pairplots
* Heatmaps
* Scatter plots

Key analysis included:

* Score distributions
* Correlation analysis
* Demographic comparisons
* Model prediction visualization

### 3. Hypothesis Testing

Performed **Welch’s t-test** to determine whether completing the test preparation course improves student performance.

#### Results

* Completed Prep Mean Score: **72.67**
* No Prep Mean Score: **65.04**
* Mean Difference: **7.63**
* p-value ≈ **0**

### Conclusion

Students who completed the test preparation course scored significantly higher on average.

## Machine Learning Model

### Model Used

* Linear Regression

### Features Used

Demographic and socio economic features only (subject scores excluded).

### Performance Metrics

* **R² Score:** 0.1139
* **MAE:** 10.84
* **RMSE:** 13.78

The model captured general performance trends but had limited predictive accuracy due to missing academic and behavioral factors.

## Key Insights

* Test preparation positively impacts academic scores
* Higher parental education is linked with better student performance
* Students with standard lunch generally performed better
* Math, reading, and writing scores are strongly correlated

## Limitations

The dataset does not include:

* Study hours
* Attendance
* Coaching
* Motivation levels
* Learning environment

These factors may significantly influence academic performance.

## Future Improvements

* Use advanced regression models
* Include additional behavioral and academic variables
* Perform feature selection and hyperparameter tuning
* Deploy the model using Flask or Streamlit

## Author

**Rajat Yadav**
Github : https://github.com/rajatyadavvv
Mini Project – Student Performance Analysis and Prediction
