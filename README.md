Telcom_Customer_Churn_Project

1. Introduction
The dataset used in this project is the telco churn dataset provided by IBM. It contains data of a telco company, and it indicates which customers stayed and which customers left the company.
In order to access the dataset, click [here](https://www.kaggle.com/datasets/alfathterry/telco-customer-churn-11-1-3)

2. Motivation
This project will be used to train my personal skills in data science. The goal of the project is to predict behavior to retain customers. Each row of the dataset represents a customer, each column contains customer’s attributes described in the data dictionary. 

3. Installation
To run this repository, you need to install the required libraries in the requirement file:
Run the following command in your terminal:

pip install -r requirements.txt

Note: Make sure you have Python and `pip` installed.

4. Repository Structure

TELCOM_CUSTOMER_CHURN_PROJECT/
│
├── data/
│   ├── data dictionary.xlsx
│   └── telco.csv
│
├── models/
│   └── xgb_classifier.pkl
│
├── notebooks/
│   └── telecommunications-customer-churn.ipynb
│
├── .gitignore.txt
├── LICENSE.txt
├── README.md
└── requirements.txt

5. Results

Results obtained on 06/12/2024

1. Random Forest
RF Precision: 0.9846827133479212
RF Recall: 0.9635974304068522
RF F1-score: 0.974025974025974

2. XGBoost (best model)
XGB Precision: 0.9955654101995566
XGB Recall: 0.961456102783726
XGB F1-score: 0.9782135076252724



