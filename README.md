# Covid-19-Dashboard
![covid_19-dashboard-screenshot](https://user-images.githubusercontent.com/68505433/156105718-f319eec8-f259-46c7-9878-696daab4410d.png)

##Overview
An interactive dashboard that summarizes the current Covid-19 
status worldwide and for each country, using public open-source 
data.

##Technical Details:
###ETL (SSIS):
o Extract Covid19 data from the CSV file.
o Transformed data and added Date and other dimensions to make OLAP operations meaningful and more manageable.
o Load the transformed data into an SQL database to benefit from SQL querying performance and make querying data easier, faster, and more reliable.
###Reporting (Power BI):
o Connect the MSSQL database with Power BI using the DirectQuery model for faster querying.
