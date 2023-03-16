# Loan Prediction

## Motivation
Approving someone a loan is a risky business because it might never be returned. Thus, estimating whether a borrower is reliable enough is a very important task, if not the most important. The motivation for this project is to predict from data about a customer whether they should be lent money using machine learning algorithms.

## Methodology
This is a multiclass classification type of problem in which a subset of classifiers were trained from `scikit-learn`, and an `XGBoost` classifier. $F_1$ is used for a single number evaluation metric because the data set is imbalanced.

## Results
The most optimal model is the `XGBoost` classifier with default parameters with $F_1=0.9267$.

## Technologies
Technologies used in this project are: scikit-learn, XGBoost, Jupyter Notebook.# Loan-Prediction
