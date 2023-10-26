# Big Data Analysis: Home Market Comparison
## Project Overview
Using SparkSQL to determine the key drivers of the home sales data, creating temporary views for cached and parquet partitioned data, and comparing queries run time efficiency using the Time library. 


### Questions Explored
1. What is the average price for a four-bedroom house sold for each year? R
2. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms?
3. What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? 
4. What is the "view" rating for homes costing more than or equal to $350,000? 


#### Libraries Used
1. FindSpark
2. PySpark
3. Time


#### Folder structure
``` yml
.
│   ├── big_data
│   |   ├── home_sales_partitioned
│   |   |   ├── date_built=2010
│   |   |   |   ├── part-00000-734483f8-ad12-4923-ab03-96afc3d01e8f.c000.snappy.parquet
│   |   |   ├── date_built=2011
│   |   |   |   ├── part-00000-734483f8-ad12-4923-ab03-96afc3d01e8f.c000.snappy.parquet
│   |   |   ├── date_built=2012
│   |   |   |   ├── part-00000-734483f8-ad12-4923-ab03-96afc3d01e8f.c000.snappy.parquet
│   |   |   ├── date_built=2013
│   |   |   |   ├── part-00000-734483f8-ad12-4923-ab03-96afc3d01e8f.c000.snappy.parquet
│   |   |   ├── date_built=2014
│   |   |   |   ├── part-00000-734483f8-ad12-4923-ab03-96afc3d01e8f.c000.snappy.parquet
│   |   |   ├── date_built=2015
│   |   |   |   ├── part-00000-734483f8-ad12-4923-ab03-96afc3d01e8f.c000.snappy.parquet
│   |   |   ├── date_built=2016
│   |   |   |   ├── part-00000-734483f8-ad12-4923-ab03-96afc3d01e8f.c000.snappy.parquet
│   |   |   ├── date_built=2017
│   |   ├── Home_Sales.ipynb             
|___README.md    
|.gitignore          
``` 

