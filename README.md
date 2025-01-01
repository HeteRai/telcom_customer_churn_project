Telcom_Customer_Churn_Project <br>
<br>
1. Introduction 
The dataset used in this project is the telco churn dataset provided by IBM. It contains data of a telco company, and it indicates which customers stayed and which customers left the company. <br>
In order to access the dataset, click [here](https://www.kaggle.com/datasets/alfathterry/telco-customer-churn-11-1-3) <br>
<br>
To see the powerpoint presentation with a summary of the project (portuguese version) click [here](https://docs.google.com/presentation/d/1ozNcy-qG0-XdpdbNBXn1F-1WUGCnOWcq/edit?usp=sharing&ouid=105775692478019800071&rtpof=true&sd=true) <br>
3. Motivation 
This project will be used to train my personal skills in data science. The goal of the project is to predict behavior to retain customers. Each row of the dataset represents a customer, each column contains customer’s attributes described in the data dictionary. 
<br>
4. Installation
To run this repository, you need to install the required libraries in the requirement file:
Run the following command in your terminal:

pip install -r requirements.txt

Note: Make sure you have Python and `pip` installed.

4. Repository Structure

<br>
TELCOM_CUSTOMER_CHURN_PROJECT/ <br>
│<br>
├── data/<br>
│   ├── data dictionary.xlsx <br>
│   └── telco.csv <br>
│<br>
├── models/ <br>
│   └── xgb_classifier.pkl <br>
│<br>
├── notebooks/ <br>
│   └── telecommunications-customer-churn.ipynb <br>
│ <br>
├── .gitignore.txt <br>
├── LICENSE.txt <br>
├── README.md <br>
└── requirements.txt <br>

5. Results

Results obtained on 06/12/2024

XGBoost (best model)
XGB Precision: 0.9955654101995566
XGB Recall: 0.961456102783726
XGB F1-score: 0.9782135076252724



