
 # Financial Payment Services Fraud Prediction
* Fraud detection is the process of identifying illegal acts that result in the acquisition of money or property under false pretenses.
* Our project aimed to use logistic regression to improve the detection rate of fraudulent payments.
* We conducted detailed data exploration and cleaning to find an optimal solution for identifying fraudulent payments.
* Our framework addresses class imbalance, chooses the appropriate logistic regression method and creates derived variables to improve fraud detection accuracy.
* We successfully developed an algorithm for detecting fraudulent transactions in financial data.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)


## General Information
Our major motivation behind choosing fraud detection as our project is that this has become a significant issue in the world. With increasing value for money and the number of trades happening throughout the world every second, it is vital to ensure that every transaction is true and real. It is humanly not possible to keep a check on whether every transaction is genuine and is not a Fraud. Hence our goal is to provide a project which will help us in showing how to detect frauds more consistently and accurately giving as minimum errors as possible.


## Technologies Used
- Python libraries: Scikit-learn, Numpy, Pandas, Matplotlib, Seaborn, Missingno


## Features
After building the Logistic regression model and finding out the accuracy and AUC curve the below analysis can be made.
* The total number of fraud transactions was 8213 out of 6362620 transactions.
* These fraud transactions were either CASH_OUT or DEBIT and were made from a customer-to-Customer account.
* We trained in Logistic Regression algorithm. It gave the score of 99.91%



## Setup
The project requirements/dependencies are listed in the import statements at the beginning of the code:
* numpy
* pandas
* missingno
* imblearn
* lightgbm
* xgboost
* matplotlib
* seaborn
* scipy
* plotly

To set up your local environment and get started with the project, you need to follow these steps:

1. Install Python on your computer if you haven't already done so. You can download Python from the official website: https://www.python.org/downloads/

2. Open a command prompt or terminal window and navigate to the directory where you want to store the project files.

3. Clone the project repository using Git or download the project files directly from the repository.

4. Install the required dependencies by running the following commands in your command prompt or terminal window:
`pip install numpy pandas missingno imblearn lightgbm xgboost matplotlib seaborn scipy plotly`

5. Once the dependencies are installed, you can open the Jupyter Notebook file containing the project code and run the code cells to execute the project.



## Usage
This project can be used to improve fraud detection and prevention in financial payment services. It can help to detect fraud patterns, analyze customer behavior, assess risk, prevent fraud, monitor transactions and analyze chargebacks. By leveraging this algorithms, financial institutions can reduce the risk of fraud, improve customer trust, and increase profitability.


## Project Status
Project is: _complete_


## Room for Improvement
In this study, we evaluated the effectiveness of using specific supervised machine learning techniques to solve the problem of fraud detection in financial transactions. The limitations of the methods applied in this study are as follows:
* We used a pre-labeled dataset to train the algorithms. However, usually, it is difficult to find labeled data and thus applying supervised machine learning techniques may not be feasible. In such cases, we should evaluate unsupervised techniques which were beyond the scope of this study.
* This study considers digital transactions data that includes amount transacted, the balance of recipient and originator, and time of transaction. These variables that helped in detecting fraud may not apply to other types of financial transactions, such as credit card fraud.
* We evaluated machine learning algorithms – Logistic Regression. Although the result of the study using these algorithms is good, it is necessary to evaluate other techniques to determine which algorithm works best for this application.
* Due to the large size of the data, we were limited by computation capacity to explore different techniques such as grid search for parameter tuning, SMOTE sampling technique. These techniques may help in further improving the results of this study.
