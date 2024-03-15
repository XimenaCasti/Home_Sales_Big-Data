1. Overview: 

This project involves analyzing home sales data using SparkSQL in PySpark. The goal is to derive key metrics from the data by creating temporary views, partitioning the data, and utilizing caching techniques to optimize query performance.

2. Setup
  Prerequisites
  Python
  PySpark
  Jupyter Notebook or any Python IDE
3. Data Analysis
  Using SparkSQL, I asnwered the following questions:
    Calculate the average price for four-bedroom houses sold each year. Round off to two decimal places.
    Determine the average price of homes built each year with three bedrooms and three bathrooms. Round off to two decimal places.
    Find the average price of homes built each year with three bedrooms, three bathrooms, two floors, and an area of at least 2,000 square feet. Round off to two decimal places.
    Compute the average price of homes per "view" rating, for homes with an average price of at least $350,000. Note the runtime for this query and round off to two decimal places.
    Performance Optimization
    Cache the home_sales temporary table.
    Verify if the table is cached.
    Re-run the last query using the cached data and compare the runtime to the uncached runtime.
    Partition the data by the "date_built" field and create a temporary table for the partitioned data.
    Compare the runtime of the last query on the partitioned data to the uncached runtime.
    Uncache the home_sales temporary table and verify it's uncached using PySpark.
