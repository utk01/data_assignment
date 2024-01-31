# Data Assignment Notebook

## Overview

This notebook contains Spark code for analyzing Amazon reviews data. It covers various tasks, including finding items with the least and most ratings, identifying items with the least and most average ratings, and exploring reviews with the longest lengths.

## Prerequisites

Make sure you have Apache Spark, Jupyter Notebook, Postgres installed and configured in your environment along with libraries and drivers like pyspark and postgres.

## Notebook Structure

### Create Spark Session and Load Data:

- Set up a Spark session and load the Amazon reviews data into a PySpark DataFrame.

### Item with Least Rating:

- Identify items with the least rating in the entire dataset.
- Find items with the least average rating for items having at least 10 ratings.

### Item with Most Rating:

- Identify items with the highest rating in the entire dataset.
- Find items with the highest average rating for items having at least 10 ratings.

### Items with Longest Reviews:

- Identify the item with the longest review.
- Find items with the maximum average review length.

### Transform: Change the Date Format:

- Convert the date format in the dataset.

### Writing to Postgres Table:

- Save the processed data to a Postgres table.

### Writing to Parquet File:

- Save the processed data to a Parquet file.
  
## Usage

- Open the notebook in a Spark environment (Jupyter etc.).
- Run the cells sequentially to execute the Spark code.
