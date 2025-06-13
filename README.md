# 🏁 F1 Podium Prediction using Machine Learning

Predicting podium finishes (Top 3 positions) in Formula 1 races using machine learning techniques applied to historical F1 race data.

## Problem Statement
Given race-specific features like qualifying positions, constructors, and driver performance, can we predict whether a driver will finish on the podium?

## Dataset
- Source: [Kaggle Formula 1 Datasets](https://www.kaggle.com/datasets)
- Features used:
  - Driver and constructor IDs
  - Race and circuit details
  - Grid position
  - Qualifying performance
  - Driver standings before the race

## Methods Used
- Data Cleaning & Feature Engineering
- Exploratory Data Analysis (EDA)
- Machine Learning Models:
  - Logistic Regression
  - Random Forest
  - Support Vector Classifier (SVC)
  - K-Nearest Neighbors (KNN)
  
## Evaluation
- Metrics used: Accuracy, ROC-AUC
- Model Comparison performed to select the best performing classifier

## How to Run
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
