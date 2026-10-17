#Predicting Alzheimers Using Handwriting 

# Alzheimer's Disease Prediction: Hyperparameter Tuning Experiment

This repository contains an experimental machine learning pipeline designed to predict Alzheimer's Disease utilizing the DARWIN dataset.

*Note: This is a temporary README while the project is in active development and will be updated with full evaluation metrics and setup instructions later.*

## Project Overview

The primary focus of this branch is to explore model optimization techniques, specifically applying hyperparameter tuning to improve predictive accuracy.

* **Dataset:** DARWIN (Diagnosis AlzheimeR WIth handwriting drops) dataset, which utilizes handwriting analysis features for early detection.
* **Algorithm:** Random Forest Classifier.
* **Optimization:** **GridSearchCV** was implemented to systematically test multiple combinations of hyperparameters (such as the number of estimators, max depth, and min samples split) to find the most optimal configuration for the Random Forest model.

## Current Files

* `alzheimers_darwin_model.ipynb`: The main Jupyter Notebook containing the data loading, model training, GridSearchCV implementation, and initial accuracy scoring.
* `data.csv` / `DARWIN.zip`: The dataset files used for training and testing.
