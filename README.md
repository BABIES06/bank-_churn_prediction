# bank_customer_churn_prediction
This GitHub repository hosts an end-to-end implementation of a Bank Customer Churn Prediction system using classific machine learning techniques. Customer churn, also known as attrition, refers to the phenomenon where customers stop using a service or product provided by a business. In the context of this repository, we focus on predicting churn in
# Problem statement
The primary objective of this project is to develop a predictive model that accurately identifies potential bank customers who are likely to churn in the near future. By leveraging historical customer data and relevant features, the model should provide insights into which customers are at the highest risk of leaving the bank, allowing proactive measures to be taken to retain them.
# Data Description
In this project we have thhe target variable as EXITED ( YES=1,NO=0 ).The dataset consit of 14 columns.The shape is (10000,14)
RowNumber — corresponds to the record (row) number and has no effect on the output. This column will be removed.

CustomerId — contains random values and has no effect on customer leaving the bank. This column will be removed.

Surname — the surname of a customer has no impact on their decision to leave the bank. This column will be removed.

CreditScore — can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.

Geography — a customer’s location can affect their decision to leave the bank. We’ll keep this column.

Gender — it’s interesting to explore whether gender plays a role in a customer leaving the bank. We’ll include this column, too.

Age — this is certainly relevant, since older customers are less likely to leave their bank than younger ones.

Tenure — refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.

Balance — also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.

NumOfProducts — refers to the number of products that a customer has purchased through the bank.

HasCrCard — denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank. (0=No,1=Yes)

IsActiveMember — active customers are less likely to leave the bank, so we’ll keep this. (0=No,1=Yes)

EstimatedSalary — as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.

Exited — whether or not the customer left the bank. This is what we have to predict. (0=No,1=Yes)
# Algorithms
Logistic regression,
Random forest,
Decision Tree Classifier,
knn,
naive bayes,
SVM
# CONCLUSIONS
 From the above machine learning models, we can conclude that Random Forest gives us the highest accuracy.
 
