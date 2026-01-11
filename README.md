# Marriage Proposal Response Prediction

## Overview
This project applies supervised machine learning techniques to predict the target variable **Response**
using the *Marriage Proposal* dataset from Kaggle.

The goal is to train and evaluate classification models and compare their performance using standard
machine learning metrics.

## Dataset
- Source: Kaggle — Marriage Proposal Dataset  
  https://www.kaggle.com/datasets/anyasorc/marriage-proposal

The dataset is included in this repository in the `data/` folder.

## Objective
- Predict the **Response** variable using supervised learning
- Compare different classification models
- Evaluate performance using confusion matrix and ROC–AUC

## Methods
- Data preprocessing and cleaning
- Encoding categorical variables using `LabelEncoder`
- Model training with:
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM with RBF kernel)
- Hyperparameter tuning with `GridSearchCV`
- Model evaluation with:
  - Confusion Matrix
  - ROC Curve and AUC score

## Tech Stack
- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebook

## How to Run
1. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
