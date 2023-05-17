
![image](./pic/sales.jpeg)
# Store-Sales-Time-Series-Forecasting ✨


## Introduction
This is a machine learning regression problem. In this project, I will build a model that more accurately  predicts the unit sales for thousands of items sold at different Favorita stores.

Corporation Favorita is a large Ecuadorian-based grocery retailer.

## File Descriptions and Data Field Information

train.csv

* The training data, comprising time series of features store_nbr, family, and onpromotion as well as the target sales.

* **store_nbr** identifies the store at which the products are sold.

* **family** identifies the type of product sold.

* **sales** gives the total sales for a product family at a particular store at a given date. Fractional values are possible since products can be sold in fractional units (1.5 kg of cheese, for instance, as opposed to 1 bag of chips).

* **onpromotion** gives the total number of items in a product family that were being promoted at a store at a given date.

test.csv

* The test data, having the same features as the training data. You will predict the target sales for the dates in this file.

* The dates in the test data are for the 15 days after the last date in the training data.

transaction.csv

* Contains date, store_nbr and transaction made on that specific date.

sample_submission.csv

* A sample submission file in the correct format.

stores.csv

* Store metadata, including city, state, type, and cluster.

* cluster is a grouping of similar stores.

oil.csv

* **Daily oil price** which includes values during both the train and test data timeframes. (Ecuador is an oil-dependent country and its economical health is highly vulnerable to shocks in oil prices.)

holidays_events.csv

* Holidays and Events, with metadata

## Additional Notes

A magnitude 7.8 earthquake struck Ecuador on April 16, 2016. People rallied in relief efforts donating water and other first need products which greatly affected supermarket sales for several weeks after the earthquake.


## Hypothesis
Null hypothesis: Sales are affected by promotions, oil prices and holidays.

## Conclusion 
The analysis showed that sales are affected by items on promotion and oil prices. We can accept the null hypothesis that sales are affected by items on promotion and oil prices. 

Kindly find attached the link to the part 1 of this project: [Article](https://medium.com/@qacheampong/store-sales-time-series-forecasting-exploratory-data-analysis-part-1-54f245b6edac/)


