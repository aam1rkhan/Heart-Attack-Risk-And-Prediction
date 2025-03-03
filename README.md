# Heart Attack Risk Analysis

Project Overview

This project analyzes heart attack risk based on various medical and lifestyle factors using a dataset downloaded from Kaggle. The analysis includes Exploratory Data Analysis (EDA), data visualization, model training, and dashboard reporting in Power BI.

# Dataset Information

The dataset consists of the following columns:

Patient_ID, State_Name, Age, Gender, Diabetes, Hypertension, Obesity, Smoking, Alcohol_Consumption, Physical_Activity, Diet_Score, Cholesterol_Level, Triglyceride_Level, LDL_Level, HDL_Level, Systolic_BP, Diastolic_BP, Air_Pollution_Exposure, Family_History, Stress_Level, Healthcare_Access, Heart_Attack_History, Emergency_Response_Time, Annual_Income, Health_Insurance, Heart_Attack_Risk.

## Exploratory Data Analysis (EDA) and Visualizations

The following visualizations were created:

Histogram: Age distribution

Boxplot: Identifying age outliers

Pie Chart: Gender distribution

Bar Chart: Number of patients in each state

Bar Chart: Smoking & alcohol consumption distribution

Boxplot: Diet score distribution across heart attack risk levels

Heatmap: Correlation between medical risk factors

Scatter Plot: Healthcare access vs. heart attack risk



## Model Training

The following machine learning models were trained to predict heart attack risk:

Logistic Regression

K-Nearest Neighbors (KNN)

Naive Bayes

Random Forest Classifier


# Model Performance

# Model                       Accuracy

Logistic Regression           70.55%

KNN                           63.25%

Naive Bayes                   70.55%

Random Forest                 70.50%



# Power BI Dashboard

A Power BI dashboard was created to visualize key insights from the dataset, including:

Patient distribution across states

Risk factor trends

Correlation between different medical and lifestyle attributes

Model prediction insights


# Conclusion

This project provides a comprehensive analysis of heart attack risk using machine learning models and visualizations. The findings can help healthcare professionals and policymakers identify high-risk patients and implement preventive measures.

# Future Enhancements

Feature Engineering: Introduce new derived features for better model performance.

Hyperparameter Tuning: Improve model accuracy through parameter optimization.

Larger Dataset: Expand the dataset for better generalization.

Real-time Prediction Dashboard: Deploy a live prediction system for better usability.

