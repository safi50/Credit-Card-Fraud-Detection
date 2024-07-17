# Fraud Detection in Credit Card Transactions using Unsupervised Learning

## Business Objective

In the banking or payment industry, fraud involves the illegal use of credit card details without the cardholder’s knowledge. The goal of this project is to detect fraudulent transaction activity in real-time using machine learning techniques.

## Approach

We use unsupervised learning methods:

- **Isolation Forest:** Identifies anomalies by isolating outliers using decision trees.
- **Local Outlier Factor (LOF):** Detects outliers based on local density deviations.

## Data Description

- **Dataset:** 15 numerical columns, 140,000 rows (PCA transformed).
- **Confidential:** No background information on the features.

## Aim

Build a model to identify fraudulent credit card transactions using Isolation Forest and LOF.

## Tech Stack

- **Language:** Python
- **Libraries:** `sklearn`, `pandas`, `matplotlib`, `numpy`, `seaborn`

## Steps

1. Import required libraries and packages.
2. Load and preprocess the dataset.
3. Perform exploratory data analysis.
4. Handle missing values.
5. Determine contamination amount.
6. Train the model.
7. Make predictions.
