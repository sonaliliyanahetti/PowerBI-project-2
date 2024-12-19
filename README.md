STEP 1: Import data set from MySQL by connecting MySQL to the PowerBI.


STEP 2:  Data Modeling 
         Make relationships between transaction.market_code and order_date with 
         sales markets.markets_code and sales_date.date.

STEP 3:Clean data 
        >Remove Blank columns in sales market query.
        >Remove negative and zero sale_amounts in sales amount column in sales 
         transactions query
        >Add a conditional column and name it as NormalizedSalesAmount to change
         USD values to INR.(By editing formular)
        >After searching SQL Queries there was two types of INR types (INR,INR/r)
         remove INR by filtering (because INR has least no of amount of data)and 
         remove USD by filtering(because USD values repeated)

STEP 4:Making PowerBi dashboard
            ![Screenshot 2024-12-19 161216](https://github.com/user-attachments/assets/882f90cf-232a-4084-925e-bb63da68dda5)
