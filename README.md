# **Machine Learning in Finance**

This repository includes several independent projects involving applications of Machine Learning in various areas of Finance. A brief description of particular projects is provided below.

### **Credit Scoring Model [under development]**

The project involves the most typical classification problem in banking - prediction of whether a client defaults if granted a loan, based on his current financial characteristics and past behavior. The project is still being developed.

The following files are related to this project:
- [Credit_Scoring_Model.ipynb](/Credit_Scoring_Model.ipynb) - Jupyter notebook containing all the codes

### **Term Deposit Subscription Propensity Model**

The aim of this project is to analyze a dataset related to the marketing campaigns run by a bank. In order to perform this exercise, 3 classification models are developed to predict whether a given client has subscribed a term deposit or not. The quality of the models is evaluated, and analysis of the impact of particular variables on the target variable is conducted. Insight gained from this exercise may help develop marketing campaigns by optimizing clients targeting actions (and possibly their form), helping to choose clients that are most probable to subscribe a term deposit when targeted, thus decreasing advertising costs. The report is prepared in R.

The following files are related to this project:
- [Bank_Marketing_Report.Rmd](/Bank_Marketing_Report.Rmd) - R code generating the output
- [Bank_Marketing_Report.html](/Bank_Marketing_Report.html) - a notebook in HTML generated based on the above code; it can be downloaded and opened to see the output without running the code

### **Prediction of Deal Outcome in a Quote-Driven Market**

This project presents an analysis of the data concerning offers made by a broker-dealer to different clients and their outcome. It includes midprice of a given security, ID of a client making inquiry, indication whether he intends to buy or sell, price offered by a broker-dealer, and the outcome of the deal (whether it was accepted or not).

First, two classification models are developed for each client - Logistic Regression and Linear Support Vector Machine (SVM). The data is divided into the training set and test set. The models are trained on the former, and their performance is assessed on the latter.

Next, clustering using k-means algorithm is applied on the data in order to classify the clients based on their propensity to accept or refuse the deal depending on the offered bid-ask spread.

The following files are related to this project:
- [Analysis_of_the_Broker-Dealer's_Trading_Dataset.ipynb](/Analysis_of_the_Broker-Dealer's_Trading_Dataset.ipynb) - Jupyter notebook containing all the codes
- [trading_data.csv](/trading_data.csv) - the dataset used for the analysis
