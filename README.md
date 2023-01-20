# <center> <font color='red'> Telecom Churn Prediction</font></center>


## Table of Contents
* [General Info](#general-information)
* [Business Goal](#business-goal)
* [Data Dictionary](#data-dictionary)
* [Files](#files)
* [Libraries](#libraries)
* [Observation](#observations)

## General Information
<p>In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate.
Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining high profitable customers is the number one business
goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn. In this project, you will analyze customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn.

In this competition, your goal is to build a machine learning model that is able to predict churning customers based on the features provided for their usage. </p>


## Business Goal
The main goal of the case study is to build ML models to predict churn. The predictive model that you’re going to build will the following purposes:

1. It will be used to predict whether a high-value customer will churn or not, in near future (i.e. churn phase). By knowing this, the company can take action steps such as providing special plans, discounts on recharge etc.
2. It will be used to identify important variables that are strong predictors of churn. These variables may also indicate why customers choose to switch to other networks.
3. Even though overall accuracy will be your primary evaluation metric, you should also mention other metrics like precision, recall, etc. for the different models that can be used for evaluation purposes based on different business objectives. For example, in this problem statement, one business goal can be to build an ML model that identifies customers who'll definitely churn with more accuracy as compared to the ones who'll not churn.
 4. Recommend strategies to manage customer churn based on your observations.

## Data Dictionary:
| Acronyms    | Description                                                                         |
|-------------|-------------------------------------------------------------------------------------|
| CIRCLE_ID   | Telecom circle area to which the customer belongs to                                |
| LOC         | Local calls  within same telecom   circle                                           |
| STD         | STD calls  outside the calling   circle                                             |
| IC          | Incoming calls                                                                      |
| OG          | Outgoing calls                                                                      |
| T2T         | Operator T to T ie within same operator mobile to mobile                            |
| T2M         | Operator T to other operator mobile                                                 |
| T2O         | Operator T to other operator fixed line                                             |
| T2F         | Operator T to fixed lines of T                                                      |
| T2C         | Operator T to its own call center                                                   |
| ARPU        | Average revenue per user                                                            |
| MOU         | Minutes of usage  voice calls                                                       |
| AON         | Age on network  number of days the   customer is using the operator T network       |
| ONNET       | All kind of calls within the same operator network                                  |
| OFFNET      | All kind of calls outside the operator T network                                    |
| ROAM        | Indicates that customer is in roaming zone during the call                          |
| SPL         | Special calls                                                                       |
| ISD         | ISD calls                                                                           |
| RECH        | Recharge                                                                            |
| NUM         | Number                                                                              |
| AMT         | Amount in local currency                                                            |
| MAX         | Maximum                                                                             |
| DATA        | Mobile internet                                                                     |
| 3G          | 3G network                                                                           |
| AV          | Average                                                                             |
| VOL         | Mobile internet usage volume in MB                                                  |
| 2G          | 2G network                                                                           |
| PCK         | Prepaid service schemes called PACKS                                             |
| NIGHT       | Scheme to use during specific night hours only                                      |
| MONTHLY     | Service schemes with validity equivalent to a month                                 |
| SACHET      | Service schemes with validity smaller than a month                                  |
| *.6         | KPI for the month of June                                                           |
| *.7         | KPI for the month of July                                                           |
| *.8         | KPI for the month of August                                                         |
| FB_USER     | Service scheme to avail services of Facebook and similar social   networking sites  |
| VBC         | Volume based cost  when no specific   scheme is not purchased and paid as per usage |


## Files

The repo contains a .zip folder that has three files:
- **train.csv** : This is the main tranining set. 
- **test.csv** : This is unseen data. This will only be used when the model is ready to be exposed.
- **data_dictionary.csv** : This file explains the terminology used in the train and test files.

<font color='red'>*Note*</font>: DO NOT MERGE the train and test data.

## Libraries:

- Pandas
- Numpy
- Matplotlib and Seaborn
- Statsmodels
- Scikit Learn:
    - Simple Imputer
    - Train Test Split
    - StratifiedKFold and GridSearchCV
    - MinMaxScaler
    - Random Forest Classifier
    - XGBoost Classifier
    - Confusion Matrix and Classification Report

## Observations



## Strategies
