# Customer Churn Prediction

This project predicts whether a customer will churn (leave) or stay with a subscription service using the Telco Customer Churn dataset.

## 🚀 What I Did
- Cleaned and preprocessed the dataset (handled nulls, encoded categorical variables)  
- Performed Exploratory Data Analysis (EDA) to identify churn patterns  
- Built and compared Logistic Regression and Decision Tree models (~80% accuracy)  
- Analyzed feature importance to highlight the biggest drivers of churn  
- Proposed business recommendations to reduce churn (e.g., discounts, longer contracts)

## 📊 Key Insights  
- Month-to-month contract customers have higher risk of churn  
- New customers (shorter tenure) are more likely to churn  
- High monthly charges are correlated with churn risk  

## 🛠️ Tools & Tech  
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

## 🔧 Setup and Run  
```bash
git clone https://github.com/Reshmabegam18/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction
pip install -r requirements.txt
jupyter notebook notebooks/Customer_Churn_Prediction.ipynb
