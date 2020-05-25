# Data-Cleansing

Once you source the data, it is essential to get rid of irregularities in the data and fix its quality.


One can encounter different kinds of issues in a dataset. Irregularities may appear in the form of missing values, anomalies/outliers, incorrect format and inconsistent spelling, etc., These irregularities may propagate further and affect the assumptions and analysis based on that dataset and may hamper the further process of machine learning model building. Hence, Data cleaning is required.


Dataset
1) Bank Marketing Campaign Dataset-
The bank provides financial services/products such as savings accounts, current accounts, debit cards, etc. to its customers. In order to increase its overall revenue, the bank conducts various marketing campaigns for its financial products such as credit cards, term deposits, loans, etc. These campaigns are intended for the bank’s existing customers. However, the marketing campaigns need to be cost-efficient so that the bank not only increases their overall revenues but also the total profit


Attributes details	
Customer id	- This column is about the id of the customer contacted
age	- This column consists of the age of each customer
salary	- This column represents monthly salary of the customer
balance	- This column represents the cash balance in the bank account of the customer
marital	 - This column consists of the information about the marital status of each customer.
jobedu	- This column consists of the information about the job and education of each cutomer
targeted	- not available
default - This column consists of two categorical variables ‘yes’ & ‘no’, where Yes - represents if the customer has defaulted any loan           no  - represents if the customer has not defaulted any loan
housing	 - This column consists of the two categorical variables ‘yes’ & ‘no’, where yes - represents if the customer has taken housing loan  no  - represents if the customer has not taken the housing loan                                                                                                                              
loan- This column consists of the two categorical variables ‘yes’ & ‘no’, where yes - represents if the customer has taken personal loan  no  - represents if the customer has not taken the personal loan
contact - This column provides the information on the means through which the customer has been contacted either ‘cellular’ , ‘telephone’ and ‘unknown’ represents no information day	day of month on which a particular customer is contacted
month	- This column provides the detail of month in which the customer is contacted during the campaign
duration	- This column represents the total call duration of each customer 
campaign- This column is the number of campaign in which customer is contacted.
pdays - This column represents  the no of days passed by since the customer has been reached via bank for any of the other products (not term deposit). Here, the value ‘-1’ represents that the customer has never been reached for any product
previous- This column represents the no of times the customer has been reached in the previous campaigns or for any of the other products(not term deposit)
poutcome- This column represents the outcome of the previous reach outs for any of the products(other than term deposits) provided by banks                                                                                                    
Unknown - This represents that the customer has not been reached so far   
Success - This represents that the previous call was a successful conversion of the customer                                            Failure - This represents that the customer is not interested in the last product                                                        Other -  This represents that during the previous call, the customer has not given any definite answer
response- This column represents whether the customer has opened the term deposit account or not
