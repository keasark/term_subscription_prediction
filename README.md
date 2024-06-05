# Machine Learning - Prediction for Term Deposit Subscription

## Team Members:
- Vyshnavi Reddy Mungi
- Poreddy Akshitha
- Xuan Mai Tran
- Maniteja Vemunoori
- Haji Mastan Vali Shaik

## Overview:
- This big project is divided into 8 mini projects implemented throughout the whole semester to help students understand clearly about Machine Learning process and advantages/disadvantages of various Machine Learning models.
- In the final date, we have a final presentation to indicate the conclusions we extracted from the projects and its applications in business, particularly Banking industry.
<div align="center">
<img width="500" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/57cab897-9a11-4afb-b3a5-56baa60ea156">
</div>

## Project Structure:
- Project 1: Select topic and collect dataset
- Project 2: EDA - Data Visualization
- Project 3: Feature Selection
- Project 4: Regression
- Project 5: Decision Tree
- Project 6: KNN and NB graph
- Project 7: SVM
- Project 8: Random Forest & Regularization
- Final Presentation: Conclusion: Insights and Suggestions 

## Introduction:
### Project topic: 
- Term Deposit Subscription

### Machine Learning type: 
- Supvervised - classification

### Banking Industry Context:
- The importance of the banking system is for business activities and citizen life.
- The health of banking system will reflect truly the health ofeconomy.
- Especially there’re news of banks shut down recently.

### Team Role:
- We as a data scientist team cooperate with Marketing department to figure out the valuable insights from the marketing campaign to support for the health of our bank.

### Business Context:
- Stakeholders want to gain insight from the recent marketing campaign to make business decisions.
  
### Business Question:
- Analyzing the marketing campaign to predict customer subscription of a term deposit.
  
### Dataset Info:
Direct marketing campaigns of a Portuguese banking institution
- Collected May 2008 - Nov 2010.
- Includes ~ 40,000 records and 20 attributes which consist 3 types of info: 
    1. bank client data
    2. related data of the marketing campaign
    3. social & economic context
       
### Implementations of ML:
- Data Visualization: to learn about the dataset
- Choose Important Features: Feature Selection
- Testing different algorithms to predict the effect of important features on classification of customer subscription’s decision
  
### Data Description:
- Building a predictive model that, given the above features, can accurately predict whether a term deposit will be subscribed or not. This involves data preprocessing, exploratory data analysis, model training, and evaluation. The dataset we are using captures various financial and personal details that could be used for assessing an individual's eligibility for a term deposit and for financial analysis purposes.
- Depending on the specific goals of the analysis, we can use these attributes to gain insights into the financial profile of individuals and build predictive models for term subscription approval process. This type of predictive modeling is common in the financial sector to automate and streamline the term subscription approval process.
  
### Data Columns:
1. age (numeric)
2. job : type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self￾employed','services','student','technician','unemployed','unknown')
3. marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
4. education (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')
5. default: has credit in default? (categorical: 'no','yes','unknown')
6. housing: has housing loan? (categorical: 'no','yes','unknown')
7. loan: has personal loan? (categorical: 'no','yes','unknown') related with the last contact of the current campaign:
8. contact: contact communication type (categorical: 'cellular','telephone')
9. month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
10. day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
11. duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.
12. campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
13. pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
14. previous: number of contacts performed before this campaign and for this client (numeric)
15. poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')
16. emp.var.rate: employment variation rate - quarterly indicator (numeric)
17. cons.price.idx: consumer price index - monthly indicator (numeric)
18. cons.conf.idx: consumer confidence index - monthly indicator (numeric)
19.  euribor3m: euribor 3 month rate - daily indicator (numeric)
20.   r.employed: number of employees - quarterly indicator (numeric)
21.   y - has the client subscribed a term deposit? (binary: 'yes','no')

## Machine Learning Process:
### Data Visualization:
<div align="center">
<img width="800" alt="1PNG" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/94ac3fe3-f6a5-4b66-9593-3c48183d424d">
<img width="800" alt="2" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/483ab7b2-d9ef-405b-b106-2e9d96750bfa">
<img width="800" alt="3" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/52124d59-536c-49ab-a726-ff310dc82b9d">
</div>

### Feature Selection:
Select the based features based on:
- Univariate method
- RFE
- Feature Importance
- Scatter plotture Selection
<div align="center">
<img width="800" alt="4" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/8b8a9863-23e9-4978-ac35-1c71e7a556bd">
<img width="800" alt="5" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/971eb9eb-7533-4345-8f5c-bc30682aa570">
<img width="800" alt="6" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/76952481-b8f6-4eac-b6e3-6e5f471e6d13">
</div>

### Regression:
<div align="center">
<img width="800" alt="7" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/8de5b95d-f1c5-4c0b-a13f-132d4e1a2cfd">
<img width="800" alt="8" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/0647f874-517f-491c-afdb-44e0dd3a78a1">
<img width="800" alt="10" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/08c8aeda-585f-464f-84e2-fa42526d10ac">
<img width="800" alt="9" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/ad1e6206-fd90-4a05-827d-f0698dd8bc04">
<img width="800" alt="11" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/020c046e-6ee1-4b20-8db1-4f4cb2c66089">
</div>

### Decision Tree:
<div align="center">
<img width="800" alt="12" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/c3eb5bcb-4b88-4816-9487-051a5474c6b2">
<img width="800" alt="13" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/152e4309-1aad-415c-8633-8119abdc32cd">
<img width="800" alt="14" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/6d671a2f-5fa9-4dbc-b8cb-bcd5b09b713d">
</div>

### KNN and Naïve Bayes (NB) Graph:
<div align="center">
<img width="800" alt="15" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/659e1d3e-f4c7-47f3-8826-c541ef99f9ef">
<img width="800" alt="16" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/90a42b32-d096-4f93-84a1-c689ffacb80d">
<img width="800" alt="17" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/3e66576f-05a1-4510-9bd4-a065156ac8f9">
<img width="800" alt="18" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/2d1f8c61-1c7c-4756-819b-c3a77b49c037">
</div>

### Support Vector Machine (SVM):
<div align="center">
<img width="800" alt="19" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/531061f9-d87a-4651-b397-2421432ee35d">
</div>

### Random Forest and Regularization:
<div align="center">
<img width="800" alt="20" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/fffe16e8-b086-493c-9c67-c1507ae11d71">
<img width="800" alt="21" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/2621fef0-0c11-4bc1-8614-2b86510ccee0">
</div>

## Conclusion:
<div align="center">
<img width="800" alt="22" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/395d8de3-2a9e-4ea6-a15b-f0f9aa89b524">
<img width="800" alt="23" src="https://github.com/keasark/term_subscription_prediction/assets/76891395/d8026ee5-1bac-4e41-8a53-71b2adad502d">
</div>

## References:
1. Moro,S., Rita,P., and Cortez,P.. (2012). Bank Marketing. UCI Machine Learning Repository. https://doi.org/10.24432/C5K306.
2. “Bank Marketing - dataset by uci,” data.world. https://data.world/uci/bank-marketing (accessed Feb. 06, 2024).
3. Hou, Sipu, et al. "Applying Machine Learning to the Development of Prediction Models for Bank Deposit Subscription."International Journal of Business Analytics, vol. 9, no. 1, Jan. 2022, pp. 1-12, doi:10.4018/IJBAN.288514

