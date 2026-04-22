# Customer Churn Prediction

## 📌 Project Overview
This project predicts whether a telecom customer will churn (leave the service) using Machine Learning techniques. The model helps businesses identify high-risk customers and take proactive retention actions.

---

## 📊 Dataset
- Source: Kaggle - Telco Customer Churn Dataset
- Features include:
  - Customer demographics
  - Subscription services
  - Billing information
  - Contract details

---

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 🔍 Workflow
1. Data Cleaning & Preprocessing
2. Feature Encoding
3. Train-Test Split
4. Feature Scaling
5. Model Training:
   - Logistic Regression
   - Random Forest
6. Model Evaluation:
   - Accuracy
   - Precision, Recall, F1-score
   - ROC-AUC Score
7. Feature Importance Analysis

---

## 📈 Results
- Random Forest performed better than Logistic Regression
- Achieved strong ROC-AUC score for churn prediction
- Identified key features influencing churn

---

## 🧠 Key Insights
- Customers with month-to-month contracts are more likely to churn
- Higher monthly charges increase churn probability
- Lack of long-term commitment is a major factor

---

## 💾 Model Saving
- Saved trained model using Joblib
- Can be reused for real-time predictions

---

## ▶️ How to Run
1. Clone the repository:
