# Lending Club Case Study
> This case study involves understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.
> It is solved by use of EDA to understand how consumer attributes and loan attributes influence the tendency of default.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
<b>What is the background of your project?</b>

- This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.
 
- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

<b> What is the business problem that your project is trying to solve? </b>

- The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.

<b> What is the dataset that is being used? </b>

- [Loan DataSet](loan.csv)
- [Data Dictionary - Data attribute definition](Data_Dictionary.xlsx)


## Conclusions
- Higher loan grade(G) will have more chances of charging out. Lesser risk grade loans(A) have less chances of charging out.
- “Small Business” loan purpose has higher chances of charging out.
- Higher interest rate of loan will have higher chances of charging out.
- Company should focus on giving loan for shorter term (36 months than 60 months).
- Company should not give loans to borrowers with derogatory public records.
- Company should not give loans to borrowers with bankruptcy records.
- Company should not give loans to borrowers with more than 24 open credit lines.
- Company should not give loans to borrowers with more than 2 inquiries in last 6 months.
- Home Loans with higher interest should not be given.


## Technologies Used
- numpy
- pandas
- matplotlib
- seaborn



## Contact
Created by [@arijeetsaha](https://github.com/arijeetsaha) - feel free to contact me!
