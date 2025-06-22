# uwl_phenotyping

22 June 2025

This repository contains a jupyter notebook with the code for training and validating phenotyping algorithms for use in Australian primary care data.

The focus is on the phenotype (symptom) of Unintended Weight Loss (UWL) but the methodology can be applied more broadly.

The notebook `phenotyping_220625.ipynb` contains the code for the phenotyping and is structured as follows:

1) Load the relevant datasets
2) Combine data sources
3) Define functions for processing data, evaluating models and producing bootstrap estimates
4) Apply data transformations
5) Create training and test datasets
6) Train and test the five different ML models, as well as the rule-based model

The ML models compared are:

- Naive Bayes
- Decision Trees
- Random Forests
- Logistic Regression
- ClinicalBERT

## Data access
Data can be made available subject to approval from the data custodians