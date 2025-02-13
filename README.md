## Simple ETL Pipeline
This repository contains a simple Python-based ETL (Extract, Transform, Load) pipeline implemented in a Jupyter Notebook. The project demonstrates how to extract data from a CSV file, transform it using pandas, and load it into a SQLite database.

### Project Overview
ETL pipelines are essential for data engineering and analytics workflows. This project provides a beginner-friendly example of how to build an ETL pipeline using Python.

### Pipeline Steps
- **Extract**: Read data from a CSV file.
- **Transform**: Clean and process the data (e.g., handle missing values, filter rows, and rename columns).
- **Load**: Store the transformed data into a SQLite database.

### Features
- **Data Extraction**: Reads data from a CSV file using pandas.
- **Data Transformation**:
    - Handles missing values by dropping rows with null values.
    - Filters rows based on specific conditions (e.g., age > 18).
    - Renames columns to lowercase for consistency.
- **Data Loading**: Saves the transformed data into a SQLite database table.

### Technologies Used
- **Python**: Core programming language.
- **Pandas**: For data manipulation and transformation.
- **SQLite**: Lightweight database for storing the processed data.
