# Finance-Sector-Customer-Churn-Analysis

This Power BI report aims to analyze customer churn in the banking industry. It explores various factors contributing to customer attrition, providing actionable insights for businesses to retain their customers. The report contains visualizations and insights based on historical customer data to understand churn patterns and potential areas of improvement in customer retention strategies.


# Data Dictionary

•	RowNumber—corresponds to the record (row) number and has no effect on the output.

•	CustomerId—contains random values and has no effect on customer leaving the bank.

•	Surname—the surname of a customer has no impact on their decision to leave the bank.

•	CreditScore—can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.

## Credit score:
•	Excellent: 800–850

•	Very Good: 740–799

•	Good: 670–739

•	Fair: 580–669

•	Poor: 300–579

## Dimension Data
•	Geography—a customer’s location can affect their decision to leave the bank.

•	Gender—it’s interesting to explore whether gender plays a role in a customer leaving the bank.

•	Age—this is certainly relevant, since older customers are less likely to leave their bank than younger ones.

•	Tenure—refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.

o	Balance—also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.

o	NumOfProducts—refers to the number of products that a customer has purchased through the bank. 

o	HasCrCard—denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.

•	1 represents credit card holder

•	0 represents non credit card holder

o	IsActiveMember—active customers are less likely to leave the bank.

•	1 represents Active Member

•	0 represents Inactive Member

o	Estimated Salary—as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.

o	Exited—whether or not the customer left the bank.

  0 represents Retain 
  
  1 represents Exit
  
o	Bank DOJ — date when the Customer associated/joined  with the bank.


# Data Gathering:

Please use the following data assets to pull the data related to Bank customer and associated details.

o	ActiveCustomer 

o	Bank_Churn

o	CreditCard

o	CustomerInfo

o	ExitCustomer

o	Gender

o	Geography

