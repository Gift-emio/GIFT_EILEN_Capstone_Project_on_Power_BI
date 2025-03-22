# GIFT_EILEN_Capstone_Project_on_Power_BI
This is the official repository for my Capstone project on Power BI for the Data Stars Cohort.

Interact with my final dashboard here:

[Churn Analysis Dashboard](https://1drv.ms/u/c/2c52db07c0f2ca61/ERUGxWujRblCjoH3TIrwKm8BkJ25HDgA_pNHf9wdNxWB5g?e=nzYyIp)

## Business Problem
The financial services industry's ecosystem is dynamic and multidimensional, characterized by a complex interplay of factors that influence consumer behaviors. In this complex environment, the ability to retain customers is more than a strategic advantage; it is a requirement for long-term growth and sustainability. The inherent challenges of customer attrition for financial institutions include substantial revenue loss and the erosion of brand loyalty.

As a result, a Canadian bank facing challenges in retaining its customer base reached out to Datafied Technologies. The bank is experiencing customer churn, impacting overall customer satisfaction and revenue, as well as they lack insights into the factors influencing customer decisions to leave or stay with the bank. There is a need to identify and address factors contributing to customer churn proactively and to do that, they provided a churn database containing information on 10,000 bank customers over six months. 

## Dataset Information
The data contains information on 10,000 Canadian bank customers who left or remained with the bank during a six-month period. The attributes are:
- **CustomerId**: Each customer has a specific identification called a CustomerId.

- **Surname**: This serves as the client's last name. It is a categorical variable

- **Credit Score**: This is the customer's credit score, which measures their creditworthiness numerically. Since a customer with a better credit score is less likely to quit the bank, a higher credit score often implies a lower credit risk and can affect customer turnover.
- **Geography**: This feature indicates the country of residence of the customer. 
- **Gender**: This feature represents the gender of the customer and can be either Male or Female. 
- **Age**: The customer's age, in years
- **Tenure**: The number of years that the consumer has been a bank client is shown by this characteristic
- **Balance**: The balance shows how much money is in their bank account.
- **NumOfProducts**: This feature shows how many distinct banking products the client has with the bank. It accepts values between 1 and 4. 
- **HasCrCard**: This variable indicates if the client has a credit card on file with the bank. The binary variable has the values 0 for "No" and 1 for "Yes." 
- **IsActiveMember**: This feature indicates if the consumer is an active bank member. It's a binary variable once more, with 0 denoting "No" and 1 denoting "Yes." 
- **EstimatedSalary**: This field contains data about the client's earnings. 
- **Churned**: This variable tells us whether or not the consumer left (churned). The variable is binary, with 0 denoting "No" (the consumer stayed) and 1 denoting "Yes" (the customer left or "churned"). 

In a bid to get additional outputs, additional columns were created using conditional columns an Replace Values. These columns include Age Categories, Numeric Age Condition, Account Balance Category, Credit Score Category, Numeric Credit Score Category and Numeric Account Balance Category.

[See dataset](https://docs.google.com/spreadsheets/d/1YqrpwWt8W5AZMfsHWMqhxYPjDiL9h2359TyOgqLW2BI/edit?gid=33620971#gid=33620971)

## Project Objective
To leverage Power BI for exploratory data analysis to provide valuable insight as to the factors influencing customer churn based on various demographic and banking behavior attributes.

## Understand Business Objectives and User Requirements
In trying to understand the specific requirements and objectives from the business problem. We identified key areas we want to focus on and the questions the business needs answers to.

## Define Business Questions and Metrics
Based on the discused business problem, we defined specific business questions that the dashboard should answer.

- What is the total number of customers had in 6 months?

- Show me the number of churned customers from each geographical location?

- Give me a report of the number of churned customers and the number of products they have?

- What are the number of churned customers with credit card and those without credit cards?

- Give me the total sum of account balance of all client within the last 6 months?

- What is the total number of active and in-active members?

- What is the total number of customers that stayed and those that left?

- Total number of client with credit card and without credit card?

- What are the credit scores of the customers that left the bank?

- Total number of customers with the highest and the lowest number of product?

- Give me the age range of the customers that left the bank?

## Define the Metrics and Key Performance Indicators (KPIs) that will help answer the business questions.
- Total Customers
  
- Total Churned Customers by Location

- Total Active and In-Active Customers

- Age Range of Churned and Un-Churned Customers
  
- Credit Score of Churned Customers

## Preprocess the Dataset:
The dataset was cleaned by removing duplicates, correcting any inconsistencies, and ensuring the data is in a suitable format for analysis and visualization.

## Dataset Before Cleaning
[View Image](https://github.com/user-attachments/assets/cea8bb91-a6f9-4479-a7ee-d0460e640c45)

## Dataset after cleaning
[View Image 1](https://github.com/user-attachments/assets/0a38ff71-2273-4096-a8d7-7cf71c77146c)

[View Image 2](https://github.com/user-attachments/assets/4247ca0a-4ed6-43fd-bbe2-8725720d1ee0)

[View Image 3](https://github.com/user-attachments/assets/17eef28b-00e7-4824-98ab-22a28d60e01b)  

[View Image 4](https://github.com/user-attachments/assets/35767ca3-b3db-4e93-8a4f-23558d05b1f0)

## Data Modelling and Relationships.
Dimensions with which to break down the analysis were identified. Hence, new tables for identified dimensions were created. These included:
- Customer's Personal Info

- Customer's Bank Info

[View Image](https://github.com/user-attachments/assets/06874726-255d-4aa6-a5f0-4349e78d8628)

## Create Visualizations and Charts:
Appropriate chart types (e.g., Bar charts, Column chart, Area charts, Donut Chart and pie charts) were used to represent the metrics and insights. Interactive features such as filters, slicer options, and tooltips were used for detailed information.

[View Image](https://github.com/user-attachments/assets/43156a08-0412-4bf6-889f-a9d3fa7bc3d8)


## Insights
- On the general analysis on churned customers, it was observed that 20.4% of the total customers were churned within 6 month. This percentage of churned customers is too high for this period of time.

- It was also observed that of the total number of customers within the 6 months period, 48.4% of customers were in-active.

- I also observed that 3,442 customers had a fair credit score with the bank. And the number of customers happens to be the highest in the chart of credit scores. This simply means these customers might have limitations in accessing credit facilities with the bank.

-   The bank had 50.14% of her customers from France, followed by Germany which had 25.09% of customers and lastly, Spain with 24.77% of customers.

-    With the tenure column, it can be safe to assume the bank has been in operations for 10 tenures. It was also observed that there was 49.7% reduction in the number of customers between tenure 9 and tenure 10.

-    Based on the distribution of churned customers by number of products, it was observed that 69.17% (1,409) of total churned customers had just 1 product with the bank. That means the other 3 categories made up the 30.83% of total churned customers.

-    Also based on the distribution of total churned customers by credit score, it was observed that 34.7% of the total churned customers had a fair credit score and that must have impacted their decision on leaving the bank. Cause they might have been experiencing some level of limitations in accessing crdit facilities.

## Recommendation
- I would recommend that the customers be encouraged to get more products with the bank. In doing so, the bank will keep the customers active and unchurned.

- I will recommend that the bank give certain considerations to customers with fair credit scores. Cause in doing so, the customers are being encouraged to stay with the bank. And in the long run, the bank wants to satisfy its customers.

## Deployment and Documentation
Once the dashboard was finalized, it was deployed to Power BI service. The project process and deliverables are documented here on GitHub.

Interact with the final dashboard 👉[here:](https://drive.google.com/drive/folders/17YDcni0YOozr5zQ-gCN6PzArrGayPnsj?usp=drive_link)👈






