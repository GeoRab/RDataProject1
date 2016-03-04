Capstone Summary - Spring 2016

Problem Statement:
What is the customer churn and churn rate for personal tax return clients for a small to mid-size public accounting firm? 

Client motivation:
The client is a small to mid-size public accounting firm that specializes in non-profit accounting. In addition, the CPA firm provides tax planning and preparation services for businesses and individuals. The client seeks to understand the customer churn rate for clients seeking personal income tax preparation services. Based on the outcome of the analysis, the client will seek to retain customers through increased outreach to clients through personalization of services. 

Data set development:
All datasets will be provided by the client from internal records. 

AGI - Adjusted Gross Income of each customer by customer ID (2009 - 2015)
Time entries detail  - Total amount of time spent per customer by ID (2010-2015)
Filing status reports (client filing single or jointly 2009 - 2015)

    Important variables:
             Existing -- 
             Customer ID - integer field
             Customer State - String
             Customer Zip - integer or String (distance from the office)
             AGI - Adjusted Gross Income - integer  (income categories)
             Total time billed per client in number of hours - integer (will need to be developed from untidy dataset)
             Filing type - Single or Joint  (more sdata may be available)

             **Possible New Variables to generate:
             Longevity (a value based on the number of years a client has with the firm (these will be boolean? fields Y/N for each of the years analyzed. Example: 2years - y, 3-years - y; etc). 
             
             Dependent variable:
             Likely to Churn (Y/ N)
             
Proposed Data Processing:
Using the data points from raw data files as an input for independent variables, the key variables will be identified and 
a logistical regression will be performed to determine the potential correlation of the each independent variable as a possible 
churn determinant.

Deliverables:
A workflow summary of the regression analysis will be provided to include all commented code and meta-data. 
A summary will be provided to the client in the form of a non-technical summary report and presentation. 
The proposed final outcome is a profile of the personal income tax clients that may be likely to leave the service of the 
CPA firm. 

