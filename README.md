# Customer Churn Analysis and Prediction

## Project Overview

This project focuses on analyzing customer churn behavior and building machine learning models to predict customers who are likely to leave a service. The objective is to combine data analysis, modeling, and business interpretation to demonstrate practical data science skills.

The project covers the complete lifecycle of a data science workflow:
- Data cleaning and preprocessing  
- Exploratory data analysis  
- Customer segmentation  
- Machine learning modeling  
- Business recommendations  
- Visualizations  

## Objectives

- Understand key factors influencing customer churn  
- Explore patterns in customer behavior using data analysis  
- Segment customers into meaningful groups  
- Build predictive models for churn  
- Translate insights into actionable business strategies  

## Tools and Technologies

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Google Colab  

## Project Structure

```
Customer-Churn-Project/
│
├── Customer_Churn_Analysis.ipynb
├── Churn_Project_Report.pdf
├── README.md
```

## Dataset Notice

The dataset used for this project is not included in this repository due to data usage and privacy considerations.

To reproduce this project, you can use a publicly available dataset such as:
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

## Task 1: Data Cleaning and Preprocessing

- Converted TotalCharges column to numeric format  
- Handled missing values using median imputation  
- Removed irrelevant identifier column (customerID)  
- Encoded categorical variables using one-hot encoding  
- Prepared a clean dataset suitable for modeling  

## Task 2: Exploratory Data Analysis

Key insights identified:
- Overall churn rate is approximately 26%  
- Customers with low tenure have significantly higher churn  
- Higher monthly charges are associated with higher churn  
- Contract type strongly impacts churn behavior  

These insights helped guide segmentation and model development.

## Task 3: Customer Segmentation

Customers were segmented based on:
- Tenure groups (0–12, 12–24, 24–48, 48+ months)  
- Monthly charge groups (Low, Medium, High)  

Findings:
- New customers (0–12 months) show the highest churn  
- High-paying customers have higher churn risk  

## Task 4: Machine Learning Models

Models implemented:
- Logistic Regression  
- Random Forest Classifier  

Random Forest achieved better performance, indicating that churn behavior is influenced by complex, non-linear relationships between features.

Evaluation metrics used:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion matrix  

Special attention was given to recall for churned customers, as identifying at-risk customers is more valuable than overall accuracy.

## Task 5: Business Recommendations

Based on analysis and modeling, the following strategies were proposed:
- Improve onboarding experience for new customers  
- Offer flexible pricing or discounts for high-bill customers  
- Encourage customers to move toward long-term contracts  
- Use predictive model outputs for proactive retention campaigns  
- Promote value-added services such as technical support and security features  

## Task 6: Visualizations

The project includes visualizations such as:
- Churn distribution chart  
- Tenure vs churn boxplot  
- Monthly charges vs churn boxplot  
- Churn rate by contract type  
- Segmentation-based churn analysis  
- Correlation heatmap  

These visualizations support both technical understanding and business interpretation.

## Limitations

- Only structured historical data was used  
- No behavioral or real-time data included  
- Class imbalance was not deeply handled  
- No deployment or production environment implemented  

## Future Improvements

- Apply techniques such as SMOTE to handle class imbalance  
- Experiment with advanced models such as XGBoost  
- Perform deeper feature importance analysis  
- Build an interactive dashboard using Streamlit  
- Deploy the model as a web application
  
## Author

Vaidehi Purohit  
BTech Student | Data Science Enthusiast

## How to Run

1. Download the notebook: `Customer_Churn_Analysis.ipynb`  
2. Open in Google Colab or Jupyter Notebook  
3. Use a public Telco churn dataset (such as Kaggle)  
4. Run cells sequentially from top to bottom  

This project is intended to demonstrate practical skills in data analysis, machine learning, and business problem-solving.
