# Churn-Reasons-Data-Analysis

This project analyzes customer data from a telecommunications company to understand the key drivers behind customer churn (when customers stop using the service).

## Dataset Overview

- **File Name:** `Databel - Data.csv`
- **Total Rows (Customers):** 7,043 (including header) / ~7,042 data rows
- **Total Columns (Features):** 39

## Column Descriptions

The dataset is divided into several logical groups: Customer Information, Service Usage, Financial Data, and Churn Details.

| Column Name | Description |
| :--- | :--- |
| **Customer ID** | A unique identifier for each customer. |
| **Churn Label** | Indicates if the customer has churned (Yes) or is still active (No). |
| **Account Length (in months)** | The total number of months the customer has been with the company. |
| **Local Calls** | The total number of local calls made by the customer. |
| **Local Mins** | The total number of local minutes used. |
| **Intl Calls** | The total number of international calls made. |
| **Intl Mins** | The total number of international minutes used. |
| **Intl Active** | Indicates if the customer has made international calls (Yes/No). |
| **Intl Plan** | Indicates if the customer has an international calling plan (yes/no). |
| **Extra International Charges** | Additional charges incurred for international calls beyond the plan. |
| **Customer Service Calls** | The number of times the customer contacted customer support. |
| **Avg Monthly GB Download** | The average amount of data (in GB) downloaded per month. |
| **Unlimited Data Plan** | Indicates if the customer has an unlimited data plan (Yes/No). |
| **Extra Data Charges** | Additional charges incurred for data usage beyond the plan. |
| **State** | The U.S. state where the customer resides (abbreviated). |
| **Phone Number** | The customer's phone number. |
| **Gender** | The customer's gender (Male/Female/Prefer not to say). |
| **Age** | The customer's age. |
| **Under 30** | Indicates if the customer is under 30 years old (Yes/No). |
| **Senior** | Indicates if the customer is a senior citizen (Yes/No). |
| **Group** | Indicates if the customer is part of a group account (Yes/No). |
| **Number of Customers in Group** | The number of customers in the group (if applicable). |
| **Device Protection & Online Backup** | Indicates if the customer has device protection or online backup services (Yes/No). |
| **Contract Type** | The type of contract (Month-to-Month, One Year, Two Year). |
| **Payment Method** | The customer's preferred payment method (e.g., Direct Debit, Credit Card, Paper Check). |
| **Monthly Charge** | The monthly amount charged to the customer. |
| **Total Charges** | The total amount the customer has paid over their entire account lifetime. |
| **Churn Category** | The broader category explaining why the customer churned (e.g., Competitor, Attitude, Price). |
| **Churn Reason** | The specific, detailed reason for the customer's churn (e.g., "Competitor made better offer"). |
