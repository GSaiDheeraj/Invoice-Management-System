# HighRadius-Summer-Internship-Invoice-Management-System

## Data 

-- Understanding data is too important than building a great model, because with out having a great data we can not build a great model.

1) business code - Product/service code provided by the company
2) cust_number - Distinguishing teh customer based on the department
3) name_customer - name of the customer
4) clear_date - Date the payment was done
5) business_year - year which the business done
6) doc_id - id of the document created
7) posting_date - date of the posting transactions
8) document_create_date = billing date/ date on the bill
9) due_in_date - due data to pay the amount
10) invoice_currency - currency in which the payment was made
11) total_open_amount - Amount prepaid to the seller
12) baseline_create_date - date till the payment terms will apply
13) isOpen - If payment was done 1, else 0

##  Data Preprocessing 
1) Importing the data
2) Checking Null values 
3) Creating the target Column
4) Removing the unwanted columns
5) Removing the rows with Null values
6) Setting the date columns

## EDA
-- Used Auto EDA libraries 1) AutoViz 2) Sweet Viz for visualizig the data and geting the insights from the data                                                                                         
-- Converted the columns into log normal distribution which are not normally distributed.

## Feature Engineering 
--Created features required for the predictions 
1) Year
2) Quarter
3) Month
4) Week 
5) Day
6) Expected Delay

## Machine Learning Models

1) Linear algorithms(linear regression, Lasso, Ridge Regressions, Elastic Net)
2) Tree Algorithms(Decision Tree, Random Forest)
3) KNN
4) Artificial Neural Network
3) EvalML: An auto ML library


