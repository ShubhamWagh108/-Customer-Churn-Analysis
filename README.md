# 📊 Customer Churn Analysis

This project aims to predict customer churn using supervised machine learning techniques. By analyzing customer data, we identify patterns and behaviors that signal a higher probability of churn, allowing businesses to take proactive steps to retain valuable customers.

---

## 📌 Project Objectives

- Analyze customer behavior to identify churn patterns.
- Apply machine learning models to predict churn with high accuracy.
- Evaluate model performance using classification metrics.
- Provide actionable insights for customer retention strategies.

---

## 🧰 Tools & Technologies

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Modeling Techniques:** Random Forest, Logistic Regression, Decision Tree
- **Preprocessing Techniques:** Label Encoding, Feature Scaling, SMOTE-ENN
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, Confusion Matrix

---

## 📁 Dataset

- **Source:** [Kaggle / Telco Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn) *(or replace with your source if custom)*
- **Features Include:** Gender, Tenure, Monthly Charges, Total Charges, Contract Type, Internet Service, etc.
- **Target Variable:** `Churn` (Yes/No)

---

## ⚙️ Workflow

1. **Data Cleaning & Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling
   - Balancing data using SMOTE-ENN

2. **Exploratory Data Analysis (EDA)**
   - Visualized churn distribution by customer segments
   - Correlation analysis for feature importance

3. **Model Building & Evaluation**
   - Trained multiple classifiers: Random Forest, Logistic Regression, etc.
   - Evaluated using accuracy and classification report
   - **Best Model Accuracy (Random Forest):** `94.27%`

---

## 📈 Key Insights

- Customers with month-to-month contracts and high monthly charges are more likely to churn.
- Tenure and payment method have strong predictive power for churn.
- SMOTE-ENN improved model balance and reduced overfitting.

---

## 🏁 Results

| Metric      | Value     |
|-------------|-----------|
| Accuracy    | 94.27%    |
| Precision   | 0.94      |
| Recall      | 0.96      |
| F1-Score    | 0.95      |

---

## 📌 Future Improvements

- Deploy the model using Flask or Streamlit for real-time predictions.
- Automate churn probability scoring for each customer.
- Include customer lifetime value (CLV) estimation.

---

## 🙌 Acknowledgments

Special thanks to open-source contributors and datasets provided on Kaggle.

---

## 📬 Contact

**Shubham Wagh**  
LinkedIn: [linkedin.com/in/shubhamwagh](#)  
Email: your-email@example.com  
