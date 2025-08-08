# Classification with Logistic Regression – Breast Cancer Prediction

This project implements a **binary classification** model using **Logistic Regression** to predict whether a tumor is **malignant** or **benign** based on the **Breast Cancer Wisconsin dataset**. It demonstrates the full machine learning workflow from preprocessing to evaluation, with explanations suitable for both learning and practical use.


## Project Overview
Logistic Regression is a widely used algorithm for binary classification problems. This project:
- Loads and explores the Breast Cancer dataset.
- Preprocesses the data (scaling & splitting).
- Trains a Logistic Regression model.
- Evaluates the model using multiple metrics.
- Tunes classification thresholds.
- Explains the sigmoid function for probability mapping.


## Tech Stack
- **Python 3**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib**, **Seaborn** – Data visualization
- **Scikit-learn** – Machine learning algorithms & metrics

## Features
- **Data Preprocessing**
  - Train/Test split
  - Feature scaling with StandardScaler
- **Model Training**
  - Logistic Regression from Scikit-learn
- **Evaluation Metrics**
  - Confusion Matrix
  - Precision, Recall, F1-score
  - ROC Curve and AUC score
- **Threshold Tuning**
  - Adjust decision threshold for custom precision/recall trade-off
- **Mathematical Insight**
  - Sigmoid function explained and visualized

## Files Included

- `Task4.ipynb` - Jupyter notebook with full implementation
- `README.md`
- `ConfusionMatrix.png`
- `ROC_curve.png`
