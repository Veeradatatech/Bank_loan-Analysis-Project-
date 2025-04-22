# 📊 Bank_loan Analysis (2018-2024)

# 📝 Project Overview
  This project involves the analysis of a dataset containing 1 million rows of bank loan data, across the years 2018-2024. This data is to understand customer loan behavior, specifically looking at loan distribution across different seasons and the types of collateral used. The analysis aims to provide insights deep-dive into loan patterns, risk assessment, and potential business strategies related to loan offerings.

# 📦 Dataset Details
  The dataset **Bank_loan** used for this project was generated and structured using **ChatGPT** to simulate real-world banking scenarios, which **Bank_loan** dataset contains 1M rows of synthetic data representing loan details about customer.

* **Source** : Chatgpt (attached with this file)

* **Volume** : 1M rows with 12 columns

* **Format** : CSV

* **Key Fields** :
Here's a brief description of the columns in the dataset:
                
  •	**Customer_Id**: Unique identifier for each customer.
               
  •	**Officer_Id**: The bank officer responsible for the loan given to the customer.
                
  •	**Loan_Amount**: The principal amount of the loan.
                
  •	**Interest_Rate**: The interest rate applied to the loan.
                
  •	**Term_Months**: The duration of the loan (e.g., 12, 36, 48 in months).
                
  •	**Start_Date**: The date when the loan was issued.
                
  •	**Status**: The current status of the loan (e.g., closed, approved, pending, rejected).
                
  •	**Loan_Type**: The type of loan (e.g., personal, mortgage, auto).
                
  •	**Payment_Frequency**: The loan payment amount paid by the customer (e.g., Quarterly, Monthly).
                
  •	**Collateral**: The asset used to secure the loan (e.g., house, car).
                
  •	**Application_Channel**: The loan application applied by customer through medium. (e.g., agent, mobile app, online).
                
  •	**Region**: The geographical region of the customer.

     <img width="1276" alt="Frame 10" src="https://github.com/user-attachments/assets/6d5c1834-39e6-4b1b-9b03-0c9e9cde026b" />


# 🔍 Deep-Dive Insights

  This report provides an in-depth analysis of our loan performance, ideal customer profile, and regional performance. By integrating these insights, we can pinpoint areas of success and identify regions requiring targeted improvements.
  
  Across the years 2018 to 2024, customers bought a total loan amount of $25.49 billion from the bank, representing an average loan amount of $26,000 with a 6% average interest rate.

**📈 Sum of Loan Amount by Year:**

**Insights:** . 

* Loan disbursements remained consistently high (~$4 billion/year) stable lending performance (2018–2023).

* Indicates strong credit demand and well-functioning lending operations.

* Loan amount in 2024 dropped by over 70% compared to prior years.

* Partial year data (e.g., only Jan–Mar)

**Action:** 

* Continue to handle increased demand and to achieve target high.

* Compare approval vs. rejection rates in 2024 vs. previous years.

     ![6](https://github.com/user-attachments/assets/4c05fd5c-8263-45c1-a108-05ab751b83e8)

**📈 Sum of Loan Amount by Region:**

**Insights:**

  * All regions are performing closely in terms of total loan disbursement (Range: $6.36bn – $6.39bn).

  * Indicates well-balanced regional lending across the country.

  * Loan amount by regoins:

    **North**: A loan amount totaling $6.36 billion was bought by customers from the bank in this northern region.

    **South**: A loan amount totaling $6.37 billion was bought by customers from the bank in this southern region.

    **West** : A loan amount totaling $6.39 billion was bought by customers from the bank in this western region.

    **East** : A loan amount totaling $6.37 billion was bought by customers from the bank in this eastern region.

**Action:** 

Analyze by region :

 * Approval rates
   
 * Customer demographics

 * Loan types and collateral preferences

     ![4](https://github.com/user-attachments/assets/ee4cc001-5b4b-4f22-a928-537cc182a6ef)

**✅ Balanced Distribution Across Loan Types**

**Insights:**

  * All loan types (auto, business, education, mortgage, personal) shows very similar total loan amounts (range: $5.08bn–$5.12bn).

  * Average Interest rate is 6% across all loan types except education.

  * Highest approval percentage (25.09%) and only category with a slightly higher average interest rate (6%).

**Action:**

  * Revisit collateral or document requirements

  * Analyze rejection reasons by loan type

     ![1](https://github.com/user-attachments/assets/3bb1614a-3339-4d90-a717-57e642d113d1)

# 🧠 SQL Concepts You Used

**📊 Data Exploration & Aggregation** : COUNT(*), SUM(), AVG(), MIN(), MAX(), GROUP BY, HAVING, ORDER BY, LIMIT

**📝 Windows Functions** : RANK(), DENSE_RANK(), PERCENT_RANK(), LAG(), SUM() OVER

**📝 CTEs (Common Table Expressions)** : WITH .... AS ()

**💾 Stored Procedures** : 

* Reusable blocks for region, Payment_frequency, status, and loan-type-based summaries

* Helps in data extraction to store what we want

**🧩 Views** :

* Created reusable datasets: North, quarterly, unsecured

* Clean way to isolate and reuse filtered data subsets

**🚀 Indexing** :

* Indexed on application_channel to optimize filtering

# 🛠 Tools:

**MS Excel** : For Data Cleaning
 
 **MySQL**   : For Data Modeling, Transformation, Complex Querying and Analysis of bank loan.

**Power BI**`: For Data visualization









