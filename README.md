# Home_Sales

# Overview

This project analyzes home sales data using PySpark and SparkSQL. It performs various queries to calculate key metrics, including average home prices based on the number of bedrooms, bathrooms, floors, and view ratings.

# Files

home_sales_analysis.py: Main script for data analysis using PySpark.

home_sales_revised.csv: Input dataset containing home sales data.

# Requirements

- Python 3.8+

- PySpark

- Google Colab

# Installation

- Install PySpark using the following command:

- pip install pyspark


# Usage

Upload the dataset to your environment.

Run the home_sales_analysis.py file in a PySpark-supported environment like Google Colab.

The script will display query results and measure query runtimes using cached and uncached data.

# Key Features

- Calculate average home prices based on bedrooms and bathrooms.

- Determine average prices for large homes with specific features.

- Compare query runtimes using SparkSQL caching.

- Partition data using Parquet for efficient querying.
