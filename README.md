#  ANALYSIS OF WHETHER A CUSTOMER CHURNS OR NOT
## Business Understanding
The company provides telecommunication services to customers which include voice, messaging, data, roaming, news/entertainment. The subscriptions are for internet and messaging, which can be either packages or monthly payments. Customers can opt out any time, and this means the company loses money. The analysis thereof is to predict whether a customer will churn put or not.
- Key Question: Are there any predictable patterns?
## Data Understanding 
The data is from [Kaggle](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset/data). 
Here's a summary of the columns:
- state: The state of the customer.
- account length: The length of the account in days or months.
- area code: The area code of the customer's phone number.
- phone number: The phone number of the customer.
- international plan: Whether the customer has an international plan or not.
- voice mail plan: Whether the customer has a voicemail plan or not.
- number vmail messages: The number of voicemail messages the customer has.
- total day minutes: Total minutes of day calls.
- total day calls: Total number of day calls.
- total day charge: Total charge for the day calls.
- total eve minutes: Total minutes of evening calls.
- total eve calls: Total number of evening calls.
- total eve charge: Total charge for the evening calls.
- total night minutes: Total minutes of night calls.
- total night calls: Total number of night calls.
- total night charge: Total charge for the night calls.
- total intl minutes: Total minutes of international calls.
- total intl calls: Total number of international calls.
- total intl charge: Total charge for the international calls.
- customer service calls: Number of times the customer called customer service.
- churn: Whether the customer churned or not (True/False).

## Visualizations
### Relationship between churning out and international plan
![image](https://github.com/user-attachments/assets/675e92c7-9390-4c3d-b8d1-57bf99d8dea8)

From the graph, customers with an international plan, are more likely to stay than those without.
### Relationship between number of calls and time of day plus international
![image](https://github.com/user-attachments/assets/60f4b331-b215-42ad-9a7d-ab9052b95ffc)

### Relationship between charges and time of day
![image](https://github.com/user-attachments/assets/452d6d97-4fff-4fbe-aa2c-782d88688dba)

### Relationship between minutes and time of day
![image](https://github.com/user-attachments/assets/c12d0c4e-64c2-4e5f-b02e-587bba0118cb)

## Modeling
### 1. Logistic Regression
Logistic regression scores:
- Precision: 0.5806451612903226
- Recall: 0.1782178217821782
- f1 score: 0.2727272727272727
- Accuracy: 0.856071964017991
- AUC: 0.8331875590385894

- Confusion matrix:
  
  ![image](https://github.com/user-attachments/assets/f2a33ab1-6d09-4afa-8e3b-cc0168e6fe8e)

### 2. Decision Tree 
Decision tree scores:
- Precision: 0.6788990825688074
- Recall: 0.7326732673267327
- f1 score: 0.7047619047619047
- Accuracy: 0.9070464767616192

- Confusion matrix:
  
  ![image](https://github.com/user-attachments/assets/738a0dcb-f357-48b0-a4ce-a50a6033dbe9)

## Recommendations
From EDA and modeling, these are the recommendations:
- Reduce day charges to lure more customers, since a lot of calls are being during the day.
- Another alternative to day charges would be to have offers from the normal charges once in a while to  encourage more day calls.
- Improve customer service. If customers make less calls to customer service department, they'll feel less frustrated, and encouraged to stay.






