# AutoML

AutoML Marketting Campaign
In this assignment, you will an AutoML library like H2O.ai to create predictive models and interpret them. Find a significant relation for each algorithm of your choosing in your data. Create multivariate models.

For the moment you will assume the data is good. In future assignments, you will check your data, fix data issues and do some feature engineering.

About Dataset - Marketing Campaign
Dataset Link - https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign

# Context

This task focuses on leveraging automated machine learning (AutoML) through platforms like H2O.ai to optimize a marketing campaign. The primary goal is to construct predictive models that identify individuals likely to respond positively to offers, thereby increasing campaign efficiency. The dataset in question contains a range of customer attributes, including campaign responses, demographics, and purchasing behavior. The tasks encompass essential aspects such as assessing model significance, checking for assumptions and multicollinearity, and fine-tuning hyperparameters. Additionally, the assignment emphasizes the importance of code professionalism for a comprehensive and reliable analysis. Overall, this assignment provides a structured approach to extracting actionable insights from the marketing campaign data, ultimately aiming to enhance the campaign's overall performance and effectiveness.

# Content

AcceptedCmp1 - 1 if customer accepted the offer in the 1st campaign, 0 otherwise
AcceptedCmp2 - 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
AcceptedCmp3 - 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
AcceptedCmp4 - 1 if customer accepted the offer in the 4th campaign, 0 otherwise
AcceptedCmp5 - 1 if customer accepted the offer in the 5th campaign, 0 otherwise
Response (target) - 1 if customer accepted the offer in the last campaign, 0 otherwise
Complain - 1 if customer complained in the last 2 years
DtCustomer - date of customer’s enrolment with the company
Education - customer’s level of education
Marital - customer’s marital status
Kidhome - number of small children in customer’s household
Teenhome - number of teenagers in customer’s household
Income - customer’s yearly household income
MntFishProducts - amount spent on fish products in the last 2 years
MntMeatProducts - amount spent on meat products in the last 2 years
MntFruits - amount spent on fruits products in the last 2 years
MntSweetProducts - amount spent on sweet products in the last 2 years
MntWines - amount spent on wine products in the last 2 years
MntGoldProds - amount spent on gold products in the last 2 years
NumDealsPurchases - number of purchases made with discount
NumCatalogPurchases - number of purchases made using catalogue
NumStorePurchases - number of purchases made directly in stores
NumWebPurchases - number of purchases made through company’s web site
NumWebVisitsMonth - number of visits to company’s web site in the last month
Recency - number of days since the last purchase
Answer the following questions for all of the models:

Is the relationship significant?

Are any model assumptions violated?

Is there any multicollinearity in the model?

In the multivariate models are predictor variables independent of all the other predictor variables?

In in multivariate models rank the most significant predictor variables and exclude insignificant ones from the model.

Does the model make sense?

Does regularization help?

Which independent variables are significant?

Which hyperparameters are important?

Coding professionalism?

# Abstract

The dataset comprises intricate customer-specific information encompassing crucial details such as age, income, and extensive shopping behavior indicators like expenditure patterns, frequency of website visits, and more. The principal objective of this study is to ascertain the likelihood of a customer responding positively to a marketing campaign. Employing state-of-the-art Automated Machine Learning (AutoML) techniques, our aim is to ascertain the most effective classification model for this purpose. Furthermore, we plan to implement regularization methodologies to assess potential enhancements in model performance. Hyperparameter tuning will also be conducted to ensure optimal model configuration. Additionally, a comprehensive exploration of multivariate models will be carried out to discern intricate relationships among variables, validating the models' logical coherence. This study encapsulates a rigorous analytical approach towards discerning patterns within customer data to bolster the efficiency and efficacy of marketing campaigns.
