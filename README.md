# CUSTOMER CHURN ANALYSIS PREDICTION MODEL
## Project Overview
In the fast paced industry of Telecommunication, customer retention is key if one is to be considered a market player. Telecommunication companies often grapple with customer switch due to the competitive nature of the industry. This project aims at equipping Telecommunication industry with an effective classifier model to predict customer churn and ultimately improve customer retention while increasing profitability.

### Business Problem

SyriaTel , a Telecommunication company has been experiencing customer churn which has led to decrease in market share resulting in losses. This study seeks to analyze quality of service and product plans offered by the Telcom.

**Target Variable**

churn: whether a customer switches to another company or remains in the company.

**Product variables**

a. state: Refers to general location where the customer is located

b. account length: Period a customer has been with the company in months

c. area code: area where customer is located

d. phone number: customer's number

e. intl plan: whether client has a package for international calls yes or no

f. voice mail plan: whether client has a package for voice mail service yes or no

g. number vmail message: number of voicemail messages received

h. total day minutes: total minutes used during the day

i. total day calls: total number of calls made during the day

j. total day charge: total billed for day calls

k. total eve calls: number of calls made in the evening

l. total eve charge: total billed for evening calls

m. total night minutes: total number of minutes used at night

n. total night calls: total number of night calls made

o. total night charge: total amount billed at night

p. total intl minutes: total minutes spent on international calls

q. total intl calls: total number of international calls made

r. total intl charge: total billed for international calls

s. customer service calls: no. of calls made to customer service

t. churn: whether customer stayed or left the company yes or no

# **OBJECTIVES**

i.) Identify key factors influencing customer churn

Investigate location-related attributes like area code and geographic coordinates to further understand whether certain areas have poor reception.

ii). Evaluate Model Performance

Utilize metrics such as Accuracy, F1Score, Recall , and mean squared error to assess the model's effectiveness in accurately predicting customer churn.

iii). Provide Actionable Recommendations

Offer practical strategies to Syria Telecom that will enhance customer retention, customer satisafaction, increase profitabilty and ultimately the market share.

# **TABLE OF CONTENT**

1. Data Preparation
2. Data Cleaning
3. Exploratory Data Analysis
4. Modelling
5. Evaluation
6. Conclusion
7. Recommendations

# **MODEL RESULTS**

Gradient Boosting Model was the best model with an accuracy level of 98% and F1score of 98%, indicative of a balanced performance.

# **CONCLUSIONS**

-500 customers are likely to churn based on the univariate analysis.

-In the analysis of area code  against churn, area code 415 has the highest number of customers (250) who are prone to churn.

-Customers who did not make a call to customer care are not likely to churn based on the analysis  between customer service call against churn.

-The Gradient Boosting Model is best placed to predict customer churn due to high accuracy of 98% . F1score of 98%  depicts classifier did well in terms of both precision and recall metrics.


# **RECOMMENDATIONS**

a. Variable enrichment: The dataset could have been enhanced by inclduing additional variables like gender and age to better understand factors influencing customer churn.

b.Network coverage: Syriatel should check on network coverage on area code 415 as it has the highest number of customers likely to churn.

c.Upselling: SyriaTel could try convincing customers to take up extra packages to increase its profitability.

d.Introduction of new products: Syriatel could try reduce churn by introducing new packages not in their company like internet service or loyalty program where customers can earn points for consistent patronage of services already offered.







