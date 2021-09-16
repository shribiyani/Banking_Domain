# Banking_Domain

Consists Banking Financial Institutes and Non-Banking Financial Institutes related. 


### What is **Banking Financial Institutes** and **Non-Banking Financial Institutes**?

- An Instutions are those corporate leaders who accepts deposits in all form, leand loans in all form, provides investment facilities also those called **Banking Finacial Institutions**.
- An Institutions are those corporate houses which allows to lend loans in all form (almost) and also provides investment facilities in different stocks & bonds, mutual funds, these institutions called as **Non-Banking Financial Institutions**.


### Types of Banking Institutes
  - Commercial Banks
    - accepts deposits, offers checking account services, makes business, personal, and mortgage loans, and offers basic financial products like certificates of deposit (CDs) and savings accounts to individuals and small businesses.
    
  - Investment Banks
    - Specialized in providing services designed to facilitate business operations such as capital expenditure financing and equity offerings, which includes IPOs [initial public offerings]. 
    - Also offer brokerage services for investors for trading exchanges and manage mergers & acquisitions, and other corporate restructurings.


## Repositaries Links.

  1. **Top-Up Loan Up-Sell Prediction** - An Classification > link - https://github.com/shribiyani/Top-up-Loan-Prediction
    - Here Company wants to issue **Top-Up Loan** Facilities to their existing customers
    - It's a **Multi-Class Classifier** Problem.
    - I have two datasets - 1. Customer's Demographic Data with bank and 2. Customer's Bureau Data regarding 

  
  2. **Credit Card Default Prediction** - link https://github.com/shribiyani/Credit-Card-Default-Prediction
     - Here, Company wants to **Predict the Credit CardHolder will be Default in next month or not** on the basis of BILL_AMT and PAY_AMT history for last 6 month
     - Dataset has 30000 instances and 23 independent attributes.
     - Response class is **Imbalance Class** with `Class 0 = 23362` and `Class 1 = 6636`
     - I used **Class Probability** to predict cardholder will be defaulter or not.
     - I have used Decision Tree, Random Forest, Extra Tree, AdaBoost, GradientBoosting and Light GBM classifiers.
     - LightGBM gave me **approx. 80% ROC-AUC score** chances of **class 1**
     - while my Accuracy is approximatly 77% and F2 Score is upto 60%.



  3. **Loan Approval Prediction** - link https://github.com/shribiyani/Loan_Approval-Prediction/blob/main/Loan_Prediction.ipynb
     -  Here, company wants to **Predict the Loan Approval**
     -  Dataset is small but very informatic.
     -  it consists 12 independent features and 1 response variable
     -  Target Variable is distributed into 2:1 means We have **approved class [Y]** more then **rejected class [N].
     -  Accurancy was upto 80%
  
  
  
  4. **Home Credit Default Risk Prediction** - An Classification - Work-in Process
     - Here, Dataset is taken from Kaggle.com
     - Task - **Predict Home Credit Deafult Risk** 
     - Data consists multiple datasets like loan balance, credit card balnce, installment details, buerau information, etc., around 7 datasets
     - Main Data(train) consists around 121 independent variables and 1 response variable.
     - Data is **Imbalanced** in nature.
     - Project planning as - Set-up Architecture, EDA, Extract extra features from other datasets and run complete ML pipeline.
    
    
  5. **Credit Card Fraud Detection** - Applied Cluster Based Algorithms (Problem Based on an Classification) - work-in process
     - This data is also from Kaggle.com
     - Task - Detect Fraud and create an system that can mitigate it at ral time. 
     - Data is **Imbalanced** in nature.
     - Project planning as - Set-up Architecture, EDA, Extract extra features from other datasets and run complete ML pipeline.
 
  
  
