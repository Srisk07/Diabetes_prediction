# Diabetes_prediction
💉 Diabetes Prediction: Logistic Regression Capstone Project
Project Overview
This project implements a complete Machine Learning pipeline using the Pima Indians Diabetes Dataset to build and evaluate a Logistic Regression model. The goal is to classify whether a female patient of Pima Indian heritage is likely to test positive for diabetes (1) or negative (0) based on diagnostic measurements.

This repository serves as the final submission for the Machine Learning Foundations course capstone project, demonstrating proficiency in data cleaning, preprocessing, model training, and evaluation.

📌 Project Objectives
The project successfully completes the following core ML steps:

Exploratory Data Analysis (EDA): Initial data inspection and identification of data quality issues (specifically, zero values representing missing data).

Data Preprocessing: Handling missing values via Imputation (replacing zeros with the median), defining features (X) and target (y).

Model Preparation: Performing Train-Test Split (70%/30%) and Feature Scaling (StandardScaler).

Model Training: Implementing and training a Logistic Regression classification model.

Model Evaluation: Assessing performance using key classification metrics: Accuracy, Confusion Matrix, and the Classification Report (Precision, Recall, F1-Score).

💾 Dataset
The project uses the diabetes.csv file, which is a version of the Pima Indians Diabetes Dataset.

Feature	Description
Pregnancies	Number of times pregnant
Glucose	Plasma glucose concentration
BloodPressure	Diastolic blood pressure
SkinThickness	Triceps skin fold thickness
Insulin	2-Hour serum insulin
BMI	Body mass index
DiabetesPedigreeFunction	Diabetes family history score
Age	Age in years
Outcome (Target)	1 (Diabetic) or 0 (Not Diabetic)

Export to Sheets
🛠️ Requirements and Installation
To run the Jupyter Notebook or Python script in this repository, you will need the following libraries.

You can install them using pip:

Bash

pip install pandas numpy scikit-learn matplotlib seaborn
Required Libraries
pandas

numpy

matplotlib

seaborn

scikit-learn (sklearn)
