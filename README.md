# 🧠 Credit Card Churn Prediction

Predicting which customers are likely to cancel their credit card subscription using machine learning and exploratory data analysis (EDA).

## 🔍 Problem Overview

**Churn** is when a customer stops using a company's product or service. In the credit card industry, churn directly impacts revenue, customer lifetime value, and growth projections.

> Reducing churn is up to 5x cheaper than acquiring new customers.

## 💡 Business Objective

- Predict which customers are at **high risk of churn**.
- Provide **actionable insights** to support customer retention strategies.
- Understand behavioral and demographic patterns that **differentiate loyal vs. churning customers**.

---

## 📊 Key Questions Answered

- Is the target variable **imbalanced**?
- What are the **main factors** correlated with churn?
- How do behaviors differ between **churned** and **retained** customers?
- Are there specific **card types or customer profiles** more prone to churn?

---

## 📁 Dataset

- Public dataset on credit card clients (Kaggle or similar)
- Target variable: `Attrition_Flag` (churned or not)

---

## 🧪 Project Structure

1. **Data Cleaning**
   - Null values, dtypes, feature engineering

2. **Exploratory Data Analysis (EDA)**
   - Distribution of target variable
   - Correlation heatmap
   - Histograms, boxplots, and bar charts

3. **Insights & Storytelling**
   - Behavioral patterns (e.g., card usage, credit limit)
   - Impact of income and card type
   - Profiles of high-risk customers

4. **Modeling**
   - Baseline model (e.g., Logistic Regression)
   - More advanced models (Random Forest, XGBoost, etc.)
   - Handling imbalance (e.g., SMOTE, class weights)

5. **Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix, ROC-AUC

---

## 📉 Financial Impact Example

If a company has:

- 10,000 clients
- Avg. monthly revenue per client: $100
- Current churn rate: **10%**

That's **$100,000/month** in lost revenue.

> Reducing churn to 5% saves **$50,000/month**.

---

## 📈 Key Results (Example)

- Accuracy: 86%
- ROC-AUC: 0.91
- Top churn indicators:
  - Low card usage
  - Low customer engagement
  - Lower credit limits

---

## 📦 Tools & Technologies

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Scikit-learn** (ML algorithms & metrics)
- **Jupyter Notebook**
- Optional: **XGBoost**, **LightGBM**

---

## 📚 Future Improvements

- Hyperparameter tuning (GridSearchCV)
- Feature importance analysis (SHAP)
- Deploy as a web app (e.g., Streamlit or Flask)
- Create a real-time churn dashboard

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📬 Contact

- GitHub: [Your GitHub Username]
- LinkedIn: [Your LinkedIn Profile]
- Email: [Your email]

---

⭐️ **If you found this project helpful, feel free to give it a star!**
