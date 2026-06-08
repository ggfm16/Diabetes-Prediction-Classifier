# Diabetes Prediction Classifier

A machine learning notebook built and designed to run in Google Colab. Predicts diabetes outcomes using the PIMA Indian Diabetes dataset by comparing four classifiers — Logistic Regression, SVM, KNN, and Random Forest — and selecting the strongest performer for a deep dive analysis.

## What It Does
- Loads the dataset directly from a public GitHub URL, no manual uploads needed
- Performs exploratory data analysis including distribution plots, a correlation heatmap, and pairplots
- Removes outliers using the IQR method
- Trains and evaluates four classifiers, comparing accuracy and ROC AUC scores
- Produces a confusion matrix, classification report, and feature importance chart for the selected Random Forest classifier

## Running the Notebook
Open in Google Colab and run cells in order. All libraries used are available in Colab by default — no additional installation required.
