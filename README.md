## Customer Transaction Analysis & Prediction
# Project Overview

This project focuses on analyzing customer transaction data to identify patterns and predict customer behavior using machine learning techniques. The goal is to extract meaningful insights that can help businesses make data-driven decisions.

# Objective

To analyze transaction-level data and build a predictive model that can classify or predict customer-related outcomes based on behavioral patterns.

# Dataset
The Train dataset contains 200000 observations of 202 columns.

The first two columns in the dataset store the unique ID_code numbers of the obseravtions and the corresponding "target" transaction prediction ,respectively.
The columns 2-202 contain 200 real-value features that have been captured which can be used to build a model to predict weather a transaction done by customer.
The Test dataset contains 200000 observations of 201 columns

#  1.Tech Stack
.Python
.Pandas, NumPy
.Matplotlib, Seaborn
.Scikit-learn
2.Data Preprocessing
summarize the data 
check for null values
Visualized target distribution  using  count plot

3 Model Building
Trained machine learning models such as:
Logistic Regression
Random Forest
XGBoost
LightGBM
4 Model Evaluation
Evaluated using metrics like:
Accuracy
Precision
Recall
F1 Score
ROC- AUC Score
5. Report
model comparison report 
 # -Results
The model was able to capture customer behavior patterns effectively.
Achieved a balanced performance across evaluation metrics.
# - Business Insight
Customers who share similar data patterns with previously positive cases are more likely to show the same condition in the future. The models learned these patterns directly from the historical dataset and used them to assign risk probabilities to each customer. Customers with higher prediction scores can be treated as priority cases for monitoring or early intervention. This helps the business focus efforts on the most likely future cases instead of applying the same strategy to everyone.

-## Dataset

The dataset used in this project is large and cannot be uploaded to this repository.

You can download it from Kaggle:
👉 https://www.kaggle.com/code/vi20027804/customer-transaction-prediction/input



 Project Structure
customer-transaction-analysis/s
│── notebook.ipynb
│── README.md
│── requirements.txt
│── .gitignore
# --How to Run
Clone this repository
Install dependencies using:
pip install -r requirements.txt
Run the Jupyter Notebook

# -- Conclusion

This project demonstrates how customer transaction data can be transformed into actionable insights using data analysis and machine learning. The model helps in understanding customer behavior and supports better business decision-making.

