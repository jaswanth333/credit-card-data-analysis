# credit-card-data-analysis

# Introduction

Banking sector is one of the important sectors in financial paradigm as it plays an important role in our everyday life and in achieving economic growth.The number of customers closing their credit account is a concerning issue to banks as it affects their business and impacts overall profitability.Hence it is important for them to find effective ways to retain existing customers and prevent them from closing their accounts.The goal of this analysis to identify the key factors that are driving the customers to close their accounts,predict the likelihood of them and provide recommendations to prevent it from happening in the future.    

# Key Findings

Some of the key findings from my analysis reveal that majority of account closures are happening among the customers with an age group between 35 to 55.It is also worth noticing that these are the age groups with more active accounts.When it comes to the employment status,48.5% of customers who close their accounts are working part-time followed by full-time employees with 41% despite having 60% and 20% of active accounts respectively.The median income of these people is around 40,000 to 50,000 USD and is not explaining anything related to the customer status.The same applies to customers with different marital status customers.While the spending ratio of two different customers is around 0.7 ;the transaction ratio of customers who are closing their account is 0.18 lower than that of active customers(0.75).The total transactions of closed account customers are at 43 while this number is 71 for active users.It is surprising to observe that the number of dependents doesn't seem to have any effect on the status of the customer.Finally the type of credit which a customer uses clearly distinguishes the active accounts from the closed ones. 58% of account closures are from blue cards users followed by gold card and silver card users with 32.9% and 25.3% respectively.Finally,the total number of blue cards customers constitute about 70% of overall closed accounts.

# Best Classification Model
In order to predict the likelihood of account closures, models such as Logistic Regression,KNN and Random Forest models has been implemented.Among these three models,Random Forest model performed so well on the unforeseen data.This model was able to predict the a customer will close his/her account 93.8% of the time leaving an error rate of 7.2%.It is also capable of distinguishing active and closed account customers 98.5% of time while the other models were struggling at 94% and 93% respectively.The model also tells that total amount spend last year,total transactions,transaction ratio,utilization ratio and spend ratio are the important variables in determining the target customer status.

# Recommendations

Based on the results from my analysis I would recommend bank executives to consider following steps in order to reduce the number of customers from closing their credit card accounts.Since,customers between ages 35-55 are more prone to close their accounts the bank officials should target these groups by understanding their problems through continuous feedback.Since,there is 90% of account closures are from  full-time and part-time customers ,there is a high possibility that they are dissatisfied with the banking functions such as delay in payroll processing/check deposits etc.To overcome this, the bank account should frequency reach out to them through telephonic surveys with proper questionnaires.Since majority of account closures are from blue cards users when compared to other card holders they should work on them credit card offers in the form of discounts and cash backs.The banks should periodically track the customer transaction and spending ratio and observe abnormalities in the banking activity.Based on the predictions obtained from the model,the banks should focus on the customers who are likely to close their accounts and work on them by re-engineering their sales, service, and marketing strategies.If the banks were able to successfully work on all these recommendations they can improve their customer retention and overall brand reputation.