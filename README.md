# New Hire Decision Prediction using Random Forests
This repository contains a Jupyter Notebook file that demonstrates how to predict new hire decisions using ensemble learning, specifically the random forests algorithm. The analysis is performed using a CSV file that contains data on previous new hire decisions, and the sklearn library is used for the machine learning analysis.

# Getting Started
To run the notebook, you will need to install the following libraries:

pandas
numpy
matplotlib
sklearn

# Data
The csv file contains information about previous new hire decisions, including the candidates' education level, years of experience, and interview scores, as well as whether they were ultimately hired or not. The goal of the analysis is to predict whether a new candidate will be hired or not based on their qualifications and interview scores.

# Approach
The analysis is performed using the following steps:

Load the data from the csv file and perform some exploratory data analysis (EDA) to understand the data.
Prepare the data for analysis by encoding categorical variables and splitting the data into training and test sets.
Train a random forests model on the training data and evaluate its performance on the test data.
Tune the hyperparameters of the random forests model using grid search and cross-validation.
Use the tuned random forests model to make predictions on new data.

# Results
The analysis shows that it is possible to predict new hire decisions with reasonable accuracy using random forests. The tuned random forests model has an accuracy of 0.84 on the test data, indicating that it can correctly predict new hire decisions for 84% of the candidates.

# Conclusion
This notebook demonstrates how to predict new hire decisions using random forests algorithm in Python and sklearn library. It shows that it is possible to predict new hire decisions with reasonable accuracy using machine learning. However, further improvements can be made by using other ensemble learning techniques or including additional variables in the analysis.
