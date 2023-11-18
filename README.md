# GreyLife Canara DACOE-Thon - Loan  Default Prediction & Prevention Solution

## Introduction

We propose to develop an AI-powered blockchain-based mobile application that will help Canara Bank to assess the risk of borrowers more accurately, making the process of loan prediction, tracking and prevention more reliable.
This app collects essential borrower data, such as credit scores, income, and debt-to-income ratios, alongside collects non-traditional data form the user in the form of personality assessment test to anticipate financial
behavior and risk tolerance level.

An Advanced ML model is then employed to ascertain whether an applicant qualifies as a low-risk candidate based
on both traditional and non-traditional data.
Notably, all borrower information will be securely stored in a decentralised private blockchain network, ensuring the
utmost security and privacy.

The app contains a user friendly customer service assisted by Automated System and Live Human Interaction so
that loan borrower can clear his doubts regarding the process etc, thus preventing the loan form turning into a bad
loan.

Furthermore, this application goes beyond risk assessment by offering borrowers personalised risk mitigation
guidance through customer service. This approach encompasses financial education and tailored
recommendations aimed at improving the borrower's financial well-being. By adopting a proactive stance, the
application empowers borrowers to progressively diminish their risk profile over time.

## Project Components

This Project is divided into 3 parts:

1. **Android**
2. **Machine Learning**
3. **Blockchain**

## Android App

The Android app has two sides:

- **Borrower**
- **Lender**

## Borrower's Side App Screenshots

### Login and Signup Screens:


<img src="https://github.com/Smarshal21/GREYLIFE_CANARA/assets/99678760/78303699-85a9-4de2-bdd1-d15a06b81578" width="250" height="500" /> 
<img src="https://github.com/Smarshal21/GREYLIFE_CANARA/assets/99678760/9fdb5c7c-8c62-4092-bacd-c1c105f42c19" width="250" height="500" />

### Home and Status Screens:
<img src="https://github.com/Smarshal21/GREYLIFE_CANARA/assets/99678760/16ec6432-b102-4d8d-8942-78e0059628c1" width="250" height="500" /> 
<img src="https://github.com/Smarshal21/GREYLIFE_CANARA/assets/99678760/ce939219-55d8-48e7-9237-3b0155a18d79" width="250" height="500" /> 
<img src="https://github.com/Smarshal21/GREYLIFE_CANARA/assets/99678760/5e8a8d03-d8a8-474f-8cc3-f965d3596887" width="250" height="500" /> 

### SRIT Test and Risk Mitigation Screens:
<img src="https://github.com/Smarshal21/GREYLIFE_CANARA/assets/99678760/476d3813-3c85-473d-914c-e8e86e71a1c3" width="250" height="500" /> 
<img src="https://github.com/Smarshal21/GREYLIFE_CANARA/assets/99678760/8d8d3e78-5411-4664-b72e-d86483ccfe92" width="250" height="500" /> 


## Lender's Side App Screenshots


### Chat and Risk Mitigation Screens:
<img src="https://github.com/Smarshal21/GREYLIFE_CANARA/assets/99678760/37b0ddf2-62a4-4f8a-b684-a5b8a03f6c1c" width="250" height="500" /> 
<img src="https://github.com/Smarshal21/GREYLIFE_CANARA/assets/99678760/817c4721-5d1b-4d85-bb16-6e9fe2a74207" width="250" height="500" /> 

### Customer Details and Status:
<img src="https://github.com/Smarshal21/GREYLIFE_CANARA/assets/99678760/0f313e15-5db8-4dcd-bca9-fb12d808f7e4" width="250" height="500" /> 
<img src="https://github.com/Smarshal21/GREYLIFE_CANARA/assets/99678760/da788086-e2d5-4188-b59d-a3a3e645d4b9" width="250" height="500" /> 


