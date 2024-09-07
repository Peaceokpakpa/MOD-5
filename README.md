Breast Cancer Data PCA and Logistic Regression
Project Overview
This project is designed to demonstrate the use of Principal Component Analysis (PCA) to reduce the dimensionality of the Breast Cancer dataset from sklearn.datasets. The PCA transformation is used to identify essential variables for securing donor funding at Anderson Cancer Center by reducing the dataset to 2 principal components. Additionally, a Logistic Regression model is implemented as an optional step to predict the target variable (benign or malignant tumor).

Structure
The repository contains the following files:

pca_cancer_analysis.py: Main Python script for PCA and Logistic Regression implementation.
README.md: This file, with instructions for running the code and an overview of the project.
Getting Started
Prerequisites
Make sure you have the following installed on your system:

Python 3.8 or higher: You can download it from the official Python website here.
Pip: Python package installer, which is installed along with Python.
Required Libraries
To install the necessary libraries, run the following command:
numpy
pandas
scikit-learn
matplotlib
seaborn
Dataset
The Breast Cancer dataset used in this project is provided directly by sklearn.datasets. No need to download or prepare any external data.
Running the Code
Clone or download the repository
Run the main script 
The script will:

Load the breast cancer dataset.
Standardize the data.
Apply PCA to reduce the data to 2 principal components.
Optionally, implement logistic regression for prediction.
You will see output related to PCA and Logistic Regression, including the model’s accuracy.
Results
The following outcomes will be produced by the script:

PCA Visualization: A scatter plot visualizing the dataset in 2D using the PCA components.
Logistic Regression (optional): Accuracy score of the logistic regression model, if implemented.
