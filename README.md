# Home-Credit-dataset
Home Credit Group

Home Credit strives to broaden financial inclusion for the unbanked population by providing a positive and safe borrowing experience. In order to make sure this underserved population has a positive loan experience, Home Credit makes use of a variety of alternative data--including telco and transactional information--to predict their clients' repayment abilities.

While Home Credit is currently using various statistical and machine learning methods to make these predictions, they're challenging Kagglers to help them unlock the full potential of their data.

Home Credit dataset can be downloaded from https://www.kaggle.com/c/home-credit-default-risk/

# PROJECT SCOPE :
# To identify defaulter and predict wheather the aplicants loan approved or  not to approved.

 # STEP 1 : creating DDL (Data Defination Language)
 
Renamed the columns of the data and identified the data type of each column and converted all downloaded csv files into relational database, using MYSQL and MYSQL workbench and saved it on server. 
( (mysql  Ver 5.7.28-0, MYSQL workbench 6.3.8, Operating system of server  ubuntu 18.04.))

Challenges faced:

* connecting MYSQL client from local machine to a remote server. 
-sucessfully overcame by changing the settings of fire wall and enabling SSH in remote server  

* learning the git bash commands. 

# DATA INSIGHTS : 

1. Sample size columns Rows 221, There are total 8% of loan rejections in the sample.
2. There are 291057 previous applicants, 16454 new applicants. Total number of applicants 307511
3. chances of new applications getting rejected is more if Median of total income is 135000   
4. new applicants are getting higher credit amount 534672 (MEDIAN)
5. 3, 8, 14, 16, 18  docs occur frequently. (applied apriori)

# Note : as per our understanding of Data two seprate algorithms should be build one for new applicants and other for new applicants.



