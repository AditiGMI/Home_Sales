# Home_Sales
Big-data

1. Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.
2. Create a temporary table called home_sales.
Answer the following questions using SparkSQL:
3. What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.4. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
5. What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
6. What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
7. Cache your temporary table home_sales.
8. Check if your temporary table is cached.
9. Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
10. Partition by the "date_built" field on the formatted parquet home sales data.
11. Create a temporary table for the parquet data.
12. Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. 13. 13. Determine the runtime and compare it to uncached runtime.
14. Uncache the home_sales temporary table.
15. Verify that the home_sales temporary table is uncached using PySpark.
16. Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.

Summary:

We used sql queries on their own for the dataset by creating partial views, then we catched the table & in the last we partitioned the table & checked the run time for each of the 3 steps. My inference is their is increase in runtime in both catched & parqueted steps, so their is no significant use of doing these steps. The other reason could also be the dataset in itself is not very big, if it was a big data set, these steps could be useful.
