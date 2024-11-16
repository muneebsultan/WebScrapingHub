# ETL Pipeline for Scraping Data from Finviz

This script implements a complete ETL (Extract, Transform, Load) pipeline for scraping financial data from Finviz. It performs the following steps:

- Extract: The script scrapes tables from the Finviz website using the html_read method.
- Transform: The scraped data is cleaned and transformed as needed (e.g., filtering columns, formatting, or aggregating).
- Load: The transformed data is saved into a database for further analysis or processing.