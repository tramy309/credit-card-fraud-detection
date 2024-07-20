# credit-card-fraud-detection

## Download Data

You can download the dataset from the following Google Drive link: [Credit Card Transactions Fraud Detection Dataset](https://drive.google.com/drive/folders/1_tzkdbcFHoXfUOr74iy5KKMQGm7mA_8f?usp=sharing)


# Credit Card Fraud Detection

Credit card fraud has become a serious and complex issue for the banking industry, especially with the rapid development of technology and the global financial system. Credit card fraud is notably prevalent, with statistics showing a clear spread of this issue.

According to the latest reports and studies from organizations like the Federal Trade Commission (FTC), credit card fraud remains one of the biggest risks in the financial system. For instance, in 2023, the FTC recorded around 426,000 cases of credit card fraud. Although this is slightly lower than the previous year, it is still significantly higher than earlier years, indicating a continuous increase in fraudulent activities and the complexity of attack methods.

Technological advancements have created new opportunities for fraudsters, from using fake software to exploiting security vulnerabilities in electronic payment systems. This poses a significant challenge for banks and regulatory agencies in protecting customer data and assets.

Advances in artificial intelligence and machine learning can provide powerful tools for banks to quickly and effectively identify and prevent fraudulent transactions. This not only helps minimize financial losses but also protects the sustainability of the financial and economic system against increasingly complex fraud threats.

## Project Overview

Our project focuses on "Building a Credit Card Fraud Detection Model" using the Credit Card Transactions Fraud Detection Dataset. This dataset contains credit card information from 1,000 customers making transactions with a group of 800 merchants. It includes both legitimate and fraudulent transactions from January 1, 2019, to December 31, 2020, with over 1 million rows and 22 attributes.

### Table 5.1. Description of Credit Card Transactions Fraud Detection Dataset Attributes

| Attribute | Description |
| --- | --- |
| trans_date_trans_time | Transaction time |
| cc_num | Credit card number |
| merchant | Merchant name |
| category | Transaction category |
| amt | Transaction amount |
| first | First name of the cardholder |
| last | Last name of the cardholder |
| gender | Gender of the cardholder |
| street | Address of the cardholder |
| city | City of the cardholder |
| state | State of the cardholder |
| zip | Zip code of the cardholder |
| lat | Latitude of the transaction |
| long | Longitude of the transaction |
| city_pop | Population of the cardholder's city |
| job | Job of the cardholder |
| dob | Date of birth of the cardholder |
| trans_num | Transaction number |
| unix_time | Unix formatted time |
| merch_lat | Merchant's latitude |
| merch_long | Merchant's longitude |
| is_fraud | Nature of the transaction (fraudulent or not) |

Based on the nature of the problem and the dataset, we build univariate and multivariate logistic regression models from the entire dataset after exploratory data analysis (EDA) and preprocessing. Additionally, we process the data (sample a random 1%) to run machine learning models including Random Forest, Neural Network, and Support Vector Machine on a subset of the data to evaluate the performance of these classifiers on credit card fraud data.
