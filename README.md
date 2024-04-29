# Safertek-Backend-2

This repository contains two Python scripts (`Task1.py` and `Task2.py`) for the Safertek Backend Exam. These scripts interact with a MySQL database to perform various operations.

## Environment Setup
- **IDE:** PyCharm
- **Library:** mysql-connector-python

## Task 1: Inserting Data into Tables

### Description
- The script `Task1.py` inserts data into two tables: `locations` and `countries`.
- It prompts the user to input data for both tables, including location ID, street address, city, state/province, postal code, and country code.
- After inserting the data, it applies a join condition between `locations` and `countries` tables to display the results.

## Task 2: Finding Locations by Country Name

### Description
- The script `Task2.py` prompts the user to enter a country name.
- It then queries the database to find the country ID based on the input country name.
- Once the country ID is found, it retrieves all the locations associated with that country and displays their details, including location ID, street address, city, state/province, and postal code.

**Note:** Make sure to replace "localhost", "root", "password", and "safertech" with your actual database host, username, password, and database name respectively in both scripts.
