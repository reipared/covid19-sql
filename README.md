# COVID-19 SQL Analysis

## Overview

This SQL script contains various queries to analyze COVID-19 data, focusing on cases, deaths, and infection rates across different locations.

## Queries Included

### 1. General Data Extraction

Retrieves key COVID-19 statistics such as:

- Total cases
- New cases
- Total deaths
- Population

### 2. Total Cases vs. Total Deaths

Calculates the percentage of deaths relative to total cases for each location and date.

### 3. Total Cases vs. Population

Determines the percentage of the population that has been infected with COVID-19.

### 4. Filtering by Location

Queries can be modified to focus on specific regions (e.g., locations containing "states").

### 5. Sorting

Results are sorted by location and date for better readability.

## How to Use

- Run these queries on a database containing the `CovidDeaths` table.
- Modify the `WHERE` clause to focus on specific countries or regions.
- Use the calculated percentages to derive insights on the impact of COVID-19.

## Notes

- Ensure the database structure matches the column names used in these queries.
- Some queries include commented-out filters that can be adjusted as needed.
