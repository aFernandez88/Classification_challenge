# Classification_challenge

Overview
This project aims to develop an effective email filtering system for an Internet Service Provider by leveraging supervised machine learning techniques. The goal is to accurately classify emails as spam or non-spam using a provided dataset containing information about emails classified as either spam or not spam. We will create and evaluate two different classification models to determine which one is more effective at filtering spam emails.


Dependencies
The project will require the following dependencies:
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score
from sklearn.preprocessing import StandardScaler
from sklearn.linear_model import LogisticRegression
from sklearn.ensemble import RandomForestClassifier


Approach
Two classification models will be created and evaluated:
Logistic Regression Model
Random Forest Model


Methodology
The project will follow these steps:
Data Preprocessing: Check the balance of the labels variable using the '.value_counts' function and Scale the data. 
Feature Engineering: Set the target as 'y' and the remainder features as 'x' and created a dataframe dropping that target 'y' column.
Model Training: Split the dataset into training and testing sets, and train both the logistic regression and random forest models on the training data.
Model Evaluation: Evaluate the performance of both models on the testing data using the accuracy metric.
Model Selection: Based on the evaluation results, select the model that performs better at detecting spam emails. In this case both models had the same score. 


Resources:
Past activities,
Tutor,
AskBCS,
Perplexity-to help with the format of the readme file. 
