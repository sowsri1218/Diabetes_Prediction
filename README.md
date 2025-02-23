# Diabetes Prediction

## Project Overview

This project aims to analyze various factors that influence diabetes, such as age, gender, hypertension, blood glucose levels, smoking history, HbA1c levels, and BMI. Additionally, it focuses on developing machine learning models to predict the likelihood of diabetes in individuals based on these factors. By examining these variables, we can better understand the risk factors and enhance our ability to predict the development of diabetes.


## Table of Contents
- [Objectives](#Objectives)
- [Dataset](#Dataset)
- [Installation_Prerequisities](#Installation_Prerequisities)
- [Usage](#Usage)
- [License](#license)
- [Results](#Results)
- [Insights&Recommendations](#Insights&Recommendations)
- [Conclusion](#Conclusion)

# Objectives

**Exploratory Data Analysis(EDA)**: Perform an initial exploration of the dataset to understand its structure, identify patterns, and gain preliminary insights.

**Identify Null Values and Duplicates**: Identify and remove null values(if any),duplicate entries, clean the data, handle missing values, and prepare the dataset for further analysis.

**Detecting and Managing Outliers and Skewness**: Use statistical methods to detect outliers and manage skewness in the data, ensuring a more accurate analysis and model performance.

**Analyze Factors**: Examine various factors such as age, sex, hypertension, blood glucose levels, smoking history, HbA1c levels, and BMI to understand their impact on diabetes.

**Visualize Data**: Create visualizations to represent the relationships between different factors and diabetes, making it easier to interpret the data.

**Data Modelling**: Develop and train machine learning models to predict diabetes, evaluate their performance, and select the best-performing model.

**Provide Insights**: Offer actionable insights and recommendations based on the analysis to help individuals and healthcare professionals manage and prevent diabetes.

## Dataset

You can download the dataset from the CSV file attached to this project or from Kaggle.

## Installation_Prerequisities

To install and set up the project, you'll need the following Python libraries:

**NumPy**

**Pandas**

**Matplotlib**

**Seaborn**

**Scikit-learn**

**Scipy**

**Plotly**

**XGBoost**


## Usage

1. Clone the repository to your local machine

      git clone https://github.com/sowsri1218/Diabetes_Prediction.git

2.	Install the required libraries by using

      pip install numpy pandas matplotlib seaborn

3.	Run the Jupyter Notebook to analyze the dataset and make predictions.

If you'd like to contribute to this project, please follow these steps:

1.	Fork the repository.

2.	Create a new branch for your feature or bug fix.

3.	Submit a pull request with a detailed description of your changes.

## License

This project is open source and available for anyone to use for personal or educational purposes. As a portfolio project, it is not encumbered by formal licensing restrictions. Feel free to explore, modify, and distribute the code as you see fit.

## Results

The analysis revealed significant correlations between diabetes and factors such as age, BMI, hypertension, HbA1c, and blood glucose levels.

Applied machine learning models like logistic regression, Random forest classifier, XGBoost and linear Regression. The machine learning (XGBoost) data model achieved an accuracy of 0.97, indicating that 97% of the predictions were correct.

Precision was 0.97, meaning that when the model predicted diabetes, it was correct 86% of the time.

Recall was 0.70, suggesting that the model correctly identified 70% of the actual diabetic cases.

The linear Regression model indicates 96% of the variability in HBA1c levels.


## Insights and Recommendations

Based on the analysis of various factors influencing diabetes, here are some actionable insights and recommendations:

**Maintain a Healthy Weight**: High BMI is significantly correlated with diabetes. Maintaining a healthy weight through a balanced diet and regular exercise can reduce the risk of diabetes.

**Monitor Blood Glucose Levels**: Regular monitoring of blood glucose levels can help in early detection and management of diabetes. Individuals with high blood glucose levels should consult healthcare professionals for appropriate interventions.

**Manage Hypertension**: Hypertension is a significant factor in diabetes. Managing blood pressure through lifestyle changes and medication can help in preventing diabetes.

**Regular Health Check-ups**: Regular health check-ups, including HbA1c tests, can help in early detection and management of diabetes. 

**Healthy Lifestyle Choices**: As individuals age, they should focus on maintaining a healthy diet, managing their BMI, and engaging in regular physical activity to reduce the risk of diabetes.


## Conclusion 

The developed machine learning model provides a data-driven approach to diabetes prediction and risk of developing elevated HBA1c levels by using strong predictors. This method enables early diagnosis and the implementation of preventive measures, which are crucial in managing and reducing the risk of diabetes-related complications.

By analyzing various factors such as age, gender, hypertension, blood glucose levels, smoking history, HbA1c levels, and BMI, this model offers valuable insights that can help individuals and healthcare professionals make informed decisions. The high accuracy and precision of the model further underscore its potential as a reliable tool in the fight against diabetes.
