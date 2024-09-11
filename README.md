# Ecommerce Customer Churn Prediction

## Overview

This project focuses on developing a robust predictive model to accurately predict customer churn in subscription-based e-commerce platforms, utilising a diverse dataset of 5,630 customers. It examines various features, including customer and warehouse demographics, customer engagement metrics like HourSpendOnApp and NumberofDeviceRegistered, transaction histories such as PreferredPaymentMode and CouponUsed, complaints and satisfaction scores. Furthermore, the project aims to provide actionable insights for proactive retention strategies and decision-making by identifying and evaluating the key drivers of churn and retention. 

![Alt text](Customer_Churn.png)

## Source of Data

The primary dataset used in the project belongs to a leading online e-commerce company and is obtained from [Kaggle](https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction). This dataset provides a comprehensive view of the historical data on how the customers have interacted with the subscription service.  It captures critical variables, including demographic information, transaction history, engagement metrics, and customer satisfaction scores, which are essential for predictive customer churn analysis modelling. 

* CustomerID: A unique identifier for each customer
* Churn: A binary variable indicating whether the customer has churned (1) or not (0)
* Tenure: The number of years the customer has been with the company
* PreferredLoginDevice: The device the customer prefers to use for logging in (e.g., Mobile Phone, Phone, Computer, etc.)
* CityTier: The tier of the city the customer is from (1, 2, or 3)
* WarehouseToHome: The distance in kilometres from the customer’s home to the nearest warehouse
* PreferredPaymentMode: The payment mode the customer prefers to use (e.g., Debit Card, Credit Card, COD, etc.)
* Gender: The gender of the customer (Male or Female)
* HourSpendOnApp: The number of hours the customer spends on the app
* NumberOfDeviceRegistered: The number of devices registered to the customer’s account
* PreferedOrderCat: The category of products the customer prefers to order (e.g., Mobile, Fashion, Laptop & Accessory, etc.)
* SatisfactionScore: The customer’s satisfaction score (1 to 5, with 5 being the highest)
* MaritalStatus: The marital status of the customer (Single, Married, Divorced)
* NumberOfAddress: The number of addresses associated with the customer’s account
* Complain: A binary variable indicating whether the customer has complained (1) or not (0)
* OrderAmountHikeFromlastYear: The percentage increase in order amount from the previous year
* CouponUsed: The number of coupons used by the customer
* OrderCount: The number of orders placed by the customer
* DaySinceLastOrder: The number of days since the customer’s last order
* CashbackAmount: The total cashback amount received by the customer

## Installation and Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/Sajithedakatt/Customer_Churn_Prediction.git

2. Install all the necessary packages and libraries. Run the python notebook file
