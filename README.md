# MLProject1
❤️ Heart Disease Prediction Using Machine Learning

This project uses Machine Learning (Logistic Regression) to predict whether a person is likely to have heart disease based on clinical and physiological data. Early prediction plays a crucial role in preventing severe heart conditions, and this model aims to support healthcare professionals and researchers with a reliable tool for risk assessment.

 Project Overview

Heart disease remains one of the leading causes of death worldwide. This project builds a predictive model using a well-structured dataset containing attributes such as:

Age

Sex

Chest pain type

Resting blood pressure

Cholesterol level

Fasting blood sugar

Resting ECG results

Maximum heart rate achieved

Exercise-induced angina

ST depression

Number of major vessels

Thalassemia

Using these features, the machine learning model predicts:

0 → No Heart Disease

1 → Heart Disease Present

Objectives

Preprocess and clean the dataset

Perform Exploratory Data Analysis (EDA)

Build and train a Logistic Regression model

Evaluate accuracy on training and test sets

Build a predictive system to test new patient data

Provide insights that support clinical decision-making

Technologies Used

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

 Project Structure
Heart-Disease-Prediction/
│
├── dataset/
│   └── heart.csv
│
├── notebooks/
│   └── heartdiseaseproject1.ipynb
│
├── README.md
│
└── requirements.txt

 Exploratory Data Analysis (EDA)

The project includes:

Data shape & summary statistics

Correlation heatmap

Distribution of key health features

Relationship between target variable and features

These visualizations help understand patterns and feature importance.

Model Used
Logistic Regression

Suitable for binary classification

Fast and efficient

Offers clear feature influence (coefficients)

Model steps include:

Train-Test Split

Standardization (scaling)

Model Training

Evaluation

Model Performance

Example metrics (your output may vary):

Training Accuracy: ~0.85

Testing Accuracy: ~0.80

These results indicate a reliable model with generalization capability.
