# walmart_sales_data
This project involves exploring, cleaning, and storing Walmart dataset using Python and MySQL. The steps include data loading, preprocessing, and saving cleaned data into a MySQL database.

Technologies Used

Python

Pandas

MySQL

SQLAlchemy

PyMySQL

Steps Implemented

Step 1: Data Exploration and Loading

Importing Dependencies

pandas for data handling

pymysql for MySQL connection

sqlalchemy for database interactions

Loading Data

Reading Walmart.csv using Pandas.

Checking the dataset's shape, head, and summary statistics.

Inspecting data types and missing values.

Handling Duplicates

Identifying and removing duplicate records.

Verifying the dataset after cleanup.

Handling Missing Values

Checking for missing values.

Dropping rows with missing values.

Verifying the dataset after cleanup.

Step 2: Data Transformation

Converting Data Types

Converting unit_price from string (with $ symbol) to float.

Creating a new column total by multiplying unit_price with quantity.

Converting column names to lowercase.

Step 3: Storing Cleaned Data

Saving Clean Data to CSV

Exporting the cleaned dataset to walmart_clean_data.csv.

Connecting to MySQL Database

Establishing a connection using SQLAlchemy and PyMySQL.

Handling connection errors gracefully.

Saving Data to MySQL

Uploading cleaned data to the walmart table in walmart_db.

Verifying the column structure.

How to Run

Install dependencies:

pip install pandas pymysql sqlalchemy

Ensure MySQL is running and properly configured.

Run the Python script to process and store the data.

Output

A cleaned dataset saved as walmart_clean_data.csv.

Processed data stored in MySQL under walmart_db database.

Notes

Ensure Walmart.csv is available in the working directory.

Modify MySQL connection credentials if needed.

Author

Nikhil Kumar Singh
