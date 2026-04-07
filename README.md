Customer Churn Analysis System (Synthetic Data)

Introduction
    Customer churn refers to customers leaving a company’s service. It is a major issue for businesses like banks, telecom, and online
    platforms. Understanding why customers leave helps companies improve their services. This project uses synthetic data and Exploratory Data Analysis
    (EDA) to study customer behavior and identify churn patterns.

Problem Statement
    Organizations collect large amounts of customer data, but analyzing it manually is difficult and time-consuming. Real-world
    data is also not easily available due to privacy issues. Hence, there is a need for a system that generates synthetic data and analyzes 
    it efficiently to understand customer churn.

Objective
Generate synthetic customer dataset
Perform data cleaning and preprocessing
Analyze customer behavior using EDA
Identify factors affecting churn
Provide insights to reduce customer loss

Dataset Overview
    The dataset contains 1,00,000 synthetic customer records created to simulate real-world business scenarios. It includes 
customer details like age, balance, credit score, and activity status.

5. Dataset Features (Columns Used)
Customer_ID – Unique identifier
Age – Customer age (18–70)
Gender – Male / Female
Tenure – Years with company
Balance – Account balance
CreditScore – Credit score (300–900)
EstimatedSalary – Annual income
NumOfProducts – Number of products used
IsActiveMember – Active or inactive
Churn – 0 (No), 1 (Yes)
6. Tools & Technologies
Python – Programming language
Pandas – Data handling and analysis
NumPy – Numerical computations
Matplotlib / Seaborn – Data visualization
Faker – Synthetic data generation

Methodology
 The project follows these steps:
Generate synthetic data
Clean and preprocess data
Perform statistical analysis
Analyze churn behavior
Visualize data
Draw insights and conclusions

Data Generation:
     Synthetic data is generated using Python libraries like Faker and NumPy. It simulates real-world customer information such as age, 
     salary, balance, and activity status without using actual sensitive data.

Data Preprocessing:
Check for missing values
Convert data types
Handle inconsistencies
Encode categorical variables (Gender, IsActiveMember)
Remove duplicates if any

Exploratory Data Analysis (EDA):
EDA is used to understand the dataset by:
Finding mean, median, mode
Calculating standard deviation
Studying distribution of data
Identifying patterns and trends

Churn Analysis:
Compare churn vs non-churn customers
Identify high-risk customers
Analyze how features like balance, tenure, and activity affect churn

Group-Based Analysis:
Age group vs churn
Gender vs churn
Active vs inactive users
Number of products vs churn

Relationship Analysis:
Balance vs churn
Credit score vs churn
Tenure vs churn
These relationships help understand key factors influencing customer decisions.

Data Visualization:

Different charts are used for better understanding:
Bar charts
Pie charts
Histograms
Scatter plots
Box plots
Heatmaps

Conclusion:

This project shows how synthetic data and EDA can help analyze customer churn effectively. It helps identify important 
factors like activity level, tenure, and product usage. Businesses can use these insights to improve customer retention and reduce churn.

Bar Chart:

<img width="797" height="586" alt="image" src="https://github.com/user-attachments/assets/8f17282d-0ba0-413a-97ae-f2af286b4fea" />

Pie Chart:

