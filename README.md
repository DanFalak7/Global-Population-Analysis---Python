# Global-Population-Analysis - Python

### Project Overview

This project analyzes global population trends from 1960 to 2025 using Python.

The objective of this analysis is to:

- Clean and standardize multi-source population datasets
- Integrate ISO country codes for consistent merging
- Map countries to their respective regions
- Analyze continental population growth trends
- Identify the most and least populated countries globally and by region

This project demonstrates data cleaning, data merging, transformation, aggregation, and exploratory data analysis (EDA) using real-world global population data.

### Dataset Description

The project combines three datasets:

- Population Data (2025)
- Population Data (1960–2024)
- Annual population figures by country
- 3-letter ISO country codes
- Region classification (continent-level grouping)

### Tools

- Python
- Pandas (Data cleaning & transformation)
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### Data Cleaning & Preparation

The following steps were performed to ensure data quality:
- Selected relevant columns from raw datasets
- Renamed columns for clarity and consistency
- Removed whitespace inconsistencies
- Dropped rows with missing ISO codes
- Manually mapped missing ISO codes
- Merged multiple datasets using ISO codes
- Cleaned and standardized region classifications
- Reorganized columns for structured analysis

The final dataset contains:
- Country
- Region
- Annual population values (1960–2025)

### Exploratory Data Analysis (EDA) And Data Visualization

The analysis includes:

#### 1.  Population Growth Rate by Region (1961–2025)
- Calculated yearly percentage growth rate by continent
- Visualized long-term regional growth trends

#### 2.  Population Distribution by Region (2025)
- Aggregated total 2025 population by region
- Compared continental population sizes

#### 3.  Top 10 Most Populated Countries (2025)
- Identified countries with the highest population counts
- Visualized global population concentration

#### 4.  Regional Deep Dive
For each region:
- Top 10 most populated countries
- Top 10 least populated countries

This highlights regional distribution disparities and demographic imbalances.

### Findings
- Africa shows the strongest sustained growth trend in recent decades, while Europe’s growth rate has stabilized.
- Asia accounts for the largest share of the global population.
- Global population is heavily concentrated in a small number of countries.
- Asia remains the most populous region globally.
- Africa demonstrates the highest long-term growth rate.
- Europe shows population stabilization and slower growth.
- Small island territories have extremely low population counts relative to global averages.
- Population growth patterns vary significantly by continent.
