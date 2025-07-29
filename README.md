# BIG-DATA-ANALYSIS

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: G.VARUN KUMAR GOUD

*INTERN ID*: CT04DZ1712

*DOMAIN*: DATA ANALYTICS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

# DESCRIPTION:
In this project, we perform scalable data analysis on a large dataset containing over one million records of New York City taxi trips. The primary objective is to demonstrate how Apache Spark, specifically its Python API PySpark, can be leveraged to efficiently process and analyze large-scale data. The dataset includes detailed trip-level data such as pickup and dropoff timestamps, passenger count, trip duration, geographic coordinates, and vendor identifiers.

📊 Objective
The task involves conducting meaningful analysis on this data to extract insights, while also showcasing Spark’s ability to scale efficiently with data volume. Using PySpark, we apply various transformations and aggregations that would be computationally expensive in traditional data processing frameworks. To illustrate scalability, we perform the same computations under different optimization strategies including baseline processing, caching, and repartitioning to evaluate their performance impact.

📈 Analysis Performed

Several analytical queries are conducted to derive insights:

1. Average Trip Duration by Hour: We compute the average duration of taxi trips for each hour of the day. This reveals which hours tend to have longer or shorter travel times, which may correlate with traffic patterns.

2. Passenger Count Distribution: Analyzes how many passengers typically ride together, helping understand trip occupancy trends.

3. Store-and-Forward Flag Distribution: Shows how often trips are delayed in being sent to the server, indicating real-time vs. batch uploads.

4. Top 5 Longest Trips: Identifies extreme cases in the dataset to understand outliers in trip duration.

🚀 Scalability Demonstration

Without Optimization: Basic transformation and aggregation without any performance tuning.

With Caching: cache() is used to keep intermediate results in memory, avoiding recomputation.

With Repartitioning: The data is repartitioned using repartition() by pickup_hour to optimize parallel processing across Spark executors.

This project provides hands-on experience in using PySpark for large-scale data analysis. It clearly demonstrates how simple optimizations such as caching and repartitioning can drastically improve performance. 

# OUTPUT:

https://github.com/user-attachments/assets/553e5f2a-ece1-4dd0-a368-23866afeb7f8
