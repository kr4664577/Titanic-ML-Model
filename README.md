# 🚢 Titanic Survival Prediction using Scikit-learn

## 📌 Overview

This project builds a machine learning classification model to predict whether a Titanic passenger survived.

The project uses **Logistic Regression** with data preprocessing, missing-value handling, categorical encoding, feature scaling, train/test splitting, and model evaluation.

## 🧠 Workflow

```text
Titanic Dataset
      ↓
Handle Missing Values
      ↓
Remove Unnecessary Columns
      ↓
Encode Categorical Features
      ↓
Standardize Features
      ↓
Train/Test Split
      ↓
Logistic Regression
      ↓
Prediction & Evaluation
```

## 🔧 Preprocessing

- Filled missing `Age` values using the median.
- Filled missing `Embarked` values using the mode.
- Removed `Cabin`, `Name`, `Ticket`, and `PassengerId`.
- Converted categorical variables using one-hot encoding.
- Standardized features using `StandardScaler`.

## 🤖 Model

**Algorithm:** Logistic Regression  
**Dataset:** Titanic training dataset  
**Library:** Scikit-learn

## 📊 Evaluation

The notebook evaluates the model using:

- Accuracy
- Confusion Matrix
- Classification Report

The original repository reports approximately **80% accuracy**. The exact score should be taken from the latest executed notebook output if the model is rerun.

## 🧰 Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab / Jupyter Notebook

## ▶️ How to Run

1. Make sure `train.csv` is in the same directory as the notebook.
2. Open `task2.ipynb` in Jupyter Notebook or Google Colab.
3. Run the cells from top to bottom.
4. Review the model predictions and evaluation results.

## 🎯 Learning Outcome

This project provided practical experience with the basic machine-learning workflow: preprocessing data, training a classification model, generating predictions, and evaluating performance.
