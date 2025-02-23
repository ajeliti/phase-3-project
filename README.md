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
## Data preparation
We will do EDA of the data and preprocessing before we get to analyze it.
![image](https://github.com/user-attachments/assets/27cf24c6-01e5-42dc-80a8-803b8627a9cb)
