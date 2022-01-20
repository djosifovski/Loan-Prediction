# Loan Prediction

## Motivation
Approving someone a loan is a risky business because it might never be returned. Thus, estimating whether a borrower is reliable enough is a very important taks, if not the most important. The motivation for this project is to predict from data about a customer whether they should be lent money using machine learning algorithms.

## Methodology
This is a multiclas classification type of problem in which a subset of learning algoritms were trained from `scikit-learn`, and `XGBoost` classifier. As a single number evaluation metric F_1 is used, and the most optimal model is the `XGBoost` classifier with F_1=0.9600.