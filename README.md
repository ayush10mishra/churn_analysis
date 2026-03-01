# 📊 Customer Churn Analysis & Prediction

## 🚀 Project Overview
Customer churn is a major challenge for subscription-based businesses. This project analyzes customer behavior data and builds machine learning models to predict whether a customer is likely to discontinue a telecom service. The objective is to identify high-risk customers early and enable data-driven retention strategies.

---

## 🎯 Problem Statement
Develop a supervised machine learning model to predict customer churn based on:

- Demographic information  
- Service usage patterns  
- Contract details  
- Billing information  
- Payment methods  

Target Variable: **Churn (Yes/No)**

---

## 📂 Project Structure

churn_analysis/  
│  
├── Churn Analysis - EDA.ipynb  
├── Churn Analysis - Model Building.ipynb  
├── Customer Churn Knowledge.py  
├── LICENSE  
└── README.md  

---

## 📊 Dataset Information
Dataset used: Telco Customer Churn Dataset  

The dataset includes:

- Gender  
- Senior Citizen status  
- Tenure  
- Internet service type  
- Contract type  
- Monthly charges  
- Total charges  
- Churn status  

⚠️ Dataset is not included in this repository due to size constraints.  
It can be downloaded from Kaggle (Telco Customer Churn dataset).

---

## 🔍 Exploratory Data Analysis (EDA)
Key insights discovered:

- Month-to-month contracts have higher churn rates.  
- Customers with shorter tenure are more likely to churn.  
- Higher monthly charges increase churn probability.  
- Electronic check payment method shows higher churn tendency.  

EDA includes distribution analysis, correlation studies, and feature relationship visualization.

---

## 🤖 Machine Learning Models Implemented
- Logistic Regression  
- Decision Tree  
- Random Forest  

---

## 📈 Model Evaluation
Models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC  
- Confusion Matrix  

The best-performing model was selected based on overall evaluation metrics.

---

## 🧠 Key Predictive Features
- Contract Type  
- Tenure  
- Monthly Charges  
- Internet Service  
- Payment Method  

---

## 🛠 Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## ▶️ How to Run

1. Clone the repository  
   git clone git@github.com:ayush10mishra/churn_analysis.git  

2. Navigate to the folder  
   cd churn_analysis  

3. Install dependencies  
   pip install -r requirements.txt  

4. Launch Jupyter Notebook  
   jupyter notebook  

---

## 📌 Business Impact
Accurate churn prediction helps businesses:

- Improve retention strategies  
- Reduce revenue loss  
- Optimize marketing efforts  
- Increase customer lifetime value  

---

## 🚀 Future Improvements
- Hyperparameter tuning  
- Advanced feature engineering  
- Model explainability using SHAP  
- Deployment using Flask or FastAPI  
- Integration with business dashboards  

---

## 👨‍💻 Author
Ayush Mishra  
Machine Learning & Data Analysis Enthusiast  
GitHub: https://github.com/ayush10mishra  
