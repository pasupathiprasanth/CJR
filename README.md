# CJR
CJR project
# Logistic Regression from Scratch using NumPy

## Project Overview
This project implements a binary Logistic Regression model entirely from scratch using NumPy. The objective is to understand the internal workings of logistic regression without relying on machine learning libraries.

## Key Features
- Custom sigmoid function
- Binary Cross-Entropy loss
- Batch Gradient Descent optimization
- Train-test split and feature scaling
- Model evaluation using accuracy

## Dataset
Synthetic binary classification data was generated using `make_classification` with 4 features. All features were standardized using `StandardScaler`.

## Files
- `logistic_regression.py` / notebook: Model implementation and training
- `README.md`: Project explanation and summary

## Results
The model successfully converges and achieves good classification accuracy on the test dataset. Learned weights and bias are reported and interpreted in the written analysis.

## Conclusion
This project demonstrates a clear and correct implementation of logistic regression fundamentals and provides interpretability of learned parameters.
