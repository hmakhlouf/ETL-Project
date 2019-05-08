# ETL-Project

1. Names:
Omar Aziz
Wilton Kwong
Ayobami Folaranmi
Hocine Makhlouf

2. The sources of data that you will extract from:
Jodidata.org - csv file containing monthly oil production by country over the last 5 years, between 02/2014 to 02/2019.
http://www.jodidb.org/TableViewer/tableView.aspx?ReportId=9390

 Bloomberg - will be using the bloomberg api to retrieve oil benchmark prices data over the last 5 years (02/2014 to 02/2019).
https://www.bloomberg.com/professional/support/api-library/


3. What useful investigation could be done with the final database: 
Users can create insights on how the oil price volatility impacts production.
Users can also see patterns or trends in oil supply  and  demand. 


4. The type of transformation needed for this data (cleaning, joining, filtering, aggregating, etc):
Joining.
Use the pandas library in Python to clean, join/merge, and structure data for easy accessibility and user consumption.

 5. The type of final production database to load the data into (relational or non-relational):  
Relational Database. The two data sources are homogeneous
 So we can match the price data from the Bloomberg API with each month of oil production from the Jodi csv dataset.

6. The final tables or collections that will be used in the production database:
Oil production by country 
Oil prices by benchmark i.e Brent and WTI
