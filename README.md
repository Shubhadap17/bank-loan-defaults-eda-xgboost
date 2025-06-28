# Bank Loan Default Prediction using EDA and XGBoost

This project analyzes bank loan application data to identify patterns associated with default risk. It follows a structured data science workflow using Python, pandas, seaborn, and XGBoost.

---

## 🔍 Project Objective

To explore and analyze loan applicant behavior using EDA, handle data quality issues, and build a machine learning model that predicts whether an applicant is likely to default.

---

## ✅ Workflow Summary

- **Step 1–7:** Data loading, missing value treatment, and outlier handling
- **Step 8–13:** Univariate and bivariate analysis, correlation insights
- **Step 14–15:** Model training using XGBoost
- **Step 17:** Class imbalance handled using manual undersampling
- **Step 18–19:** Retrained model and evaluated performance
- **Step 20–21:** Hyperparameter tuning using RandomizedSearchCV

---

## 📊 Final Model Performance

| Metric         | Value   |
|----------------|---------|
| Accuracy       | 69%     |
| Recall (Class 1) | 68%   |
| AUC Score      | ~0.70   |

The final model prioritizes recall for defaulters, making it effective for risk-flagging use cases in financial lending.

---

## 🧠 Key Insights

- Strong predictors include: `DAYS_BIRTH`, `EXT_SOURCE_3`, `AMT_ANNUITY`
- Imbalanced target was managed to improve minority class detection
- Manual class balancing was used for simplicity and explainability
- Hyperparameter tuning improved model robustness

---

## 🛠 Tech Stack

- Python (pandas, numpy)
- seaborn, matplotlib
- XGBoost
- scikit-learn
- Google Colab

---

## 📁 Files Included

- `loan_defaults_eda_XGBoost.ipynb`: Full Colab notebook with code and markdown
- CSV file for `Q_application_data.csv`
- README.md

---

## 🙋 Author

- **Shubhada Patil**
- [GitHub Profile](https://github.com/Shubhadap17)
- [LinkedIn Profile](https://linkedin.com/in/shubhada-s-patil)

---

## 📎 License

This project is intended for educational and demonstration purposes. Contributions and forks are welcome.
