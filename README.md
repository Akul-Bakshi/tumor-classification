# Tumor Malignant/Benign Prediction

Simple machine learning project using logistic regression to predict if a tumor is malignant or benign.

## Dataset
Breast Cancer Wisconsin dataset from Kaggle

## Features Used
- Radius (tumor size)
- Texture (tumor surface roughness)

## Libraries Used
- pandas
- numpy
- matplotlib
- scikit-learn

## What It Does
- Loads tumor data from CSV file
- Trains AI model to classify tumors
- Shows accuracy of predictions
- Visualizes tumor types (blue = benign, red = malignant)
- Tests model on new tumor examples

## Results
- Model accuracy: ~91%
- Successfully distinguishes between malignant and benign tumors
- Can predict new tumor classifications

## How to Run
1. Download the breast cancer dataset from Kaggle
2. Save as `breast_cancer.csv` in same folder
3. Run: `python tumor_prediction.py`

## Files
- `tumor_prediction.py` - Main code
- `breast_cancer.csv` - Dataset (download from Kaggle)
- `README.md` - This file

## About
This project demonstrates basic machine learning classification using logistic regression. Built as part of learning machine learning fundamentals.
