\# Breast Cancer Classification using Logistic Regression



\## Overview

This project uses Logistic Regression to classify tumors as malignant or benign using the Breast Cancer dataset from scikit-learn.



\## Dataset

\- Breast Cancer Wisconsin Dataset from `sklearn.datasets`

\- Binary classification task

\- Target classes:

&#x20; - 0 = malignant

&#x20; - 1 = benign



\## Features

The dataset contains 30 numeric features related to cell nucleus characteristics, such as radius, texture, perimeter, area, smoothness, and concavity.



\## Workflow

\- Loaded and inspected dataset

\- Checked class distribution

\- Split data into training and testing sets

\- Standardized features using `StandardScaler`

\- Trained Logistic Regression model

\- Evaluated using accuracy, confusion matrix, classification report, ROC curve, and AUC

\- Saved trained model and scaler



\## Model

\- Algorithm: Logistic Regression

\- Library: scikit-learn



\## Evaluation Metrics

\- Accuracy: add your value here

\- ROC-AUC: add your value here



\## Results

The model performs strongly on this dataset and is able to separate malignant and benign tumors effectively.



\## Visualizations

\### Confusion Matrix

!\[Confusion Matrix](images/confusion\_matrix.png)



\### ROC Curve

!\[ROC Curve](images/roc\_curve.png)



\## Files

\- `breast\_cancer\_classification.ipynb` - full notebook

\- `logistic\_regression\_model.pkl` - trained model

\- `scaler.pkl` - fitted scaler

\- `requirements.txt` - dependencies



\## Conclusion

This project demonstrates a complete machine learning classification workflow using Logistic Regression on a real-world medical dataset.



\## Future Improvements

\- Tune regularization parameters

\- Compare with Random Forest and SVM

\- Deploy using Streamlit

