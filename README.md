# Datakliq-capstone
Datakliq Cohort 3 project 
![](65e221d80e47f1b6a163bb9aba3ac62c.jpg)

---
## Introduction 
The ATM, an Automated Teller Machine, stands as a cornerstone of modern banking, serving as a vital link between customers and their finances.
These self-service kiosks allow 24/7 access to basic banking functions like withdrawals, deposits, and transfers, empowering customers with flexibility and immediacy.
By offering convenience at any hour and location, ATMs cater to customers’ immediate needs, delivering a crucial touchpoint for efficient transactions.
This accessibility and ease of use not only satisfy customers’ demands for convenience but also solidify their loyalty, playing a pivotal role in retaining a satisfied clientele within the dynamic landscape of financial services.

## Objective
This project aims to:
- Uncover valuable insights to enhance understanding of customer behavior.
- Enhance operational efficiency.
- Foster enduring customer relationships as the ultimate goal.

---

## Tools used
In this project, SQL (PostgreSQL) will be utilized for dataset cleaning purposes. Additionally, Microsoft Power BI will serve as the primary tool for data analysis and visualization.

---

## Dataset Description
This dataset is Datakliq Cohort 3 project dataset, obtained from the datakliq_education_hub.
It contains seven dimension tables (hour table, Calendar table, ATM Location table, Customers table, ATM Maintenance table) all of which are in CSV format, and a Fact table that is a union of Five different States (Lagos State, Enugu State, Federal Capital Territory, Kano State, Rivers State) Transaction records.

---

## Data Transformation
During the analysis phase, SQL (PostgreSQL) was employed for the process phase. Microsoft Power BI, on the other hand, was used for the Analyze and visualization phases.

For the process phase, the initial step involved importing the CSV file into PostgreSQL. Subsequently, columns were modified to fit appropriate data types. Null values within columns of Numeric data types were replaced with "0". Additionally, a Calendar table was established, and the transaction records from the five states were merged to form a unified Transaction table.
The removal of duplicates was executed using the "Select Duplicates" functionality.

---

## Data Modelling
The clean tables from the postgresql were uploaded to Microsoft Power Bi through the import mode. The tables were linked together through Snowflake Modelling. The relationship established between the tables is the "one-to-many" relationship. When it is taking a long period of time to analyze and visualize data, I switch to direct query mode. 

---

