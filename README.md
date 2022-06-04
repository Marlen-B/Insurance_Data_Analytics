# INSURANCE DATA ANALYTICS



We ware provided with an Insurance dataset.
The main objective is perform EDA on the given dataset and draw useful conclusions about general trends in Insurance products and how factors governing Insurance market interact with each other.

 

## Dataset	

A Dataset called **Data analytics Project dataset** was given and after collecting and reading this data I’ve observed that it has 139390 rows and 26 columns.
The columns variables that I’ve used for this analysis were:

*InsurProductID:   Product code origination or contract, all products are linked to a system generation number 
*InsurCustomerID: 	Unique system bank id customer number
*Sub Seg: 	Customer Segment
*Insurance:  Currency	Currency
*Insur Sub Name: 	Product Name
*Insur Bank:   Related	Some products that a merely mandatory, e.g. there's no need to sign for them 
*Insur PackName:  	Insurance product family/group
*Product Status: 	Product Status



## Data Cleaning
First, I’ve analyzed the date them I’ve performed the cleaning:

1.	Dropping some columns

The following variables ware dropped: *Insurance Currency','Insur Sub Name','Insur Bank Related','Insur Value','Insur Cancellation Date','Insur end date','Next Pay Date','Last Pay date','NO_OF_TRXNS202007','NO_OF_TRXNS202008','NO_OF_TRXNS202009','TURNOVER202007','TURNOVER202008','TURNOVER202009','TURNOVER202010','NO_OF_TRXNS202010* .

2.	Removing duplicate rows

All duplicate rows were removed.

3.	Handling Null or Missing Values

  - Null values in *NO_OF_TRXNS202005, NO_OF_TRXNS202006, TURNOVER202005, TURNOVER202006* were replaced with 0.
  - Missing values in *Insur PackName* were replaced with ‘others’

## Exploratory Data Analysis 

In the EDA, I’ve tried to answer the following questions:
1. Which customer segment is most prevalent?
2. Which insurance group is most prevalent?
3. What is the status of product distribution?
4. Which customer segment has the most cancellations?

For these questions I had the following answers:

1. The most prevalent segment is GENNESIS.
2. The most prevalent Insurance group is Funeral.
3. The status is: 62% ACTIVE, 34% CANCELLED, 3% MATURED.
4. The customer segment with more cancellations is GENNESIS with a index of 40%.

# CONCLUSIONS

-	It was possible to notice that we have a cancellation rate of approximately 34% taking into account all the products offered;
-	The segment with the most cancellations is GENNESIS, with an index of approximately 40%. This value is worrying because GENNESIS is the product segment with the most adherence, therefore of the 91947 customers, around 37633 canceled the insurance;
-	With the facts described above, we can conclude that customers in the GENNESIS segment are more likely to cancel the product in the future;
-	Looking at the results obtained, the best product is platinum, which occupies the third position in the ranking of most used segments and has a cancellation rate of 9%.
