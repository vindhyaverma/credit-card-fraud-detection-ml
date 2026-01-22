# credit-card-fraud-detection-ml
# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques.  
Since fraud cases are very rare compared to normal transactions, the dataset is highly imbalanced, making this a real-world and challenging problem.

The goal of this project is to build and evaluate machine learning models that can accurately identify fraudulent transactions.

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Logistic Regression
- Random Forest

---

## 📊 Dataset
Credit Card Fraud Dataset (Kaggle)

- Class 0: Normal transaction  
- Class 1: Fraudulent transaction  

---

## ⚙️ Project Workflow
1. Load and explore the dataset
2. Analyze class imbalance
3. Split data into training and testing sets
4. Train Logistic Regression as a baseline model
5. Train Random Forest with class balancing
6. Evaluate models using precision, recall, and F1-score
7. Test the trained model on unseen transactions

---

## 📈 Model Evaluation
Due to heavy class imbalance, accuracy alone is not reliable.  
Models were evaluated using:
- Precision
- Recall
- F1-score
- Confusion Matrix

Random Forest performed better than Logistic Regression in identifying fraud cases.

---

## ▶️ Example Usage
```python
rf_model.predict(X_test[:1])
