---

# Logistic Regression Model using Pandas

## Overview
This project demonstrates the implementation of a **Logistic Regression** model using Python, `pandas`, and `scikit-learn`.
The objective is to classify whether a tumor is malignant or benign using the **Breast Cancer dataset**.

## Methodology

### Data Collection
- The dataset used in this project is the **Breast Cancer dataset** from the `scikit-learn` library.
- The data is loaded into a `pandas DataFrame` for easier manipulation.
- It consists of:
  - **Features (`x`)**: Various measurements related to tumor characteristics.
  - **Target (`y`)**: Binary classification where `1` represents a malignant tumor and `0` represents a benign tumor.

### Data Preprocessing
- The dataset is separated into independent features (`x`) and the dependent label (`y`).
- The data is split into **70% training data** and **30% test data** using `train_test_split`.

### Model Training
- A **Logistic Regression** model is instantiated using `scikit-learn`.
- The model is trained on the training data to classify tumors based on their features.

### Prediction
- The trained model is used to predict the class of tumors in the test dataset.
- The predictions are compared against the actual labels.

### Evaluation
- The model’s performance is evaluated using:
  - **Accuracy Score**: Indicates the percentage of correct predictions.
  - **Confusion Matrix**: Displays the counts of True Positives, False Positives, True Negatives, and False Negatives.

## Requirements
```bash
pip install pandas scikit-learn
```

## Results
This project produces the following outputs:
- **Accuracy Score**: Shows the proportion of correct predictions made by the model.
- **Confusion Matrix**: Provides a summary of prediction results by showing counts of actual vs. predicted classes.

---
