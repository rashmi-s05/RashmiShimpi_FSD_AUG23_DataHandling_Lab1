# **E-commerce Database Setup**

This repository contains the Python code and SQL queries to create and manage an e-commerce database. The database is set up with tables for suppliers, customers, products, orders, and ratings, and it is used to answer various business-related queries.

## Table of Contents
- [Project Overview](#project-overview)
- [Installation Instructions](#installation-instructions)
- [Usage Instructions](#usage-instructions)
- [Queries](#queries)
- [License](#license)

## Project Overview

The project sets up an E-commerce database with the following tables:
- **supplier**: Stores details of suppliers.
- **customer**: Stores information about customers.
- **category**: Contains the product categories.
- **product**: Contains product details like name and description.
- **product_details**: Stores information about products from different suppliers.
- **order**: Stores the orders placed by customers.
- **rating**: Stores ratings given by customers to suppliers.

SQL queries are written to answer business-related questions, such as finding customer orders, displaying supplier details, and calculating the total order amount for male customers.


## Usage Instructions

### Set up MySQL:
Make sure that your MySQL service is running. If it's not, start it via your MySQL server manager (like XAMPP if you're using it).

### Create Database:
Use the provided SQL queries to create the `e_commerce` database and all its associated tables.

### Insert Sample Data:
Use the SQL queries in the provided notebook to insert sample data into the tables.

### Run Queries:
Execute the SQL queries for various operations like finding customer orders, displaying supplier details, etc.

### Access the Jupyter Notebook:
Open the Jupyter Notebook by running `jupyter notebook` in your command line or terminal. Once it's running, open the notebook file (`e_commerce.ipynb`).

### Execute Code in the Notebook:
The notebook contains Python code that interacts with the MySQL database to execute the queries.

**Example**:
To execute a query that displays the number of customers who have placed orders greater than or equal to Rs.3000, simply run the relevant cell in the notebook.

## Queries

Some of the key queries that are run in the notebook include:

- **Q3**: Display the number of customers grouped by their gender who have placed an order of amount greater than or equal to Rs.3000.
- **Q4**: Display all the orders along with the product name ordered by a customer with `Customer_ID=2`.
- **Q5**: Display the supplier details who can supply more than one product.
- **Q6**: Find the category of the product whose order amount is minimum.
- **Q7**: Display the product ID and name of the products ordered after "2021-10-05".
- **Q8**: Print the top 3 supplier names, IDs, and ratings along with the customer name who has given the rating.

Refer to the notebook to run these queries and obtain the results.
