# part-1-neural-network-analysis

# Customer Churn Prediction using Neural Networks

## Project Overview

This project focuses on building and analyzing a Feed Forward Neural Network for customer churn prediction using a structured dataset.

The main objective of this project is to understand how neural networks learn through:
- Forward Propagation
- Loss Calculation
- Backpropagation
- Weight and Bias Updates
- Hyperparameter Tuning

The model predicts whether a customer is likely to churn or remain with the company.

---

# Dataset Information

Dataset Used:
- `customer_churn_nn.csv`

Target Variable:
- `churn`
  - 1 = Customer Churned
  - 0 = Customer Retained

---

# Features Used

## Categorical Features
- region
- plan_type
- contract_type
- payment_method

## Numerical Features
- tenure_months
- monthly_charges
- total_charges
- avg_login_days
- support_tickets
- payment_delays
- data_usage_gb
- satisfaction_score
- complaint_recency_days
- discounts_used
- referrals

---

# Project Workflow

## Task 1: Dataset Understanding
- Loaded dataset using Pandas
- Checked rows and columns
- Analyzed feature types
- Checked missing values
- Generated statistical summary
- Visualized target variable distribution

## Task 2: Data Preprocessing
- Removed unnecessary columns
- Handled missing values
- Encoded categorical features
- Scaled numerical features
- Performed train-test split

## Task 3: Neural Network Model Building
- Built Feed Forward Neural Network using TensorFlow/Keras
- Added hidden layers with ReLU activation
- Used Sigmoid activation for output layer
- Used Binary Crossentropy loss function
- Used Adam optimizer

## Task 4: Training and Evaluation
- Trained neural network model
- Evaluated training and testing performance
- Generated:
  - Accuracy Graph
  - Loss Graph
  - Confusion Matrix
  - Classification Report

## Task 5: Hyperparameter Experimentation
Performed multiple experiments by changing:
- Hidden layers
- Number of neurons
- Batch size
- Epochs
- Activation functions

Compared model performances using a comparison table.

## Task 6: Final Reflection
Explained:
- Role of weights and biases
- Importance of activation functions
- Effect of learning rate
- Underfitting and overfitting

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow/Keras
- Jupyter Notebook

---
