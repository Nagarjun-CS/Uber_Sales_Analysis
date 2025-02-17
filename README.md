# Uber Sales Analysis

## Project Overview
This project analyzes Uber's quarter-over-quarter (QoQ) sales performance based on ride and fare data. The analysis includes different vehicle types, pickup locations, trip distances, travel times, and total fares to gain insights into revenue distribution and ride patterns. The objective is to understand sales trends, vehicle-wise revenue contributions, and customer ride behavior.

## Features and Approach

### Features
The insights from this analysis are visualized in the **Tableau Dashboard**, which provides:
- **Average Trip Distance & Travel Time**: Identifying variations in trip duration and distance.
- **Revenue Distribution by Vehicle Type**: Analyzing which vehicle types contribute the most to total revenue.
- **Total Fare Breakdown**: Visualizing tolls, tips, surcharges, and other fare components.
- **Location-Based Insights**: Understanding ride frequency and revenue trends across different pickup locations.

### Approach
The solution follows a structured ETL and visualization pipeline, as depicted in the **Solution Architecture Diagram**:
1. **Data Sources**: Two Excel files containing Uber ride and fare details.
2. **Exploratory Data Analysis (EDA)**: Conducted using Python to clean and analyze data.
3. **ETL Process**: Implemented using **SQL Server Integration Services (SSIS)** to extract, transform, and load data into the database.
4. **Database Management**: Data is stored and managed in **SQL Server Management Studio (SSMS)**.
5. **Visualization & Reporting**: Final insights are displayed using **Tableau**.

## Files in the Repository

- **Uber_ETL/** – Contains all ETL-related project files.
- **Dashboard.png** – Tableau dashboard showcasing Uber sales insights.
- **Solution architecture.png** – Diagram illustrating the end-to-end ETL pipeline.
- **Uber Input Data.zip** – Compressed folder containing the input Excel datasets.
- **Uber_ETL.sln** – Solution file for the ETL pipeline built using SSIS.


## Tools & Technologies Used
- **Python** – Data preprocessing and exploratory analysis
- **SSIS (SQL Server Integration Services)** – ETL process implementation
- **SQL Server Management Studio (SSMS)** – Database storage and querying
- **Tableau** – Data visualization and reporting

---

Feel free to update or customize this **README** as needed!
