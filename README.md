# Cancer Prediction Machine Learning Model

A machine learning model that predicts whether a cancer is malignant or benign based on 30 attributes of cancer cells such as radius, area, and texture.

## Overview

This project was completed as part of my Computer Science capstone. The motivation for this project was to explore how machine learning could be applied in a healthcare setting and potentially assist in early diagnosis and treatment planning.

## Data

The data for this project was sourced from a dataset available on Kaggle. The dataset contains measurements of cancer cells, such as area, radius, and texture, that are used to train the machine learning model.

## Methods

The project involves multiple steps including exploratory data analysis, model selection, hyperparameter tuning, and model evaluation.

### Data Cleaning and Exploration

I performed initial data cleaning to handle missing or irrelevant data. The clean data was then explored using bar graphs and histograms to gain insights into the distributions of different attributes. I also created a heatmap to see the correlation between all the features.

### Model Selection

Six different machine learning models were initially tested to identify which performed the best on the dataset. These models included K-Nearest Neighbors, Logistic Regression, Random Forest, Linear SVC, Gradient Boosting, and Decision Tree.

### Hyperparameter Tuning

The best performing models were then fine-tuned using `RandomizedSearchCV` to identify optimal hyperparameters. This was followed by a more precise tuning with `GridSearchCV` on the top-performing models.

### Model Evaluation

The models were evaluated based on various metrics, including accuracy, precision, recall, f1-score, ROC curve, and confusion matrix. The final model (logistic regression) achieved an impressive accuracy of 98%.

## Results

The project resulted in a logistic regression model that achieved high accuracy in predicting whether a given cancer was malignant or benign based on the attributes of cancer cells. This demonstrates the potential for machine learning models to aid in diagnosis and treatment planning in healthcare.

## Contact

For any queries, feel free to reach out at dakotadurfee23@gmail.com
