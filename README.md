# 🧠 Customer Churn Prediction using Deep Learning

## 📌 Overview
This project uses a Deep Learning model to predict **bank customer churn**.  
Businesses can use this to identify customers likely to leave and take retention actions.

---

## 📂 Dataset
- **Rows:** 10,000  
- **Columns:** 14  
- **Source:** Bank Churn Modelling dataset  

### Features
- **CreditScore** – Creditworthiness of customer  
- **Geography** – Country (France, Spain, Germany)  
- **Gender** – Male/Female  
- **Age** – Age of customer  
- **Tenure** – Years with the bank  
- **Balance** – Account balance  
- **NumOfProducts** – Number of bank products  
- **HasCrCard** – Credit card ownership (1/0)  
- **IsActiveMember** – Activity status (1/0)  
- **EstimatedSalary** – Estimated annual salary  

### Target
- **Exited** = 1 → Customer churned  
- **Exited** = 0 → Customer stayed  

Columns like `RowNumber`, `CustomerId`, and `Surname` are dropped.

---

## 🔎 Project Workflow
1. Data preprocessing (encoding, scaling, feature selection)  
2. Exploratory Data Analysis (EDA)  
3. Neural Network model development (TensorFlow/Keras)  
4. Training with EarlyStopping  
5. Model evaluation (Accuracy, Precision, Recall, F1, ROC-AUC)  

---

## ⚡ Model Performance
- **Accuracy:** 86%  
- **ROC-AUC:** 0.89  
- Precision & Recall balanced  

---

## 📊 Business Insights
- Customers with **low tenure**, **month-to-month contracts**, and **high balance** are more likely to churn.  
- **Geography = Germany** shows higher churn compared to France/Spain.  
- **Retention strategies** should focus on high-risk groups (new customers, high charges).  

---

## 🛠 Tech Stack
- Python  
- TensorFlow/Keras  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🚀 How to Run
```bash
git clone https://github.com/your-username/Churn-Prediction-DL.git
pip install -r requirements.txt
jupyter notebook Churn.ipynb
