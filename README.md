# COVID-19 Cases, Deaths, and Vaccination Analysis

## Overview

This project analyzes COVID-19 deaths and vaccination data across multiple countries in **Africa, Asia, Europe, and America**.
The analysis focuses on understanding mortality trends, vaccination progress, and cross-continental comparisons using structured SQL queries and interactive visualizations.

The workflow includes loading datasets into **SQL Server Management Studio (SSMS)**, performing data exploration and analysis using SQL, and building a **Tableau dashboard** for clear and insightful data storytelling.

---

## Dataset

The project uses two primary datasets:

* **COVID-19 Deaths Dataset**
* **COVID-19 Vaccinations Dataset**

**Data Source:** Public COVID-19 datasets
**Format:** Excel (.xlsx)

---

## Tools & Technologies

* **SQL Server Management Studio (SSMS)**

  * Importing CSV data
  * Creating tables and databases
  * Writing SQL queries for data exploration
* **SQL**

  * Filtering, aggregations, joins, and calculations
* **Tableau Public**

  * Connecting to SQL Server
  * Data visualization and dashboard creation
* **GitHub**

  * Project version control and documentation

---

## Project Workflow

1. **Data Loading**

   * Imported COVID deaths and vaccination datasets into SQL Server
   * Created structured tables for analysis

2. **Data Exploration (SQL)**

   * Explored total cases, deaths, and vaccination numbers
   * Calculated death rates and vaccination percentages
   * Joined deaths and vaccinations datasets for combined analysis
   * Filtered data by continent and country

3. **Data Preparation for Visualization**

   * Created SQL views or query outputs for Tableau
   * Ensured clean and analysis-ready datasets

4. **Data Visualization**

   * Connected Tableau Public to SQL Server
   * Built interactive dashboards for trend and comparison analysis

---

## Dashboard

The Tableau dashboard focuses on high-level global and regional COVID-19 metrics, including:

* Global Numbers – total confirmed cases, total deaths, and overall death rate
* Total Deaths per Continent – comparison of COVID-19 fatalities across continents
* Percent Population Infected per Country – proportion of population infected by country
* Percent Population Infected Over Time – trend of infection rates over time
* The dashboard is designed to be intuitive and suitable for both technical and non-technical audiences.

The dashboard is designed to provide a clear overview of the global impact of COVID-19 and enable easy comparison across regions and countries.

---

## Key Results & Insights

* Global COVID-19 data shows significant variation in infection and death rates across continents
* Certain countries experienced a higher percentage of population infected compared to others
* Infection rates increased at different paces across regions, highlighting uneven pandemic progression
* Continental-level analysis reveals disparities in total deaths, reflecting differences in population size and regional impact

---

## How to Run This Project

### 1. Set Up SQL Server

* Open SQL Server Management Studio
* Create a new database
* Import the COVID deaths and vaccination .xlsx files
* Run the provided SQL scripts to explore and prepare the data

### 2. Run SQL Analysis

* Execute SQL queries to analyze deaths, vaccination rates, and trends
* Create views or result sets for visualization

### 3. Open Tableau Dashboard

* Open the Tableau workbook
* Connect to SQL Server
* Refresh the data source
* Explore the interactive dashboard

---

## Notes

* This project is created for educational and portfolio purposes.
* Data accuracy depends on the original public data sources.

---

📊 *This project demonstrates SQL-based data exploration, cross-dataset analysis, and effective data visualization using Tableau for analytical storytelling.*
