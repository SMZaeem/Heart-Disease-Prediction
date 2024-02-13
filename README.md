# Innovative Health Analysis: Revolutionizing Health Insights with Machine Learning

### by S.M. Zaeem

## A) Project Objectives

- Thorough analysis of Health Data Set to extract meaningful insights for improved inference.
- Development of a predictive model to assess the likelihood of heart disease based on diverse physiological parameters.
- Creation of a robust and accurate model ensuring high precision for confident predictions.
- Deployment of accessible prediction tools for users, enabling them to monitor their health status conveniently.

## B) Data Acquisition and Exploration

## 1. Data Collection

Utilized the Heart Disease UCI dataset sourced from Kaggle, comprising 76 attributes with a focus on 14 crucial features for ML research. The objective is to identify the presence of heart disease in patients.

![Data Preview](https://user-images.githubusercontent.com/30470730/72439674-5f9a6a00-37cd-11ea-9366-6ef953b6879e.png)

## 2. Exploratory Data Analysis

The dataset, while comprehensive, required interpretation due to certain non-obvious column headers. Key attributes include age, gender, chest pain type, blood pressure, cholesterol levels, and maximum heart rate.

## 3. Data Visualization

Various graphical representations were employed to analyze relationships between different features.

![Graph 1](https://user-images.githubusercontent.com/30470730/72439765-822c8300-37cd-11ea-8b3e-e0e53fedf0c9.png)

![Graph 2](https://user-images.githubusercontent.com/30470730/72439779-89539100-37cd-11ea-80bb-7c721f8e06cb.png)

## 4. Correlation Matrix

A correlation matrix was utilized to assess relationships between features.

![Correlation Matrix](https://user-images.githubusercontent.com/30470730/72439867-bef87a00-37cd-11ea-8613-8144b209d65f.png)

## 5. Model Inputs

The model utilized common physiological features such as age, gender, chest pain type, blood pressure, cholesterol levels, and maximum heart rate for prediction.

## C) Solution Implementation

- Implemented a Linear Regression Model tailored for binary classification.
- Deployed the model on AWS Sagemaker and created an endpoint for predictions.
- Utilized AWS Lambda Function and Amazon Gateway to develop a publicly accessible API for prediction queries.

## D) Performance Evaluation

Performance evaluation included benchmarking against a test dataset, comparing predicted labels with actual labels to ascertain false positives and false negatives.

## E) Evaluation Metrics

Evaluation metrics employed include accuracy, precision, and recall to gauge model performance effectively.

## F) Project Architecture

![Project Architecture](https://user-images.githubusercontent.com/30470730/72440035-1a2a6c80-37ce-11ea-8f3e-60817563e088.png)

The architecture illustrates the interaction between the trained model deployed on SageMaker, the Android App, a Lambda function for data exchange, and an API Gateway for communication between the app and Lambda function.
