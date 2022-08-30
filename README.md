# Data-Engineering-Capstone-Project
Overview
This Capstone Project requires learners to work with the following technologies to manage an ETL process for a Loan Application dataset and a Credit Card dataset: Python (Pandas, advanced modules e.g., Matplotlib), MariaDB, Apache Spark (Spark Core, Spark SQL), and Python Visualization and Analytics libraries. Learners will be expected to set up their environments and perform installations on their local machines. 

The Credit Card System database is an independent system developed for managing activities such as registering new customers and approving or canceling requests, etc., using the architecture.
A credit card is issued to users to enact the payment system. It allows the cardholder to access financial services in exchange for the holder's promise to pay for them later. Below are three files that contain the customer’s transaction information and inventories in the credit card information.

--CDW_SAPP_CUSTOMER.JSON: This file has the existing customer details. \
--CDW_SAPP_CREDITCARD.JSON: This file contains all credit card transaction information. \
--CDW_SAPP_BRANCH.JSON: Each branch’s information and details are recorded in this file. 


Business Requirements - ETL
1. Functional Requirements - Load Credit Card Database (SQL)
2. Functional Requirements - Application Front-End
3 - Functional Requirements - Data analysis and Visualization
After data is loaded into the database, users can make changes from the front end, and they can also view data from the front end. Now, the business analyst team wants to analyze and visualize the data according to the below requirements.


Overview of LOAN application Data API
Banks deal in all home loans. They have a presence across all urban, semi-urban, and rural areas. Customers first apply for a home loan; after that, a company will validate the customer's eligibility for a loan.
Banks want to automate the loan eligibility process (in real-time) based on customer details provided while filling out the online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and others. To automate this process, they have the task of identifying the customer segments to those who are eligible for loan amounts so that they can specifically target these customers. Here they have provided a partial dataset.


API Endpoint: https://raw.githubusercontent.com/platformps/LoanDataset/main/loan_data.json
The above URL allows you to access information about loan application information. This dataset has all of the required fields for a loan application. You can access data from a REST API by sending an HTTP request and processing the response.
 
4. Functional Requirements - LOAN Application Dataset

5 - Functional Requirements - Data Analysis and Visualization for Loan Application
After the data is loaded into the database, the business analyst team wants to analyze and visualize the data according to the below requirements.
