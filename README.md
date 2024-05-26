[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/1lXY_Wlg)
# MLB Play-by-Play Data Processing Pipeline

## Overview

This project aims to extract and process Major League Baseball (MLB) play-by-play data into structured formats suitable for analytical processing and visualization. The pipeline includes data extraction, transformation, loading (ETL), and visualization using modern data warehousing and business intelligence tools.

## Steps

1. **Extract Game ID for Today's MLB Game**
2. **Extract Data from MLB Play-by-Play API**
3. **Transform Data into Stage Tables**
4. **Create Dimensional Models Using Kimball Method**
5. **Load Data into Snowflake or Databricks Warehouse**
6. **Data Quality Checks with dbt**
7. **Visualization with Power BI, Tableau, Seaborn, or Matplotlib**

## Requirements

- Python
- Apache Spark
- Snowflake or Databricks
- dbt (Data Build Tool)
- Power BI / Tableau / Seaborn / Matplotlib
- Git
## Data Extraction

### 1. Get Game ID

Fetch the game ID for today's MLB game. This can be achieved using an MLB API endpoint.

### 2. Extract Play-by-Play Data

Use the MLB Play-by-Play API to extract detailed game data in JSON format.

## Data Transformation

### 3. Transform Data into Stage Tables

- **Pitcher Play-by-Play Stats Table**
- **Hitter Summary Table**
- **Pitcher Summary Table**

Utilize Spark for transforming the raw JSON data into these stage tables.

### 4. Dimensional Modelling Using Kimball Method

Create the following tables using the Kimball fact-dimensional table method:

- **Pitcher Pitch Type Fact Table**
- **Pitcher Summary Fact Table**
- **Hitter Summary Table**
- **Pitcher and Hitter Is_Active SCD2 Table**
- **Pitch Data Stats Dimensional Table**

## Data Loading

### 5. Load Data into Snowflake or Databricks

Load the transformed data into your data warehouse (Snowflake or Databricks).

## Data Quality Checks

### 6. dbt for Data Quality

Use dbt to perform data quality checks and ensure the integrity and consistency of your data.

## Visualization

### 7. Data Visualization

Visualize the processed data using Power BI, Tableau, Seaborn, or Matplotlib to gain insights.


