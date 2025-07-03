# Task 7 – Support Vector Machines (SVM)

This project is part of the **AI & ML Internship**. The goal is to build and evaluate Support Vector Machine (SVM) models for binary classification using the Breast Cancer Dataset from Kaggle.

## What I Did

- Loaded the dataset from Kaggle using `pandas.read_csv()`.
- Preprocessed the data by removing unnecessary columns and encoding labels (`M` → 1, `B` → 0).
- Standardized features with `StandardScaler`.
- Trained two SVM models:
  - One with a **linear kernel**.
  - Another with an **RBF kernel** (non-linear).
- Visualized decision boundaries using **PCA** (2D projection).
- Tuned hyperparameters (**C**, **gamma**) using **GridSearchCV**.
- Evaluated models using accuracy, confusion matrix, classification report, and 5-fold cross-validation.

## Dataset

- **Name:** Breast Cancer Dataset  
- **Source:** [Kaggle - yasserh/breast-cancer-dataset](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset)  
