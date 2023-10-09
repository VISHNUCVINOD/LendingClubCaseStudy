# Leading Club case Study

You work for a consumer finance company which specialises in lending various types of loans to urban customers
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
When a person applies for a loan, there are two types of decisions that could be taken by the company:

Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
    Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
    Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
    Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan
Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.).Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study. In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment

## Table of Contents
        Understanding Business Problem and  Requirement                                         
        Data Cleaning                               
        Data  Analysis
            a. Univariate Analysis
            b. Bivariate Analysis
        Conclusion            


## General Information
-   We have used Loan.csv file which is provided for the casestudy analysis material , as the dataset. 
-   We have done the analysis using the Loan dataset and cleaned the original data  and also used the concepts like Univarient , bivarient to find the variations. For better understanding we have plotted those derived point usin the charts for better visual representation. 
-   We have also provided solution / conclusion for the requested business problem where we need to find the key atributes of the defaulters.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Found the key identifier(variables/attributes) for the applicant to be defaulter.

## Technologies Used
    import pandas as pd
    import matplotlib.pyplot as plt
    import seaborn as sns
    import numpy as np
    import re
    import warnings


## Contact
Created by [VISHNUCVINOD@githubusername] - feel free to contact me!


