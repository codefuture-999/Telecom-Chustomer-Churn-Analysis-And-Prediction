# 📞Telecom-Chustomer-Churn-Analysis-And-Prediction
An interactive Power BI dashboard project designed to analyze customer churn behavior for a telecom company. This solution helps understand churn drivers and patterns using demographic, behavioral, geographic, and service usage dimensions.

📊 Project Overview
This project investigates customer churn for a telecom company by combining descriptive and predictive analytics using Power BI, SQL, and Python. It comprises four major components:

1. ETL Process
-A structured ETL (Extract, Transform, Load) pipeline was implemented using SQL Server tools:

-Source data ingested from CSV files.

-Transformation and cleaning using SQL queries.

-Loaded into a production-ready database with views created for Power BI.

2. Churn Analysis Dashboard
This Dashboard investigates churn among telecom customers and answers key questions such as:

Which customer segments have the highest churn rate?

How do contracts, services, and payment methods influence churn?

What are the key geographical zones contributing to churn?

Which reasons dominate churn categories?

3. Churn Prediction Model based on Random Forest Algorithm
A machine learning-based prediction model was developed using the Random Forest algorithm in Python. It included:

Preprocessing with label encoding and null handling

Training and evaluation of the model using a variety of performance metrics

Predicting churn probability and assigning risk profiles to customers

4. Churn Prediction Dashboard
A dedicated dashboard was built in Power BI on top of the prediction output. It includes:

Total predicted churners

Gender-based churn counts

Churn by age group, marital status, tenure, contract, payment method, and state

Customer risk profile matrix

Using advanced DAX measures and data modeling, the dashboard presents insights to support retention strategies and customer lifetime value enhancement.

🔄 ETL Framework
The data for this project was extracted and processed using a structured ETL pipeline as described below:

CSV File: This is the raw source file containing customer churn data.

SQL Server Management Studio (SSMS): Used the built-in import wizard to load and transform the data into a staging table.

SQL Server Database: Final cleaned data was inserted into a production table, which is then used to build Power BI views.

This process ensures data quality, consistency, and scalability for downstream analysis.

