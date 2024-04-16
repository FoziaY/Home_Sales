Home Sales Analysis
This project utilized SparkSQL to analyze key metrics about home sales data. Various operations were performed, including creating temporary views, partitioning the data, caching and uncaching a temporary table, and comparing runtimes.

Findings
Average Price for Four-Bedroom Houses: The average price for a four-bedroom house sold each year was calculated and rounded off to two decimal places.

Average Price of Homes by Year Built: The average price of homes with three bedrooms and three bathrooms, grouped by the year they were built, was determined and rounded off to two decimal places.

Average Price of Homes Meeting Specific Criteria: The average price of homes with three bedrooms, three bathrooms, two floors, and a size greater than or equal to 2,000 square feet, grouped by year, was calculated and rounded off to two decimal places.

View Ratings for Expensive Homes: The "view" ratings for homes costing more than or equal to $350,000 were identified. The runtime for this query was determined and rounded off to two decimal places.

Data Comparison
Original Data: The analysis was initially performed on the original dataset.

Cached Data: The dataset was cached to enhance query performance, resulting in faster runtimes compared to the original data.

Parquet Formatted Data: Further optimization was achieved by partitioning the data and storing it in Parquet format. This resulted in the best runtime performance among the three options (original, cached, and Parquet formatted data).

In conclusion, the Parquet formatted data demonstrated superior runtime performance, providing an efficient solution for analyzing home sales data.
