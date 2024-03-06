# Crowdfunding_ETL
Group project 2 submission<br>
Contributors: Leonid Lyakhovich, Matthew Mosca
## Context
Demonstrate ETL (Extract, Transform, Load) by building a pipeline using Python, Pandas, and PostgreSQL. Data was extracted from Excel spreadsheets into Python. The data was transformed using list comprehensions, Python dictionaries, and Pandas dataframes. The cleaned and formatted data was exported into comma separated value files. An entity relationship diagram was created and used to load the data into a PostgreSQL database.
## Usage
- **Extract and Transform** - download the ETL_Mini_Project_LLyakhovich_MMosca.ipynb Jupyter Notebook and the Resources folder containing the Excel spreadsheets. Run the Jupyter Notebook to create 4 comma separated value files in the Resources folder.
- **Load** - download crowdfunding_db_schema.sql. Create a new local database in PostgreSQL and use the schema file to create the table structure. For a visualization of the database schema see crowdfunding_entity_relationship_diagram.svg. Load the comma separated value files into their corresponding tables in the following order:
  1) contacts.csv
  2) category.csv
  3) subcategory.csv
  4) campaign.csv
 - The postgresql_screenshots folder contains screenshots demonstrating SELECT * statements on each of the 4 tables.
