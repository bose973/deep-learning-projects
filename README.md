# 🧠 Deep Learning with Keras and TensorFlow
## 📊 Home Loan Data Analysis

## 📝 Problem Statement
For a safe and secure lending experience, it is crucial to analyze past loan data.
This project aims to build a deep learning model that predicts the likelihood of default for future loans using historical data.
The dataset is highly imbalanced and contains numerous features, making this problem both challenging and realistic.

## 🎯 Objective
Create a model that predicts whether or not an applicant will be able to repay a loan using historical data.
Domain: Finance
Focus: Risk assessment and default prediction

## 🔍 Analysis to be Done
Perform data preprocessing
Build a deep learning prediction model using Keras and TensorFlow

## ⚙️ Steps to Perform
1. Load the Dataset
Import the dataset provided.
Inspect its structure and dimensions.

2. Handle Missing Values
Check for null values.
Apply imputation or removal strategies as needed.

3. Analyze Target Column
Print the percentage of default vs. non-default in the TARGET column.
Identify imbalance in the dataset.

4. Balance the Dataset
Apply techniques such as:
Oversampling (SMOTE)
Undersampling
Class weights in the model

5. Visualize Data Distribution
Plot balanced vs. imbalanced data.
Use bar plots or pie charts for class distribution.

6. Encode Categorical Columns
Apply Label Encoding or One-Hot Encoding for categorical features.
Ensure compatibility with TensorFlow/Keras models.

7. Build and Train Deep Learning Model
Define a neural network using Keras Sequential API.
Compile with appropriate loss function (e.g., binary_crossentropy) and optimizer (e.g., adam).
Train and validate the model.

8. Evaluate Metrics
Sensitivity (Recall): Measure the ability to correctly identify defaults.
ROC-AUC: Calculate the area under the Receiver Operating Characteristic curve for overall performance.