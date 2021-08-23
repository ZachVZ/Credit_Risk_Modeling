# Credit_Risk_Modeling

This notebook uses supervised learning to train and evaluate a credit risk model with imbalanced classes to identify the risky loans.

Below are the actions that will be performed in this notebook.
1. Split the Data into Training and Testing Sets
2. Create a Logistic Regression Model with the Original Data
3. Predict a Logistic Regression Model with Resampled Training Data


## Technologies Require
* This project leverages python version 3.8.5
* sklearn Library
* scikit-learn 
* Project will be accomplished in JupyterLab

## Installation Guide and Running Jupyter Notebook
Installing Jupyter notebook
* On the terminal (Git Bash) under the conda dev environment, type the code below:

pip install jupyterlab

* To open the Jupyter notebook
Open a new Git Bash and type the below command into your conda dev environment:

jupyter lab

* then hit the ENTER key to run


## Required Imports
* pandas - data manipulation and analysis
* numpy - fundamental package for scientific computing in Python
* pathlib - imports csv files 
* sklearn.metrics -  implements several loss, score, and utility functions to measure classification performance
* filterwarnings - adding rules to the filter, ignoring error msgs

## Install Guide
* import pandas as pd
* import numpy as np
* from pathlib import Path
* from sklearn.metrics import balanced_accuracy_score
* from sklearn.metrics import confusion_matrix
* from imblearn.metrics import classification_report_imbalanced
* import warnings
* warnings.filterwarnings('ignore')

## Usage
To use the notebook:
1. Clone the repo
2. Run jupter lab git bash
3. Open file credit_risk_resampling.pynb

### Contributors
Zach Zwiener

### Contact
Email - zachzwiener3@gmail.com

### License
MIT