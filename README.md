## Telco Customer Churn Prediction

**Machine Learning & Business Insights Project by Vania Souza**

---

###  Objective

This project aims to predict customer churn using machine learning and generate business-oriented insights for retention strategy.  
The model was trained on real telco data and evaluated using classification metrics. Final predictions are presented in tabular form.

---

### 📁 Project Structure

| File                                | Description                                                 |
|-------------------------------------|-------------------------------------------------------------|
| `Telco_customer_churn_with_results.ipynb` | Jupyter notebook with full ML pipeline and visual analysis |
| `churn_predictions.csv`            | Final output including `CustomerID`, churn prediction and probability |
| `README.md`                         | Project overview (this file)                               |

---

###  Dataset

- Source: Kaggle – Telco Customer Churn

- Records: 7,043 customers

---

###  Techniques & Tools

- Exploratory Data Analysis (EDA)
- Data preprocessing (handling nulls, encoding, scaling)
- Feature selection
- Model training: **Random Forest (tuned)**
- Threshold adjustment for better recall
- Model evaluation: accuracy, F1-score, ROC AUC


---

###  Model Performance

| Metric              | Score |
|---------------------|-------|
| Accuracy            | 0.80  |
| F1-Score (Churn)    | 0.67  |
| ROC AUC             | 0.86  |
| Threshold used      | 0.40  |

---

###  Key Insights

- Customers on month-to-month contracts with high monthly charges have higher churn risk.
- Adjusting the model's threshold improved churn detection.
- Predictive probabilities allow the business to segment risk and take proactive action.

---

###  Business Recommendations

- Offer long-term contract incentives for high-risk profiles.
- Prioritise retention campaigns for customers with short tenure and high bills.
- Integrate churn scores into CRM to alert sales/support teams in advance.

---




╔══════════════════════════════════════╗
║      📊 Customer Churn Prediction    ║  <- Título grande
║   Machine Learning Project (Python)  ║
╠══════════════════════════════════════╣
║ 📌 Model: Random Forest (tuned)      ║
║ 🎯 Accuracy: 80%                     ║
║ 📈 ROC AUC: 0.86                     ║
║ 📊 F1-score (churn class): 0.67      ║
╠══════════════════════════════════════╣
║ 💡 Business-focused predictions      ║
║ 🧠 Threshold adjusted for recall     ║
╚══════════════════════════════════════╝
         By Vania Souza | Data Analytics

###  Next Steps

- Deploy model via Streamlit or API for business use
- Add customer segmentation layer for more detailed targeting
- Train on expanded or multilingual datasets

---
