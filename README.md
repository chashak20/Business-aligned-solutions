#  Customer Segmentation & Churn Prediction

##  Project Overview
This project focuses on analyzing customer behavior and predicting churn using machine learning techniques. The goal is to identify customers at risk of leaving and provide actionable insights for improving retention.

##  Objectives
- Analyze customer data to understand behavior patterns  
- Identify key factors influencing customer churn  
- Build machine learning models to predict churn  
- Provide business insights for retention strategies  

##  Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

##  Exploratory Data Analysis (EDA)
- Identified **imbalanced dataset** (~14% churn rate)  
- Found that **customers with high service calls are more likely to churn**  
- Observed strong relationships between usage (minutes) and charges

##  Models Used
### 🔹 Logistic Regression
- Baseline model for churn prediction  
- Improved recall from **47% → 80%** using class balancing  

### 🔹 Random Forest (Best Model)
- Accuracy: **96%**  
- Precision: **1.00**  
- Recall: **0.60**  
- Provided better overall performance and reliability

 
##  Model Results
### Logistic Regression
- Accuracy: ~80%
- Recall (Churn): 80%

### Random Forest (Best Model)
- Accuracy: 96%
- Precision: 1.00
- Recall: 0.60  

##  Key Insights
-  High **customer service calls** strongly indicate churn  
-  Usage patterns (minutes & charges) influence customer behavior  
-  Trade-off between **precision and recall** depends on business goals  

##  Business Impact
- Helps companies identify high-risk customers  
- Enables targeted retention campaigns  
- Reduces revenue loss due to churn  

##  Conclusion
Logistic Regression is useful for maximizing churn detection, while Random Forest provides more accurate and confident predictions. The final model choice depends on business requirements.

##  Future Improvements
- Apply SMOTE for better imbalance handling  
- Hyperparameter tuning  
- Deploy model using Flask/Streamlit  


