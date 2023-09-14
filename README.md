# Home_Sales

Instructions
Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

Import the necessary PySpark SQL functions for this assignment.

Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

Create a temporary table called home_sales.

Answer the following questions using SparkSQL:

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

![image](https://github.com/joeldemontigny/Home_Sales/assets/130711180/2d10e429-8694-48fb-b4ef-fc940f463b3c)


What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

![image](https://github.com/joeldemontigny/Home_Sales/assets/130711180/fd7d8738-2811-4126-9131-111f1f51a7ff)


What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

![image](https://github.com/joeldemontigny/Home_Sales/assets/130711180/53e92ecb-5b7b-45bc-bf94-7653d7598b8a)


What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

![image](https://github.com/joeldemontigny/Home_Sales/assets/130711180/3322c2e2-d7f5-48a5-b8b4-a25fd6e54423)


Cache your temporary table home_sales.

Check if your temporary table is cached.

Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

Partition by the "date_built" field on the formatted parquet home sales data.

Create a temporary table for the parquet data.

Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

Uncache the home_sales temporary table.

Verify that the home_sales temporary table is uncached using PySpark.

Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.

