# Bright-Coffee-Shop-Sales-Analysis

##This is an Analysis on the sales trend for the Bright Coffee Shop 
The **Bright Coffee Shop Sales Analysis ** project aims to uncover key business insights using transactional data from a local coffee shop./
The goal is to help the new CEO make data driven decisions that will 
** increase revenue , identity best-selling products , and improved overall performance **
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Project Objectives
-Process and clean sales data for accurate amalysis ./
-Identity **sales trends** ,**best-selling products** ,and **peak sales times**./
-Create visual dashboards to communicate findings clearly./
- Provide ** strategic recommendations ** for business growth.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Task Breakdown 

###**Task 1:Data Preparation**
1.Review the provided Excel dataset./
2.Convert the dataset to **CSV format **for use in Snowflake ./
3.Plan the data workflow using a **Miro diagram**(from data input to insights).

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

##Task 2:Data Processing in Snowflake **

1.**Convert ** the Excel file CVS and **upload ** it too your Snowflake workspace ./
2.Performance the following **data transformations** :
-Create a new column 'transaction_time_bucket' to group transactions into 30-minute (or 1-hour) intervals./
- Clean 'unit_price' values(convert formats such a '3,1'./

- Compute 'total_amount' using :
  
  '''sql
  total_amount = unit_price *transaction_qty'''

  -Use SQL to group data by product type ,time intervals ,and other relevant categories.

  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  ### Task 3: Data Analysis in Excel**

  1.Export the cleaned and processed data Snowflake onto **Excel**
  or **Google Sheets **./
  2.Create **dashboards** or ** pivot tables ** showing :
   -Total revenue per product type\
   -Peak time intervals for sales \
   -Quantity of items sold by product category \
   -Best-selling products or product details \
3.Use **charts and graphs** to make insights visually appealing and easy to interpret

  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  ###** Task 4: Presentation to the CEO **

  Prepare a **presentation ** summarizing your findings and insights.

  Include :1.**Overview of your approach ** (methodology and data)\
  2.**Key insights and visuals **from your analysis\
  3.** Recommendations ** such as:-Lauch Marketing campaigns during slow time slots\
  -Stock more of the best-selling products\
  -Promote or phase  out underperforming items

  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  ###**Next Steps**

  --Automate daily sales reporting.\
  -Track sales across multiple store locations.\
  -Implement loyalty programs based on peak customer time slots.

  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  ## Submission Guidelines

  Submit the following deliveries :- Miro Plan/Diagram\
-Processed Dataset (Excel or Google Sheets) with pivot tables and charts\
-Powerpoint Presentation for the CEO \
-Text file containing SQL code used in snowflake

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Tools Used 

- **Snowflake ** Data processing and transformation\
- **Microsoft Excel /Google Sheets** -- Data analysis and visualization\
- **Miro** --Workflow and process planning\
- **powerPoint** -- Presentation to the CEO

- -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Author

** BrightLearn Data Analytics Student **\
Project *Bright Coffee Shop Sales Analysis (2025)*

