# Lending Club Case Study
> This study is to identify the factors which leads the loans to get defaulted, in order to help the lending company, avoid losses
> 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Project Made By](#project-made-by)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
You work for a consumer finance company Lending Club which specialises in lending various types of loans to urban customers.
 
 When a person applies for a loan, there are two types of decisions that could be taken by the company:


**Loan accepted:** If the company approves the loan, there are 2  possible scenarios described below:

 -Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
 -Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan

**Loan rejected:** The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

**Objective:**

Lending loans to ‘risky’ applicants is the largest source of financial loss(called credit loss). The credit loss is the amount of money lost by the lender when the borrower refusesto pay or runs away with the money owed.  

The main objective is to be able to identify these risky loan applicants,then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.   

Perform an analysis to understand the driving factors (or driver variables) behind loan default, i.e.the variables which are strong indicators of default.The company can utilise this knowledge for its portfolio and risk assessment.

## Conclusions
-Customers with more DTI are more likely to default. Ofcourse, more DTI means, more liabilities as per 
the income. So, less chances of repaying the loan.

-Loans provided to customers belonging to a specific state NE are more likely to Charge Off. So the 
lenders need to be more cautious while giving loan to this state.

-Higher the interest rate, higher are the chances of loan to get Charged Off.

-Percentage of Charged off customer are more for 15000-20000 range loan amount(Low level).

-Customers taking loan for Small Business are more likely to Charge off as the chances of business 
failure is high as compared to other reasons.

-An increase is percentage of charged off customer as the grade decreases from A to G

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python : 3.8.8.final.0
- Pandas : 1.2.4
- Numpy : 1.20.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Project Made by
-Shachi Snehmayee

-Deepak Verma


## Contact
Created by [@dverma12] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
