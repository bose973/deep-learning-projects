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

## 🚀 How to Run
1. Clone the repository:
   git clone https://github.com/bose973/deep-learning-projects.git
2. Make sure python 3.12.1 is installed in your system
3. Navigate to the project folder:
   cd deep-learning-projects\home_loan_analysis\
4. Create the virtual env - run these two commands step by step:
   1)python -m venv DL_ENV
   2).\DL_ENV\Scripts\Activate.ps1
   3)pip install -r ./Data-Science-EDA/marketing-analysis/required_packages.txt
5. Update the python interpretor of your IDE to DL_ENV
6. Unzip the dataset Home_loan_data.zip
7. Run the project-code file using jupyter editor in your IDE:
   model_analysis.ipynb