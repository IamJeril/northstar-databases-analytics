# NorthStar Databases and Analytics Coursework

This repository contains the coursework implementation for the Databases and Analytics module based on the NorthStar Urban Mobility and Logistics case study.

## Project Overview

The project investigates NorthStar's operational and data management problems using Python data processing, SQL within R, R analytics and visualisation, MongoDB Atlas NoSQL database design, CRUD operations, aggregation queries, indexing, and query optimisation.

## Repository Structure

- `data/` contains the NorthStar dataset files used for analysis.
- `notebooks/` contains the Google Colab notebooks.
- `report/` contains the final coursework report.
- `screenshots/` contains screenshots used as evidence in the report.

## Notebooks

1. `01_python_data_processing.ipynb`
   - Loads and cleans CSV files
   - Checks missing values and duplicate records
   - Creates delivery duration fields
   - Merges datasets
   - Creates Python analysis charts

2. `02_sql_in_r_analysis.ipynb`
   - Uses SQL within R
   - Creates SQLite database tables
   - Runs SQL joins and aggregation queries
   - Creates R visualisations
   - Demonstrates SQL indexing and explain query plan

3. `03_mongodb_atlas_pymongo.ipynb`
   - Connects to MongoDB Atlas using PyMongo
   - Creates MongoDB collections
   - Inserts customer case, service event, route exception, and app interaction documents
   - Demonstrates CRUD operations
   - Runs aggregation queries
   - Creates indexes and explain plans

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- R
- DBI
- RSQLite
- ggplot2
- MongoDB Atlas
- MongoDB Compass
- PyMongo
- Google Colab

## Security Note

The MongoDB password is not included in the public notebook. Users must replace `YOUR_PASSWORD_HERE` with their own MongoDB Atlas password before running the MongoDB notebook.

## Final Report

The final report is available in the `report/` folder.
