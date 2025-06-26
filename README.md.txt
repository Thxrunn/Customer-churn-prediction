# 📊 Customer Churn Prediction

This project is a machine learning-based solution to predict whether a customer is likely to **churn** (i.e., stop using a service) based on behavioral and demographic factors. The dataset comes from a real-world telecom company and contains various customer attributes.

---

## 🚀 Project Goals

- Analyze and clean customer churn data
- Build a predictive model using machine learning (Random Forest)
- Evaluate model performance using accuracy, precision, recall, and F1-score
- Understand feature importance using SHAP (SHapley Additive exPlanations)
- Deploy a risk scoring engine to flag high-risk customers

---

## 📁 Dataset

- **Source**: IBM Sample Dataset (Telco Customer Churn)
- **File**: `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- **Target Variable**: `Churn` (Yes/No)

---

## 🧠 ML Techniques Used

- **Data Cleaning**: Handled missing values, label encoding for categorical features
- **Model**: RandomForestClassifier from `sklearn`
- **Evaluation**: `accuracy_score`, `classification_report`
- **Explainability**: SHAP summary and interaction plots

---

## 🔍 Key Results

- **Accuracy**: ~78%
- High precision on predicting "churn" customers
- SHAP analysis showed `MonthlyCharges`, `Tenure`, and `Contract Type` as key drivers

---

## ⚙️ Risk Scoring Engine

A post-model pipeline was added to calculate a **Churn Risk Score** (0 to 100 scale) for each customer based on prediction probabilities, giving a business-friendly view of each customer’s likelihood to churn.

---

## 📊 Visualizations

- SHAP interaction plot for feature interaction insights
- Distribution plot of churn risk scores across customer segments

---

## 🧰 Tech Stack

- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- SHAP
- Google Colab

---

## 🗂️ Files in Repo

| File | Description |
|------|-------------|
| `customer_churn_prediction.ipynb` | Jupyter notebook with full end-to-end implementation |
| `WA_Fn-UseC_-Telco-Customer-Churn.csv` | Dataset file |
| `README.md` | Project documentation |

---

## ✨ What I Learned

- Real-world handling of messy categorical and numerical data
- Model interpretability using SHAP
- Turning probabilities into actionable business insights with a risk engine

---

## 📌 Future Improvements

- Add more classifiers (e.g., XGBoost, Logistic Regression)
- Build a simple Streamlit app for demoing predictions
- Tune hyperparameters using GridSearchCV

---

## 🤝 Connect

Feel free to fork, use, or reach out with any feedback or suggestions!

---
Made by Tharun Kumar Malla Dinakaran 
2nd Year Computer Science Student | Aspiring Data Scientist  
California State University San Marcos

