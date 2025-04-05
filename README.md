# Customer-Churn-Prediction-Behavioral-Segmentation-Dashboard

📘 README.md for
Customer Churn Prediction & Behavioral Segmentation Dashboard
GitHub: ysaikumar21/Customer-Churn-Prediction-Behavioral-Segmentation-Dashboard

markdown
Copy
Edit
# 🧠 Customer Churn Prediction & Behavioral Segmentation Dashboard

An end-to-end data science project that predicts customer churn using machine learning and segments customers based on their behavior. The insights are visualized using an interactive Power BI dashboard to drive actionable retention strategies.

![Screenshot 2025-04-05 143509](https://github.com/user-attachments/assets/7513c6af-e9cd-4edc-ad5b-effe5309fc06)


---

## 🚀 Project Overview

This project is built on a real-world Telco customer dataset and covers the full data science pipeline:

- 📊 Exploratory Data Analysis (EDA)
- 🧼 Data Cleaning & Feature Engineering
- 🧠 Machine Learning (Logistic Regression, Random Forest, XGBoost)
- 🔍 SHAP for model explainability
- 📦 Customer Segmentation (KMeans Clustering)
- 📈 Power BI Dashboard for storytelling & insights

---

## 📁 Dataset

**Source**: [Telco Customer Churn - Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- ~7,000 customer records
- Features: Demographics, Services, Charges, Contract, and Churn Status

---

## 🛠️ Tools & Technologies

| Tool        | Purpose                             |
|-------------|-------------------------------------|
| Python      | Data processing & machine learning  |
| Scikit-learn | ML models                          |
| SHAP        | Explainable AI                      |
| Power BI    | Business Intelligence Dashboard     |
| KMeans      | Customer Segmentation               |
| Pandas, Seaborn | EDA and visualization           |

---

## 📌 Key Insights

- Contract type and tenure are strong churn predictors.
- Customers with month-to-month contracts are at highest churn risk.
- SHAP reveals `MonthlyCharges`, `Contract`, and `tenure` as top churn drivers.
- KMeans clustering identifies 3 behavioral segments with different churn tendencies.

---

## 📊 Power BI Dashboard Highlights

- ✅ Total Customers, Churn %, and Revenue at Risk
- ✅ Churn Analysis by Services & Demographics
- ✅ SHAP Feature Importance Bar Chart
- ✅ Customer Segments with Avg Tenure, Charges, Churn %
- ✅ Filters for Gender, Segment, Contract Type, etc.
- ✅ Strategic recommendations for each customer segment

---

## 📁 Folder Structure

├── data/ │ └── WA_Fn-UseC_-Telco-Customer-Churn.csv ├── notebooks/ │ └── churn_modeling.ipynb ├── dashboard/ │ └── Churn_Dashboard.pbix ├── images/ │ └── dashboard-preview.png ├── README.md

yaml
Copy
Edit

---

## 📚 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/ysaikumar21/Customer-Churn-Prediction-Behavioral-Segmentation-Dashboard.git
Run the notebook inside /notebooks to explore and train models.

Open the Power BI file inside /dashboard to explore insights visually.


📈 Results Summary
Model	                              Accuracy	      Precision	      Recall	    F1 Score	            ROC AUC
Logistic Regression	                  80.6%	            65.8%	      55.6%	        60.3%	                84.2%
Random Forest	                        79.9%	             63.3%	    49.5%	        55.5%	                82.2%
XGBoost	                              78.9%	             61.7%	     54.2%	       57.7%	              82.8%

🙋‍♂️ Author
Saikumar Y
📧 ysaikumar21@gmail.com
🔗 LinkedIn :https://www.linkedin.com/in/saikumar-y-853666317/| 
GitHub:https://github.com/ysaikumar21/Customer-Churn-Prediction-Behavioral-Segmentation-Dashboard

⭐ Project Highlights for Resume
Developed an ML-driven Power BI dashboard to predict customer churn and segment behavior, delivering insights into high-risk customers and retention strategies using SHAP and clustering techniques.

