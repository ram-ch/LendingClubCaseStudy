# Lending Club case study
This Case study is about analysing the loans dataset to extract insights on what could be the reasons for loan defaults. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:   

1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.     
Hence, This case study mainly performs EDA to understand how consumer attributes and loan attributes influence the tendency of default.   


## Table of Contents
* [Background](#Background)
* [BusinessProblem](#BusinessProblem)
* [Dataset](#Dataset)
* [Insights](#Insights)

### Background:   
The Lending company doest want give loans to defaulters or dosent want to loose business by rejecting loans to non-defaulters. So, how to identify the loan defaulters
### Business Problem:
Understand how consumer attributes and loan attributes influence the tendency of default.   
### Dataset:   
The dataset used is the loans dataset containing 111 features including the loan status with 39717 data points

## Insights
**Univariate Analysis**        
**<font color='green'>1. There is a higher chance of defaulting for 36 months term</font>**  
**<font color='green'>2. There is a higher chance of defaulting for grades B,C,D. Especially B5,C1,C2,D2 have a high count of Charged off loans</font>**  
**<font color='green'>3. emp_length with 10+ years are most likely to be Charged Off</font>**  
**<font color='green'>4. home_ownership is RENT for many Charged Off loans</font>**  
**<font color='green'>5. Most of the Charged Off loans are not verified</font>**  
**<font color='green'>6. Most of the loans issued in 2011 are defaulters, especially in the months of november and december</font>**  
**<font color='green'>7. Most of the Charged Off loans have an int_rate from 9%-13% , 13-17%</font>**  
**<font color='green'>8. Charged Off loans have an open_acc in the range of 2-10</font>**  
**<font color='green'>9. Charged Off loans have an revol_util in the range of 60-80 and 80-100</font>**  
**<font color='green'>10. Charged Off loans have an total_acc in the range of 2-20 and 20-37</font>**  
**<font color='green'>11. Charged Off loans have an annual_inc in the range of 31k-58k and 58k-85k</font>**     
**<font color='green'>12. Charged Off loans have an installment in the range of 145-274</font>**    
**<font color='green'>13. Charged Off loans have an funded_amt_inv in the range of 0k-5k and 5k-10k</font>**    
**<font color='green'>14. Charged Off loans have an loan_amount in the range of 0k-5k and 5k-10k</font>**    
**<font color='green'>15. Charged Off loans have an dti in the range of 12-18</font>**    


**Bivariate Analysis**    
**<font color='green'>1. Charged off loans are for the loans taken for the purpose of home_improvement</font>**   
**<font color='green'>2. The Charged Off loans in the low income group i.e, 3k-31k are approximately 5k</font>**   
**<font color='green'>3. The Charged Off loans in the high income group i.e, 112k-140k are approximately 17.5k</font>**   
**<font color='green'>4. The Charged Off loans amounts to more than 58k in the 60 months term category. similarly amounts to almost 50k in the 36 months category</font>**    
**<font color='green'>5. The Charged Off loans are having an installment of around 500 in the high income group i.e., 112k-140k. Similarly the Charged Off loans are having an installment of around 150 for the low income group i.e., 3k-31k </font>**    
**<font color='green'>6. The Charged Off loans are highest in the Grade G</font>**    
**<font color='green'>7. As the annual income is higher and the emp_length is higher there is a higher chance of defaulting</font>**    
**<font color='green'>8. Charged Off loans have a dti in the range of 12-14 for the low income group i.e., 3k-31k. Similarly the dti is in the range of 12-14 for the high income group i.e., 112k-140k</font>**    
**<font color='green'>9. The Charged Off Loan amount is in the range of 12k-14k for the borrowers with home_ownership as OTHER.</font>**     
**<font color='green'>10. The Charged Off Loans are very high for the borrowers with home_ownership as MORTGAGE</font>**     


## Contact
Created by [@ram-ch] - feel free to contact me!