## Machine Learning
### Overview
This project showcases the deployment of machine learning models using PCA (Principal Component Analysis) and XGBoost in Python. The models are trained and saved using pickle, then integrated into a Flask API. The Flask API is deployed on Railway, enabling users to send data from their mobile devices and receive predictions in real-time.
#### PCA (Principal Component Analysis)
Reduces the dimensionality of data, which can lead to faster training and improved model efficiency.
Helps in identifying important patterns and reducing noise in the data
It Reduces the input size from 11 to 3 and then process the result 
#### XGBoost
Provides high predictive accuracy and often outperforms other machine learning algorithms.
Allows for feature selection and can handle both numerical and categorical data
#### Ensemble Learning
Can lead to improved model performance, especially when the individual models have complementary strengths and weaknesses. Provides more robust predictions and is less sensitive to outliers or noise in the data.

### Workflow

<img src="https://github.com/Smarshal21/GREYLIFE_CANARA/assets/99678760/186e90d2-8e2e-4885-b72d-76308e8cf12b" width="700" height="300" /> 


### Sample Input and Output
<img src="https://github.com/Smarshal21/GREYLIFE_CANARA/assets/99678760/04403898-f017-4204-a711-8576a999cd91" width="1000" height="500" /> 

## BlockChain
### Overview
This project focuses on the deployment of a Polygon Edge Chain on Amazon Web Services (AWS) using the Kaleido platform. The Polygon Edge Chain provides high-performance, low-latency infrastructure for blockchain applications. By successfully running a Polygon Edge Chain, this project aims to facilitate the development of efficient and scalable decentralized applications
### Consortium blockchain architecture
#### Node
Each node stores a copy of the blockchain and participates in the consensus process to validate transactions and add new blocks to the chain. There are two nodes running on polygon blockchain
#### Ledger
The ledger is the decentralized database that stores all of the transactions that occur on the blockchain
#### Smart Contracts
Smart contracts are self-executing contracts.These are used blockchain consortium architecture to automate the process of executing transactions on the blockchain. Kaleido's Smart Contract Management component simplifies Ethereum transaction submission and application development by providing clean RESTful interfaces for interaction with your smart contract methods.
##### Smart Contract WorkFlow
<img width="1025" alt="Screenshot 2023-11-16 at 2 42 25 AM" src="https://github.com/Smarshal21/GREYLIFE_CANARA/assets/99678760/aedf1e91-5731-47a9-9206-b5ec68a8633d">

#### Governance
Consortium blockchain governance is member-defined and adaptable, comprising rules and decision-making mechanisms tailored to specific use cases and goals.
Access to a private blockchain network is restricted to authorized parties only, and the network is not open to the public.
Private blockchains are preferred in enterprise use cases, such as supply chain management, to maintain greater network control.
#### Transaction Details


<img src="https://github.com/Smarshal21/GREYLIFE_CANARA/assets/99678760/795fc8ed-f16a-418a-8b90-aed448b0086d" width="500" height="250" /> 
<img src="https://github.com/Smarshal21/GREYLIFE_CANARA/assets/99678760/63e3c1fa-7def-44df-8042-0644c1d4831b" width="500" height="250" /> 
<img src="https://github.com/Smarshal21/GREYLIFE_CANARA/assets/99678760/7745bf72-2e5f-4b42-8704-5e606e2c2efb" width="550" height="300"/> 

## Features
- Authentication - Email-Password
- Dashboard
- Status Page (Application Status)
- Page for Uploading Documents and Data
- ML model Processed Output
- Secure Storage of data in Private Polygon BlockChain Deployed on Kaleido

## TECH STACK
- Kotlin
- XML
- Firebase
- Python
- Sklearn
- Flask
- Railway
- Solidity
- Kaleido
- Polygon-Edge
- JavaScript
## Meet The Team
- KSN Samanwith (Team Leader)|[Github](https://github.com/Smarshal21)
- Badri Akkala |[Github](https://github.com/LCB2021029-Badri)


