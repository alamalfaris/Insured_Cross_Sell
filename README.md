# Insurance Cross Selling Prediction
![Image of CrossSell](https://github.com/alamalfaris/Insured_Cross_Sell/blob/main/img_cross.jpg)

## Background:
> Just like medical insurance, there is vehicle insurance where every year customer needs to pay a premium of certain amount to insurance provider company so that in case of unfortunate accident by the vehicle, the insurance provider company will provide a compensation (called ‘sum assured’) to the customer. Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.

## The goal is:
> Build machine learning to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.

## Table of Content:
1. Import Data
2. Describe Data
3. Exploratory Data Analysis
4. Feature Engineering
5. Feature Selection
6. Splitting Data
7. Base Model
8. Evaluation Matrix Base Model
9. Improvement Data
10. Improvement Model

## About Dataset
* We get the dataset from kaggle : https://www.kaggle.com/anmolkumar/health-insurance-cross-sell-prediction
### Feature Descriptions
- id: Unique ID for the customer
- Gender: Gender of the customer
- Age: Age of the customer
- Driving_License: 0 : Customer does not have DL, 1 : Customer already has DL
- Region_Code: Unique code for the region of the customer
- Previously_Insured: 1 : Customer already has Vehicle Insurance, 0 : Customer doesn't have Vehicle Insurance
- Vehicle_Age: Age of the Vehicle
- Vehicle_Damage: 1 : Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past.
- Annual_Premium: The amount customer needs to pay as premium in the year
- PolicySalesChannel: Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.
- Vintage: Number of Days, Customer has been associated with the company
- Response: 1 : Customer is interested, 0 : Customer is not interested

## Algorithm
We use 3 algorithms in this notebook:
1. Logistic Regression
2. KNearestNeighbors
3. Random Forest

## EDA-Conclusion
No ones interested with vehicle insurance when they already have it
Adult more interested than elderly
Adult male more interested than adult female
Elderly male more interested than elderly female
Who interested with vehicle insurance mostly who have vehicle 1-2 years old
Who interested with vehicle insurance mostly who have got vehicle damage
Who interested with vehicle insurance mostly who have annual premium above median

## EDA-Recommendation
We can more offer vehicle insurance to health insurance owner who doesn't have vehicle insurance before. Because no ones interested with vehicle insurance when they already have it
We can more offer vehicle insurance to adult. Because adult more interested than elderly
We can more offer vehicle insurance to adult male. Because they are more interested than adult female
We can more offer vehicle insurance to they who have vehicle 1-2 years old
We can more offer vehicle insurance to they who have annual premium above median
We can more offer vehicle insurance to they have got vehicle damage
