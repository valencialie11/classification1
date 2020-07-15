# Classification 1: Logistic regression and k-Nearest-Neighbour model

The dataset is used to predict a customer's choice of churning or not based on the following parameters.

## Parameters:

* CustomerID: Customer ID
* Gender: Whether the customer is a male or a female
* SeniorCitizen: Whether the customer is a senior citizen or not (1, 0)
* Partner: Whether the customer has a partner or not (Yes, No)
* Dependents: Whether the customer has dependents or not (Yes, No)
* Tenure: Number of months the customer has stayed with the company
* MultipleLines: Whether the customer has multiple lines or not (Yes, No, No phone service)
* OnlineSecurity: Whether the customer has online security or not 
* OnlineBackup: Whether the customer has online backup or not 
* DeviceProtection: Whether the customer has device protection or not 
* TechSupport: Whether the customer has tech support or not 
* StreamingTV: Whether the customer has streaming TV or not
* StreamingMovies: Whether the customer has streaming movies or not
* Contract: The contract term of the customer (Month-to-month, One year, Two year)
* PaperlessBilling: Whether the customer has paperless billing or not (Yes, No)
* PaymentMethod: The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
* MonthlyCharges: The amount charged to the customer monthly
* TotalCharges: The total amount charged to the customer
* Churn: Whether the customer churned or not (Yes or No)

## Dependencies:
- tidyverse
- rsample
- gtools
- class
- car
- caret

In this report, I have also compared between logistic regression model and kNN model and decide which model is more suitable for this particular dataset to predict future data.


