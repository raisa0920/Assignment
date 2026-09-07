# Bank Marketing Prediction Using Logistic Regression

## Introduction

Bank marketing campaigns are used to identify customers who may be interested in subscribing to a term deposit. In this project, Logistic Regression is used to predict whether a customer will subscribe or not.

The model predicts two classes:

* Yes - Customer subscribed
* No - Customer did not subscribe

## Problem Statement

The objective is to develop a Logistic Regression model that can predict whether a customer will subscribe to a term deposit based on their banking and campaign-related information.

## Objectives

The main objectives of this project are:

* To preprocess the bank marketing data.
* To handle categorical and numerical features.
* To apply OneHotEncoder and StandardScaler.
* To train a Logistic Regression model.
* To evaluate the model using different performance metrics.

## Dataset Description

The project uses the Bank Marketing Dataset.

* **Records:** 45,211
* **Attributes:** 17
* **Target:** `y`
* **File:** `bank-full.csv`

The dataset contains information such as age, job, education, balance, loans, contact details, and previous campaign information.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## Data Preprocessing

The following preprocessing steps were performed:

* Checked missing and duplicate values.
* Separated features and target.
* Converted `yes/no` target values into 1/0.
* Encoded categorical features using OneHotEncoder.
* Scaled numerical features using StandardScaler.
* Split the dataset into 80% training and 20% testing.

## Model and Results

Logistic Regression was used for binary classification.

| Metric                |      Score |
| --------------------- | ---------: |
| **Training Accuracy** | **90.20%** |
| **Testing Accuracy**  | **90.13%** |
| **Precision**         | **64.45%** |
| **Recall**            | **34.78%** |
| **F1-Score**          | **45.18%** |
| **ROC-AUC**           | **0.9056** |

The model achieved good overall accuracy, but identifying customers who actually subscribed was more challenging.
