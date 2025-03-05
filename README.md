# Data-mining-project

# Customer Churn Prediction

📌 Project Description:
This project aims to predict customer churn in a telecom company using machine learning algorithms. It analyzes customer data to identify the key factors contributing to churn and helps businesses take proactive actions to reduce customer loss.


📂 1. Dataset Information
📊 Source: Telco Customer Churn Dataset
📊 Total Customers: 7043
📊 Key Features:

tenure - Duration of subscription in months
MonthlyCharges - Monthly bill amount
Contract - Type of contract (Monthly, One Year, Two Years)
InternetService - Type of internet service used
Churn - Whether the customer left the company (0 = No, 1 = Yes)

⚙️ 2. Dependencies
To run this project without issues, ensure you have installed the following libraries:
pip install pandas numpy matplotlib seaborn scikit-learn xgboost

🚀 3. How to Run the Project
1️⃣ Clone the project:

git clone https://github.com/RA1997/Data-mining-project.git
cd customer-churn-prediction
2️⃣ Run the Jupyter Notebook (notebook.ipynb)

3️⃣ (Optional) Run the Python script

python churn_prediction.py

📊 4. Models Used
✅ Logistic Regression
✅ Random Forest
✅ XGBoost

🔍 Model Performance Comparison:
Model	Accuracy	Precision	Recall	F1 Score
Logistic Regression	80.48%	65.52%	55.88%	60.32%
Random Forest	80.55%	67.01%	52.67%	58.98%
XGBoost	79.13%	62.90%	52.14%	57.02%
✳ Random Forest achieved the highest accuracy and precision, but Logistic Regression had the best recall.

🔥 5. Key Insights from Data Analysis
📌 Top Factors Contributing to Customer Churn:
1️⃣ Contract Type - Customers on monthly contracts are more likely to churn.
2️⃣ Monthly Charges - Higher monthly bills increase churn probability.
3️⃣ Tenure Duration - Long-term customers tend to stay longer.

📊 Feature Importance Plot:


💡 6. Future Improvements
🔹 Optimize model performance by tuning hyperparameters.
🔹 Use additional data sources to identify more churn factors.
🔹 Experiment with advanced models like Deep Learning (Neural Networks).
