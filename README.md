# Data-Cleaning---Python


Overview

This data analysis project involved importing and cleaning sales data for a year, as well as performing data transformation and analysis to answer various business questions. While the main focus was not on sales analysis, insights were gained into sales trends and product performance. The project made use of several libraries in Python, including pandas, matplotlib, os, itertools, and collections.




Libraries:


pandas: This is a library for data manipulation and analysis. It provides data structures for efficiently storing and analyzing large data sets, as well as tools for data cleaning, merging, and transformation.

os: This is a module for interacting with the operating system. It provides a way to work with files, directories, and paths.

matplotlib: This is a library for creating visualizations in Python. It provides tools for creating line plots, scatter plots, bar charts, and many other types of plots.

itertools: This is a module that provides various functions for working with iterable objects. It includes tools for combining, filtering, and transforming data, as well as generating permutations and combinations.

collections: This is a module that provides specialized container data types. It includes tools for working with collections of items, such as counters and deques. In your code, you are importing the Counter class, which is a tool for counting occurrences of items in a collection.





Process from Raw Data to Actionable Insights


Data import and concatenation: The sales data for all 12 months is merged into a single CSV file using pandas' "concat" method.
Data cleaning: Rows containing missing data and duplicated data are dropped and the invalid rows that contain only strings are also removed.
Data transformation: The "Order Date" column is converted to a pandas datetime format, and new columns such as "Month" and "Sales" are added.
Sales analysis: Various questions are answered using pandas' data frame methods, to understand sales trends over time and patterns in product sales.



Tool and version:

Python 3.6.6

