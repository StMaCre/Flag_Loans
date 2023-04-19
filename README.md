# Flagging High-Risk Loan Customers

This project aims to predict high-risk customers, who are likely to default or cause financial loss to a lending institution. The goal is to improve the recall of the model to better identify potential red-flagged customers while maintaining an acceptable precision. I used various machine learning models and techniques to address the class imbalance and improve the overall prediction performance.

## Table of Contents
- Installation
- Data Preprocessing
- Modeling
- Evaluation
- Addressing Imbalanced Classes

## Installation
Clone this repository, and make sure you have the following Python libraries installed:
numpy
pandas
scikit-learn
xgboost
imbalanced-learn
yellowbrick

You can install the necessary packages using the requirements.txt file. 

## Data Preprocessing
The dataset contains customer information, loan details, and the target variable, which indicates whether a customer is red-flagged (1) or not (0). I perform the following preprocessing steps:
- Handling missing values
- Converting categorical variables into numerical format
- Scaling the numerical features
## Modeling
I train and evaluate the following machine learning models:
- Logistic Regression
- Random Forest
- XGBoost

Model hyperparameters are optimized using Grid Search.

## Evaluation
I use Yellowbrick to visualize the performance of our models with confusion matrices, precision-recall curves, and other relevant metrics.

## Addressing Imbalanced Classes
To improve the recall of the minority class, I used SMOTE to oversample the minority class. 

After addressing the class imbalance and optimizing the models, I present the improved recall scores and overall performance of our model. 
