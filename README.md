# Loan Approval Prediction System

## Overview

The Loan Approval Prediction System is a Machine Learning project that predicts whether a loan application should be approved or rejected based on an applicant's personal and financial information. The project demonstrates the complete machine learning workflow, including data generation, preprocessing, exploratory data analysis (EDA), visualization, model training, evaluation, and prediction.

## Features

* Synthetic dataset generation with 1500+ applicant records
* Data cleaning and preprocessing
* Handling missing values and duplicate records
* Encoding categorical variables
* Feature scaling
* Exploratory Data Analysis (EDA)
* Data visualization using charts and graphs
* Loan approval prediction using Machine Learning
* Interactive console-based prediction system
* Performance evaluation using multiple metrics

## Dataset Attributes

* ApplicantID
* Gender
* Age
* MonthlyIncome
* LoanAmount
* CreditScore
* EmploymentStatus
* ExistingLoans
* LoanTerm
* PropertyArea
* LoanApproved (Target Variable)

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab
* Jupyter Notebook

## Machine Learning Workflow

1. Generate a synthetic loan applicant dataset
2. Perform data preprocessing and cleaning
3. Conduct exploratory data analysis
4. Visualize important patterns and relationships
5. Encode categorical features
6. Scale numerical features
7. Split data into training and testing sets
8. Train classification models
9. Evaluate model performance
10. Predict loan approval status for new applicants

## Visualizations Included

* Loan Approval by Employment Status (Bar Chart)
* Correlation Heatmap of Numerical Features
* Monthly Income vs Loan Amount (Scatter Plot)
* Approved vs Rejected Applications (Pie Chart)
* Feature Importance Analysis

## Model Evaluation Metrics

* Accuracy Score
* Precision Score
* Recall Score
* F1 Score
* Confusion Matrix
* Classification Report

## Project Structure

Loan-Approval-Prediction-System/

├── Loan_Approval_Prediction.ipynb

├── loan_prediction.py

├── loan_dataset.csv

└── README.md

## How to Run

1. Clone the repository.
2. Install required libraries.
3. Open the Jupyter Notebook or Python script.
4. Run all cells sequentially.
5. Train the model and evaluate performance.
6. Use the interactive prediction system to test new loan applications.

## Sample Prediction Output

Input:

* Age: 30
* Monthly Income: 70000
* Loan Amount: 500000
* Credit Score: 750
* Employment Status: Employed

Output:

* Loan Approved

* ## Live Demo

Try the deployed Streamlit application here:

**🔗 Live Demo:** https://loanapprovalapp-vgit9bwihgvawa8kckvupf.streamlit.app/

The web application allows users to enter applicant details such as age, income, loan amount, credit score, employment status, existing loans, loan term, and property area to receive an instant loan approval prediction.


## Future Enhancements

* Web-based interface using Flask or Streamlit
* Real-time prediction system
* Integration with real-world banking datasets
* Hyperparameter tuning for improved performance
* Deployment on cloud platforms

## Author

Developed as part of a Machine Learning project to demonstrate loan approval prediction using classification algorithms.
