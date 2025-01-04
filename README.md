# Breast-Cancer-Exploratory-Data-Analysis-EDA-
This repository contains the code for performing exploratory data analysis (EDA) on the Breast Cancer dataset. The dataset contains features related to cell properties from biopsies, such as texture, perimeter, area, and smoothness, used to classify breast cancer tumors as either malignant or benign.

## Project Overview
In this project, we will:
  Load the dataset.
  Perform data cleaning and preprocessing.
  Explore the data by visualizing distributions and correlations.
  Implement basic EDA techniques such as distribution analysis and correlation heatmap.

## Dataset Information
The dataset used in this project is from the Kaggle Breast Cancer Dataset and contains information on various attributes of cell nuclei present in breast cancer biopsies. The primary objective is to predict whether the tumor is malignant or benign based on the cell features.

Diagnosis: The target variable, encoded as:
M for Malignant (1)
B for Benign (0)
Features: The dataset includes 30 feature columns like radius_mean, texture_mean, perimeter_mean, etc.

## Steps Performed:
Data Preprocessing:
Check for Null Values.
Drop the id column.
Encode the diagnosis column as binary values (M -> 1, B -> 0).

### Exploratory Data Analysis (EDA):
Distribution of Target Variable: Visualization of the distribution of malignant and benign tumors.
Histograms of Features: Distribution of numerical features, such as radius, area, and smoothness.
Correlation Heatmap: Identify relationships between the features using a correlation matrix.

## Requirements
Python 3.x
Libraries:
pandas
matplotlib
seaborn
kagglehub
