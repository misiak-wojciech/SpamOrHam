# Project: Spam/Ham Message Classification

## Project Description

The goal of this project is to build a classifier that distinguishes text messages as "spam" or "ham" (non-spam messages). The project uses **Logistic Regression** and **Naive Bayes** algorithms, with additional **RandomizedSearchCV** for hyperparameter optimization. To handle imbalanced data, the project leverages **class balancing** through the `class_weight='balanced'` parameter in **Logistic Regression**.

## Contents

- **Input Data**: A dataset containing text messages labeled as "spam" or "ham".
- **Preprocessing**: Includes text cleaning (removing special characters, numbers, etc.) and vectorization using **TF-IDF**.
- **Modeling**: Applied **Logistic Regression** and **Naive Bayes** models, with hyperparameter optimization using **RandomizedSearchCV**.
- **Class Balancing**: Handled using the `class_weight='balanced'` parameter in **Logistic Regression** to adjust for class imbalance.
- **Evaluation**: Evaluated models using accuracy, classification report, and confusion matrix.

## Requirements

- Python 3.x
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - re
  - string


