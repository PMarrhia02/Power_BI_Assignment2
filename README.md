# Power_BI_Assignment2
This Repository contains Power BI Assignment 2.

In this assignment, I used Power BI to analyze banking data. The project steps include:

Load the Dataset: 
Import the banking CSV file into Power BI.

Clean and Transform Data: 
Use Power Query to remove unnecessary columns, fix data types, and handle missing values.

Create Relationships: 
Link tables (e.g., Customer_Modelling and Account_Details) via common fields like CustomerId.

Add Calculated Columns: 
 Use DAX to create new columns. For example, a churn indicator:
 Churn Status = IF('Account_Details'[Exited] = 1, "Churned", "Active")
Visualize Data :
Build charts and dashboards (e.g., pie charts for churn vs. active customers) to present insights.

This is the google drive link for the screenshots uploaded : https://drive.google.com/drive/folders/1oU8wS7uBby_JeXXLZHuURbSkw2KB-KEf?usp=sharing
