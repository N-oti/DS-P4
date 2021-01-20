# Starbucks Capstone Challenge


### Motivation

This project is part of Udacity Data Scientist Nanoodegree , and the given dataset contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.
In this project , I'll build a model to predict how the customer will respond to a given offer based on demographics and offer type.

### Installation

This project written in pyathon and followig libraries need to be installed:

1. Panda
2. Numpy
3. sklearn
4. json
5. math
6. matplotlib
7. seborn



### Datasets:

Datasets available in data folder and include the below files:

#### 1. portfolio.json:
containing below columns:
id (string) - offer id
offer_type (string) - type of offer ie BOGO, discount, informational
difficulty (int) - minimum required spend to complete an offer
reward (int) - reward given for completing an offer
duration (int) - time for offer to be open, in days
channels (list of strings)

#### 2. profile.json:
 demographic data for each customer containing below columns:
 profile.json
 age (int) - age of the customer
 became_member_on (int) - date when customer created an app account
 gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
 id (str) - customer id
 income (float) - customer's income


#### 3.transcript.json:
records for transactions, offers received, offers viewed, and offers completed. Containing below columns:
event (str) - record description (ie transaction, offer received, offer viewed, etc.)
person (str) - customer id
time (int) - time in hours since start of test. The data begins at time t=0
value - (dict of strings) - either an offer id or transaction amount depending on the record


### Result
All my finding is available in the following blog: https://n-oti.medium.com/starbucks-capstone-challenge-e678da6b0302

### License & Acknowledgements :

This is completed as part of Udacity Data Scientist Nanoodegree. templates and data were provided by Udacity.
