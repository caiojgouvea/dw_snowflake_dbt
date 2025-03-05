# Vehicle Sales Data Warehouse - SnowFlake, DBT

## Project Description

This project implements a **Data Warehouse** solution for a vehicle sales system using **PostgreSQL**, **DBT**, **Airflow**, **Python**, and **Snowflake**.

The goal of this project is to build an ETL pipeline that extracts data from a PostgreSQL relational database, performs transformations using **DBT** (Data Build Tool), and loads the transformed data into **Snowflake** as the data warehouse.

### Key Technologies Used:
- **PostgreSQL**: The source relational database containing vehicle sales data.
- **DBT**: Used for transforming the data inside the warehouse.
- **Airflow**: Used to orchestrate and automate the ETL pipeline.
- **Python**: Utilized for various scripting tasks and custom transformations.
- **Snowflake**: The cloud data warehouse where the transformed data is loaded.

## Features
- ETL pipeline that extracts data from a PostgreSQL database.
- Data transformation using **DBT**.
- Data loading into **Snowflake** for scalable analytics.
- **Airflow** orchestrates and automates the entire ETL process.
