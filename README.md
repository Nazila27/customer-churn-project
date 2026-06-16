# 📊 Customer Churn Prediction & Customer Segmentation

## 🧠 Project Overview
This project focuses on predicting customer churn for a telecom company using machine learning techniques. In addition, unsupervised learning (K-Means clustering) is applied to segment customers into meaningful business groups.

The goal is to identify customers who are likely to leave and provide actionable insights for customer retention strategies.

---

## 🎯 Problem Statement
Customer churn is a major issue in subscription-based businesses. The objective of this project is to:
- Predict whether a customer will churn or not
- Identify the key factors influencing churn
- Segment customers based on behavior patterns

---

## 📂 Dataset
The dataset contains telecom customer information including:
- Customer demographics
- Subscription details
- Billing information
- Target variable: **Churn**

---

## 🧹 Data Preprocessing
- Converted `TotalCharges` to numeric format
- Handled missing values
- Encoded categorical variables using one-hot encoding
- Scaled numerical features using StandardScaler

---

## 📊 Exploratory Data Analysis (EDA)
Key insights:
- Customers with shorter tenure are more likely to churn
- Month-to-month contracts have higher churn rates
- Higher monthly charges increase churn probability

---

## 🤖 Machine Learning Models

### Supervised Learning Models:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1-score

### Key Result:
Random Forest performed best among all models.

---

## 🧩 Customer Segmentation (Unsupervised Learning)
K-Means clustering was applied to group customers into 3 segments:

- 🔴 High Risk Customers (high churn probability)
- 🟢 Loyal Customers (low churn probability)
- 🟡 Low Usage Customers (low engagement)

---

## 📈 Key Insights
- High-risk customers have lower tenure and higher monthly charges
- Loyal customers show long-term engagement
- Payment method and contract type are strong churn indicators

---

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 📊 Visualizations
- Feature importance from Random Forest
- PCA visualization of clusters
- Churn rate by cluster
- Monthly charges distribution across segments

---

## 🚀 Conclusion
This project demonstrates an end-to-end machine learning pipeline including:
- Data preprocessing
- Predictive modeling
- Customer segmentation
- Business insight extraction

The results can help businesses improve customer retention and reduce churn rate effectively.

---

## 📌 Author
Nazila Roudini
