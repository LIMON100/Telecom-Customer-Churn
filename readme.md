# Customer Chrun

**Problem Statement**

You have a telecom firm which has collected data of all its customers" The main types of attributes are : 

1.Demographics (age, gender etc.) 

2.Services availed (internet packs purchased, special offers etc) 

3.Expenses (amount of recharge done per month etc.) 

Based on all this past information, you want to build a model which will predict whether a particular customer will churn or not. So the variable of interest, i.e. the target variable here is ‘Churn’ which will tell us whether or not a particular customer has churned. It is a binary variable 1 means that the customer has churned and 0 means the customer has not churned. With 21 predictor variables we need to predict whether a particular customer will switch to another telecom provider or not.




**Dataset**
Dataset is provided here,also you can find it kaggle.
[https://www.kaggle.com/dileep070/logisticregression-telecomcustomer-churmprediction]





**Preprocessing**

- Convert binary categorical to 0 and 1
- Convert categorical features to Dummy_variables
- Checking outliers.
- Feature Standardization






**Model Buiding**

- Only use Logistice Regression
- Drop some columns by checking them using VIF
- Use RFE method







**Visualize**
- Plot ROC curve
- Find the cutoff point
