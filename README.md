# 🚀 Customer Churn Prediction Using Artificial Neural Network (ANN)

## 📌 Project Overview

Customer churn is a major business challenge where companies need to identify customers who are likely to leave their services.

This project develops an **Artificial Neural Network (ANN)** to predict customer churn using customer demographic, account, and service-related information.

The objective is to build a classification model that can identify customers at higher risk of churn, helping businesses take **proactive customer-retention actions**.

---

## 🎯 Problem Statement

The goal of this project is to build a **Deep Learning binary classification model** that predicts whether a customer is likely to churn based on historical customer information.

### Target Variable

**Churn**

* `0` → Customer stays
* `1` → Customer churns

---

## 📂 Dataset

The project uses the **Churn Modelling** dataset available on Kaggle.

**Dataset File:**

```text
Churn_Modelling.csv
```

The dataset contains customer information such as:

* Customer demographics
* Credit score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of products
* Credit card status
* Active membership
* Estimated salary

The target variable indicates whether the customer exited the service.

---

## 🔄 Project Workflow

The project follows a complete Machine Learning and Deep Learning workflow:

```text
Dataset
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Categorical Encoding
   ↓
Feature Selection
   ↓
Feature Scaling
   ↓
Train-Test Split
   ↓
ANN Architecture
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Churn Prediction
```

---

## 🧹 Data Preprocessing

The dataset contains both numerical and categorical features.

The preprocessing pipeline includes:

* Checking missing values
* Removing unnecessary columns
* Separating features and target
* Encoding categorical variables
* Splitting data into training and testing sets
* Scaling numerical features

Feature scaling is particularly important for ANN models because neural networks are sensitive to differences in feature magnitudes.

---

## 🧠 Artificial Neural Network Architecture

The project uses a feed-forward **Artificial Neural Network** for binary classification.

### Architecture

```text
Input Features
      ↓
Dense Layer
      ↓
ReLU Activation
      ↓
Dropout
      ↓
Dense Layer
      ↓
ReLU Activation
      ↓
Dropout
      ↓
Output Layer
      ↓
Sigmoid Activation
      ↓
Churn Probability
```

### Activation Functions

**ReLU**

Used in hidden layers to introduce non-linearity and help the network learn complex relationships.

**Sigmoid**

Used in the output layer because churn prediction is a binary classification problem. It produces a probability between `0` and `1`.

---

## 🛡️ Regularization

The model uses **Dropout** to reduce the risk of overfitting.

During training, Dropout randomly disables a portion of neurons, encouraging the network to learn more robust patterns rather than memorizing the training data.

---

## ⚙️ Model Training

The ANN is trained using:

* Forward propagation
* Backpropagation
* Gradient-based optimization
* Binary classification loss
* Multiple training epochs

The model learns by minimizing the difference between predicted churn probabilities and actual customer outcomes.

---

## 📊 Model Evaluation

The trained model is evaluated using multiple metrics rather than relying only on accuracy.

### Metrics Used

* **Accuracy Score**
* **Confusion Matrix**
* **Classification Report**
* Precision
* Recall
* F1-Score

These metrics provide a better understanding of how effectively the model identifies customers who are likely to churn.

---

## 💼 Business Use Case

A churn prediction system can help organizations:

* Identify high-risk customers
* Prioritize retention campaigns
* Personalize customer offers
* Reduce customer acquisition costs
* Improve customer retention
* Make data-driven business decisions

For example, customers predicted to have a high probability of churn could be targeted with personalized offers or retention strategies.

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Libraries & Frameworks

* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* TensorFlow
* Keras

### Environment

* Jupyter Notebook
* Kaggle Notebook

---

## 📁 Project Structure

```text
customer-churn-prediction-ann/
│
├── customer-churn-prediction-ann.ipynb
├── README.md
└── Churn_Modelling.csv
```

> The dataset is sourced from Kaggle and may be loaded directly through the Kaggle environment rather than stored locally in the repository.

---

## 🎓 Key Learning Outcomes

Through this project, I gained practical experience with:

* Customer churn prediction
* Binary classification
* Artificial Neural Networks
* Data preprocessing
* Categorical feature encoding
* Feature scaling
* ReLU and Sigmoid activation functions
* Dropout regularization
* Model training and evaluation
* Confusion matrix interpretation
* Precision, Recall, and F1-score
* Applying Deep Learning to a real-world business problem

---

## 🚀 Future Improvements

Potential improvements for this project include:

* Hyperparameter tuning
* Early stopping
* Learning-rate optimization
* Class imbalance handling
* ROC-AUC evaluation
* Precision-Recall curve
* Feature importance analysis
* SHAP-based model interpretability
* Comparison with Logistic Regression
* Comparison with Random Forest and XGBoost
* Deployment using Streamlit or FastAPI

---

## 💡 Key Takeaway

This project demonstrates how **Artificial Neural Networks can be applied to a practical business problem such as customer churn prediction**.

The main objective is not only to achieve good predictive performance but also to understand the complete Deep Learning workflow—from preprocessing and feature scaling to ANN architecture, regularization, training, and evaluation.

It provides a practical foundation for building more advanced **Deep Learning and Machine Learning solutions for real-world business problems**.

---

## 👨‍💻 About the Project

This project is part of my ongoing **Machine Learning and Deep Learning learning journey**, where I focus on understanding algorithms practically and applying them to real-world datasets.

I am continuously building projects to strengthen my skills in **Machine Learning, Deep Learning, and Artificial Intelligence**.
