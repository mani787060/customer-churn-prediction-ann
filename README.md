# Customer Churn Prediction Using Artificial Neural Network (ANN)

## Project Overview
Customer churn prediction is a crucial business problem where organizations aim to identify customers who are likely to discontinue their services.  
This project uses an **Artificial Neural Network (ANN)** to predict customer churn based on customer demographics, account information, and service usage data.

The model helps businesses take **proactive retention decisions** by identifying high-risk customers early.

---

## Problem Statement
To build a deep learning model that accurately predicts whether a customer will **churn (Yes/No)** using historical customer data.

---

###  Target Variable
- **Churn**: Indicates whether a customer has left the service.

### 🔑 Key Features
- Gender  
- Senior Citizen  
- Tenure  
- Monthly Charges  
- Total Charges  
- Contract Type  
- Payment Method  

---

## ⚙️ Project Workflow
1. Data Loading and Inspection  
2. Data Cleaning and Encoding  
3. Feature Scaling  
4. Train-Test Split  
5. ANN Model Design  
6. Model Training  
7. Model Evaluation  

---

## ANN Model Architecture
- **Input Layer**: Customer features  
- **Hidden Layers**:
  - Dense layer with ReLU activation
  - Dropout for regularization
- **Output Layer**:
  - Sigmoid activation for binary classification  

---

## Evaluation Metrics
The model performance is evaluated using:
- Accuracy Score  
- Confusion Matrix  
- Classification Report  

---

## Tech Stack
- **Programming Language:** Python  
- **Libraries & Frameworks:**
  - NumPy  
  - Pandas  
  - Matplotlib  
  - Scikit-learn  
  - TensorFlow  
  - Keras  
