# Project: SQL Analysis of DVD Rental Database

## Overview
This project involves analyzing the DVD rental database, which contains information about a fictional DVD rental store's inventory, customers, rentals, and staff. By querying and analyzing this database using SQL (Structured Query Language), we can gain insights into various aspects of the rental business, such as customer behavior, popular movies, rental trends, and staff performance.

## Objective
The primary objective of this project is to explore the DVD rental database and extract meaningful insights that can inform business decisions and improve operational efficiency. Specifically, we aim to:

- Understand customer preferences and behavior, such as favorite movie genres and rental frequency.
- Identify popular movies, actors, and directors.
- Analyze rental patterns over time, such as peak rental hours and days.
- Evaluate staff performance in terms of rental transactions and customer interactions.

## Methodology
The analysis will involve querying the DVD rental database using SQL to extract relevant data and perform various analyses. The methodology includes the following steps:

1. **Data Exploration**: Understanding the structure and contents of the DVD rental database, including tables, columns, and relationships.

2. **Querying Data**: Writing SQL queries to retrieve data from different tables in the database, such as `film`, `customer`, `rental`, `staff`, and `payment`.

3. **Data Analysis (Optional)**: Analyzing the retrieved data to answer specific questions and uncover insights related to customer behavior, movie popularity, rental trends, and staff performance.

4. **Visualization (Optional)**: Visualizing the analysis results using charts, graphs, and dashboards to make the insights more accessible and understandable.

5. **Reporting (Optional)**: Summarizing the key findings and insights in a report or presentation format, along with recommendations for business improvement.

## Dataset
The DVD rental database contains the following tables:

- `film`: Information about movies, including title, description, release year, length, rating, and genre.
- `actor`: Information about actors, including first name and last name.
- `customer`: Information about customers, including first name, last name, email, and address.
- `rental`: Information about rentals, including rental ID, rental date, return date, customer ID, and inventory ID.
- `staff`: Information about staff members, including first name, last name, email, and store ID.
- `payment`: Information about payments, including payment ID, amount, payment date, and customer ID.

## Tools and Technologies
The analysis will be conducted using SQL in conjunction with a database management system (DBMS) such as PostgreSQL, MySQL, or SQLite. Additionally, tools for data visualization may be used to create charts and graphs to visualize the analysis results.

## Project Structure
The project will be organized into the following directories and files:

- **README.md**: This document provides an overview of the project, its objectives, methodology, dataset, tools, and project structure.
- **queries/**: This directory contains SQL query files used for data retrieval and analysis.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
