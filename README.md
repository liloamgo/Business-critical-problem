# CreditOne
Define a Data Science Process

**Data Set Information:**
This research aimed at the case of customers default payments in Taiwan and compares the predictive accuracy of probability of default among six data mining methods. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. Because the real probability of default is unknown, this study presented the novel Sorting Smoothing Method to estimate the real probability of default. With the real probability of default as the response variable (Y), and the predictive probability of default as the independent variable (X), the simple linear regression result (Y = A + BX) shows that the forecasting model produced by artificial neural network has the highest coefficient of determination; its regression intercept (A) is close to zero, and regression coefficient (B) to one. Therefore, among the six data mining techniques, artificial neural network is the only one that can accurately estimate the real probability of default.

**Attribute Information:**
This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study reviewed the literature and used the following 23 variables as explanatory variables:
- **X1 = LIMIT_BAL**: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.
- **X2 = SEX**: Customer's gender (1 = male; 2 = female).
- **X3 = EDUCATION**: Customer's highest level of education (1 = graduate school; 2 = university; 3 = high school; 0, 4, 5, 6 = others).
- **X4 = MARRIAGE**: Customer's marital status (1 = married; 2 = single; 3 = divorce; 0=others).
- **X5 = AGE**: Age (year).
- **X6-X11 = PAY_1-PAY_6**: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows:
    * **PAY_1** (X6) = the repayment status in September, 2005; 
    * **PAY_2** (X7)= the repayment status in August, 2005;
    * **PAY_3** (X8)= the repayment status in July, 2005; 
    * **PAY_4** (X9)= the repayment status in June, 2005;  
    * **PAY_5** (X10)= the repayment status in May, 2005;  
    * **PAY_6** (X11)= the repayment status in April, 2005.
    * **The measurement scale for the repayment status is:**
        * **-2**: No consumption; 
        * **-1:** Paid in full; 
        * **0:** The use of revolving credit; 
        * **1=** payment delay for one month; 
        * **2=** payment delay for two months;
        * **3=** payment delay for three months;
        * **4=** payment delay for four months;
        * **5=** payment delay for five months;        
        * **6=** payment delay for six months;
        * **7=** payment delay for seven months;        
        * **8=** payment delay for eight months;
        * **9=** payment delay for nine months and above.
- **X12-X17 = BILL_AMT1-BILL_AMT6:** Amount of bill statement (NT dollar). We tracked the amount of bill statement records (from April to September, 2005) as follows:
    * **BILL_AMT1** (X12) = amount of bill statement in September, 2005; 
    * **BILL_AMT2** (X13) = amount of bill statement in August, 2005;
    * **BILL_AMT3** (X14) = amount of bill statement in July, 2005;
    * **BILL_AMT4** (X15) = amount of bill statement in June, 2005;    
    * **BILL_AMT5** (X16) = amount of bill statement in May, 2005;    
    * **BILL_AMT6** (X17) = amount of bill statement in April, 2005.
- **X18-X23 = PAY_AMT1-PAY_AMT6:** Amount of previous payment (NT dollar). We tracked the previous payment records (from April to September, 2005) as follows:
    * **PAY_AMT1** (X18) = amount paid in September, 2005; 
    * **PAY_AMT2** (X19) = amount paid in August, 2005;
    * **PAY_AMT3** (X20) = amount paid in July, 2005;
    * **PAY_AMT4** (X21) = amount paid in June, 2005;
    * **PAY_AMT5** (X22) = amount paid in May, 2005;
    * **PAY_AMT6** (X23) = amount paid in April, 2005.
- **Y = DEFAULT_STS:** Client's behavior; Y=0 then not default, Y=1 then default"
    * **What Is Default?** Default is the failure to repay a debt including interest or principal on a loan or security. A default can occur when a borrower is unable to make timely payments, misses payments, or avoids or stops making payments

### Loan Approval Prediction Model in Python
- Informal Report can be found [here](https://github.com/liloamgo/CreditOne/blob/master/Credit%20One_%20Loan%20Approval%20Prediction%20Model%20in%20Python.pptx).
- Jupyter Notebook is located [here](https://github.com/liloamgo/CreditOne/blob/master/CreditOne-LoadandExamine.ipynb).
- Data Extract copy is located [here](https://github.com/liloamgo/CreditOne/blob/master/CreditOne_Data_Extract.csv).
