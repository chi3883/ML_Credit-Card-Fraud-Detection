# Credit Card Fraud Detection

## Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset used is highly imbalanced, with fraudulent transactions accounting for only a small portion of the total transactions. The aim is to accurately classify transactions as fraudulent or legitimate by addressing the class imbalance problem using resampling techniques.

## Key Features of the Project

1. **Dataset**: 
   - Includes features like transaction amount, time, and anonymized attributes.
   - Imbalanced: Fraudulent transactions are significantly less than legitimate ones.

2. **Challenges**:
   - **Class Imbalance**: Legitimate transactions far outnumber fraudulent ones.
   - **Cost of Misclassification**: A false negative (missed fraud) is more costly than a false positive (incorrectly flagged fraud).

3. **Techniques**:
   - **Resampling Methods**: Use of oversampling methods like SMOTE (Synthetic Minority Over-sampling Technique).
   - **Anomaly Detection**: Treat fraud detection as an anomaly detection problem.
   - **Cost-sensitive Learning**: Adjust class weights to give more importance to fraudulent transactions.
   - **Ensemble Methods**: Apply models like Random Forest and XGBoost, which are robust against class imbalance.

4. **Evaluation Metrics**:
   - **Precision**: Measures how many predicted frauds are actual frauds.
   - **Recall**: Measures how many actual frauds are detected by the model.
   - **F1 Score**: Harmonic mean of precision and recall.
   - **ROC-AUC Curve**: Measures how well the model distinguishes between classes.

---

## Project Structure

- `notebooks/`: Contains Jupyter notebooks for data exploration, preprocessing, and model training.
- `data/`: Contains the dataset (both raw and preprocessed).
- `models/`: Saved models in this directory for future use.
- `reports/`: Contains evaluation metrics, graphs, and summary reports.
- `README.md`: This file.

---

## Installation Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/chi3883/ML_Credit-Card-Fraud-Detection/edit/main/README.git
   cd fraud-detection
