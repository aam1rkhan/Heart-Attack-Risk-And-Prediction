<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Heart Attack Risk Analysis</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; margin: 20px; padding: 20px; background-color: #f4f4f4; }
        h1, h2 { color: #333; }
        pre { background: #e8e8e8; padding: 10px; border-radius: 5px; overflow-x: auto; }
    </style>
</head>
<body>
    <h1>Heart Attack Risk Analysis</h1>
    <h2>Project Overview</h2>
    <p>This project analyzes heart attack risk based on various medical and lifestyle factors using a dataset downloaded from Kaggle. The analysis includes Exploratory Data Analysis (EDA), data visualization, model training, and dashboard reporting in Power BI.</p>
    
    <h2>Dataset Information</h2>
    <p>The dataset consists of the following columns:</p>
    <pre>
Patient_ID, State_Name, Age, Gender, Diabetes, Hypertension, Obesity, Smoking, Alcohol_Consumption,
Physical_Activity, Diet_Score, Cholesterol_Level, Triglyceride_Level, LDL_Level, HDL_Level,
Systolic_BP, Diastolic_BP, Air_Pollution_Exposure, Family_History, Stress_Level,
Healthcare_Access, Heart_Attack_History, Emergency_Response_Time, Annual_Income,
Health_Insurance, Heart_Attack_Risk
    </pre>
    
    <h2>Exploratory Data Analysis (EDA) and Visualizations</h2>
    <ul>
        <li>Histogram: Age distribution</li>
        <li>Boxplot: Identifying age outliers</li>
        <li>Pie Chart: Gender distribution</li>
        <li>Bar Chart: Number of patients in each state</li>
        <li>Bar Chart: Smoking & alcohol consumption distribution</li>
        <li>Boxplot: Diet score distribution across heart attack risk levels</li>
        <li>Heatmap: Correlation between medical risk factors</li>
        <li>Scatter Plot: Healthcare access vs. heart attack risk</li>
    </ul>
    
    <h2>Model Training</h2>
    <p>To predict heart attack risk, the following machine learning models were trained:</p>
    <ul>
        <li>Logistic Regression</li>
        <li>K-Nearest Neighbors (KNN)</li>
        <li>Naive Bayes</li>
        <li>Random Forest Classifier</li>
    </ul>
    
    <h2>Model Performance</h2>
    <table border="1" cellpadding="5" cellspacing="0">
        <tr>
            <th>Model</th>
            <th>Accuracy</th>
        </tr>
        <tr>
            <td>Logistic Regression</td>
            <td>70.55%</td>
        </tr>
        <tr>
            <td>KNN</td>
            <td>63.25%</td>
        </tr>
        <tr>
            <td>Naive Bayes</td>
            <td>70.55%</td>
        </tr>
        <tr>
            <td>Random Forest</td>
            <td>70.50%</td>
        </tr>
    </table>
    
    <h2>Power BI Dashboard</h2>
    <p>A Power BI dashboard was created to visualize key insights from the dataset, including:</p>
    <ul>
        <li>Patient distribution across states</li>
        <li>Risk factor trends</li>
        <li>Correlation between different medical and lifestyle attributes</li>
        <li>Model prediction insights</li>
    </ul>
    
    <h2>Conclusion</h2>
    <p>This project provides a comprehensive analysis of heart attack risk using machine learning models and visualizations. The findings can help healthcare professionals and policymakers identify high-risk patients and implement preventive measures.</p>
    
    <h2>Future Enhancements</h2>
    <ul>
        <li>Feature Engineering: Introduce new derived features for better model performance.</li>
        <li>Hyperparameter Tuning: Improve model accuracy through parameter optimization.</li>
        <li>Larger Dataset: Expand the dataset for better generalization.</li>
        <li>Real-time Prediction Dashboard: Deploy a live prediction system for better usability.</li>
    </ul>
</body>
</html>
