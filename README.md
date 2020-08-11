#### Pre-Modeling: Data Preprocessing and Feature Exploration in Python


This repo contains several files:

- Notebook:
  - adult.ipynb
- Data:
  - adult.csvx
- Images:
  - interactions.jpg
  - outliers.jpg
  - pca.jpg
  - tukeyiqr.jpg
Pre-Modeling: Data Preprocessing and Feature Exploration in Python

### Goal

- Goal:
Pre-modeling/modeling 80%/20% of work
Show the importance of data preprocessing, feature exploration, and feature engineering on model performace
Go over a few effective pre-modeling steps
This is only a small subset of pre-modeling 

#### Format:
#### Tutorial style 
Walk through concepts and code (and point out libraries)
Use an edited version of the 'adult' dataset (to predict income) with the objective of building a binary classification model
Python libraries:
Numpy
Pandas
Sci-kit learn
Matplotlib
Almost entire workflow is covered by these four libraries
Source of 'adult' dataset: https://archive.ics.uci.edu/ml/datasets/Adult

#### Agenda

Modeling Overview 
Introduce the Data
Basic Data Cleaning
Dealing with data types
Handling missing data
More Data Exploration
Outlier detection
Plotting distributions
Feature Engineering
Interactions between features
Dimensionality reduction using PCA
Feature Selection and Model Building

Part 1: Modeling Overview

Review of predictive modeling

#### Definition
#### Statistical technique to predict unknown outcomes

Today's example
Binary classification model - determine the probability that an observation belongs to one of two groups
Examples:
Whether a person votes for one of two political candidates
Whether a credit card transaction is fraud
Whether or not a person will be diagnosed with a given disease in the next year
Data terminology
Inputs - Independent variables (also called features)
Predictors
Outputs - Dependent variable (also called the outcome)
The target variable for prediction
Models explain the effect that features have on the outcome
Assessing model performance
Randomly split observations into train/test sets
Build model on train set and assess performance on test set
AUC of ROC is common performance metric
True positive vs. false positive rates
Types of models for binary classification

### Logistic regression
### Random Forest
### Gradient Boosted Trees
### Support Vector Machines
Many, many more

### Part 2: Introduce the Data
Task: Given attributes about a person, predict whether their income is <=50K or >50K