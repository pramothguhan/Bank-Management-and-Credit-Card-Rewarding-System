## Bank Management and Credit Card Rewarding System :credit_card:

## Overview :memo:

This project involves the development of an integrated Bank Management and Credit Card Rewarding System designed to address the challenges faced by financial institutions in managing operations and enhancing customer loyalty. By standardizing processes and leveraging data-driven insights, the system streamlines banking operations while offering personalized customer experiences through a tailored credit card reward system.

## Project Highlights :sparkles:

- **Integrated Banking Operations:** The system connects essential banking entities such as Accounts, Transactions, Credit Cards, Loans, Employees, and Customers, creating a seamless banking experience that enhances operational efficiency.
  
- **Credit Card Rewarding System:** This feature incentivizes customer engagement and loyalty by offering rewards and benefits based on customer behaviors and transactions. The system tracks these interactions to provide personalized reward offerings, strengthening customer relationships with the bank.

- **Flexibility and Adaptability:** The system is designed to support various functionalities, including managing customer-branch relationships, loan-branch associations, employee-branch affiliations, and credit card-merchant interactions. This adaptability ensures the system meets the diverse needs of the banking sector.

## Technologies Used :computer:

[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-FCA121?style=for-the-badge&logo=python&logoColor=white)](https://www.sqlalchemy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-FF69B4?style=for-the-badge&logo=python&logoColor=white)](https://matplotlib.org/)

## Conceptual Data Modeling :bar_chart:

### 1. Enhanced Entity-Relationship (EER) Diagram:
The EER diagram provides a visual representation of the system's entities and their relationships, ensuring a clear understanding of the data structure.

### 2. UML Diagram:
The UML diagram illustrates the system's architecture, showing the interactions between different components and the flow of data.

## Implementation :hammer_and_wrench:

### Relational Model in MySQL:
- **Branch Management:** The `BRANCH` table manages branch details, including address, email, and phone number.
- **Account Management:** The `ACCOUNT` table stores information about customer accounts, including balance, type, and associated branch.
- **Employee Management:** The `EMPLOYEE` table records employee details, including salary, email, and branch affiliation.
- **Customer Management:** The `CUSTOMER` table tracks customer information, including income, contact details, and associated branch.
- **Transaction Management:** The `TRANSACTION` table logs customer transactions, including amount, time, and status.
- **Loan Management:** The `LOAN` table manages loan details, including type, amount, duration, and associated branch and customer.
- **Credit Card Management:** The `CREDIT CARD` table tracks credit card details, including limit, balance, and associated customer.
- **Reward Management:** The `REWARD` table manages reward details, including amount, request date, and associated customer.
- **Merchant Management:** The `MERCHANT` table tracks merchant details, including category, associated branch, and reward program.

### NoSQL Implementation:
- **Customer Account Retrieval:** Query to retrieve customer account details from MongoDB.
- **Employee Salary Aggregation:** Aggregation query to calculate average employee salary in MongoDB.
- **Loan Sorting:** Query to sort loans by amount and duration in MongoDB.

### Database Access via Python:
- The MySQL database is accessed using Python's `SQLAlchemy`, with data analysis and visualization performed using `Matplotlib`.

## Visualizations :chart_with_upwards_trend:

1. **Pie Chart of Account Types:** Displays the distribution of different account types.
2. **Boxplot of Loan Amounts:** Illustrates the distribution of loan amounts across different branches.
3. **Histogram of Customer Incomes:** Shows the income distribution among customers.

## Conclusion :checkered_flag:

The Bank Management and Credit Card Rewarding System represents a significant advancement in the banking industry, providing a streamlined, data-driven approach to managing banking operations and enhancing customer engagement. The integration of various banking entities into a cohesive system allows for better management of customer relationships and operational efficiency. The Credit Card Rewarding System, in particular, sets a new standard for fostering customer loyalty and satisfaction.
