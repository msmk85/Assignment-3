# Assignment-3
Calorie_Burn_Prediction_&amp;_Workout_Pattern_Clustering_Using_Fitbit_Data

This project uses Fitbit-based fitness data to build a Calorie Burn Prediction model and perform Workout Pattern Clustering to understand user behavior, workout intensity, and health patterns.

📌 Project Overview
The project focuses on:

Predicting Calories Burned using machine learning regression models.

Identifying workout behavior clusters using unsupervised learning.

Understanding fitness patterns based on heart rate, MET values, BMI, workout frequency, and session duration.

📂 Dataset
The dataset contains 14,102 rows and 19 features, including:

Demographics: Age, Gender, Weight, Height

Heart Rate Metrics: Max BPM, Avg BPM, Resting BPM

Workout Details: Duration, Type, Frequency

Body Metrics: BMI, Fat %, Water Intake

Target Variable: Calories Burned

🛠️ Key Steps
Data Cleaning & Preprocessing

Outlier Handling (IQR capping)

Label Encoding for categorical features

Feature Scaling

Regression Model Training (RF, LR, XGBoost, etc.)

K-Means Clustering for workout pattern discovery

Cluster interpretation & visualization

📊 Models Used
Regression: Random Forest, Linear Regression, Ridge, Lasso, KNN, SVR, XGBoost

Clustering: K-Means

Dimensionality Reduction: PCA (optional)

🎯 Outcomes
Accurate calorie burn prediction

Identification of workout intensity groups

Insights into user fitness behavior

Visualizations for heart rate, MET, BMI, and cluster patterns

🚀 Technologies
Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Google Colab
