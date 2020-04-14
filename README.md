# Expense_Prediction
## E2E Model Implementation using python
1)
### Project Planning - Get Expenses based on the Income and Age
2)
### Data Collection - manually created in excel (csv format) - used library(import pandas as pd)
3)
### Data Cleaning - checked for na values, replaced na with median, checked for outliers, replaced the outlier with IQR(Inter Quartile Range) process - used library (import numpy as np)
4)
### Exploratory Data Analysis (EDA) - box plot - library(from matplotlib import pyplot as plt), correlation matrix for checking strength of two variables - used library(import seaborn as sns)
5)
### Model Building - feature engineering (technique used normalization/scaling data - MinMaxScaler()) - used library(from sklearn.preprocessing import MinMaxScaler(()), converted data to to DataFrame from the min and max values (0's and 1's) array of the scaled data, divided data into test and train (from sklearn.model_selection import train_test_split,from sklearn.linear_model import Linear Regression, also for the accuracy of the model from sklearn import metrics)
6)
### Model Deployment - used web framework flask - used library(import pickle)

#### RUNNING A FLASK APPLICATION
1st step :  Run the app.py which is existed in the Model Deployment Folder from the Anaconda Navigator Prompt
2nd step :  We will find a localserver running on some port address ex-https://127.0.0.1:5000/
3rd step :  Copy the url and run in browser.
4th step :  THATS'S IT!!!!!!!!!
