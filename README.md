# Home Credit Default Risk Prediction
---

## 1. Introduction & Problem Statement

This repository contains a data science project focused on the **Kaggle Home Credit Default Risk** competition. The primary objective is to predict whether a loan applicant will experience payment difficulties (i.e., default) based on a diverse set of data provided by Home Credit.

Home Credit provides loans primarily to the "unbanked" population, who often lack traditional credit histories. Therefore, the challenge involves leveraging alternative data sources (like telco and transactional information) alongside application data to accurately assess repayment capability. This project aims to build a machine learning model to classify applicants based on their likelihood to default.

**Competition Link:** [https://www.kaggle.com/c/home-credit-default-risk](https://www.kaggle.com/c/home-credit-default-risk)

## 2. Dataset

The project utilizes the comprehensive dataset provided for the Kaggle competition, which includes:

* `application_{train|test}.csv`: Main table with applicant information for training/testing.
* `bureau.csv`: Information about client's previous credits from other financial institutions reported to Credit Bureau.
* `bureau_balance.csv`: Monthly balances of previous credits reported to Credit Bureau.
* `POS_CASH_balance.csv`: Monthly balance snapshots of previous point-of-sale or cash loans applicants had with Home Credit.
* `credit_card_balance.csv`: Monthly balance snapshots of previous credit cards applicants had with Home Credit.
* `previous_application.csv`: Information about previous loan applications at Home Credit for clients in the main dataset.
* `installments_payments.csv`: Repayment history for previous loans at Home Credit.

**Data Source:** [https://www.kaggle.com/c/home-credit-default-risk/data](https://www.kaggle.com/c/home-credit-default-risk/data)

*Note: Due to size, the raw data files are not included in this repository. Please download them directly from Kaggle.*
