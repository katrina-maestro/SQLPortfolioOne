# SQLPortfolioOne

## Introduction
The COVID-19 Data Analysis project aims to provide insights into the global impact of the COVID-19 pandemic by analyzing data related to cases, deaths, and vaccinations. Using SQL, the project involves querying and manipulating data to understand trends, calculate rates, and compare statistics across different regions and time periods.

## Objectives
Extract and organize COVID-19 case and death data.
Calculate death percentages to understand the severity of the pandemic in different locations.
Compare infection rates to population sizes.
Identify countries with the highest infection and death rates.
Analyze global and regional trends in COVID-19 cases and deaths.
Assess vaccination rates and their impact on populations.

## Methodology
Data Extraction:

Retrieve all records from the covid-vaccinations and COVIDDEATHS tables.

Sorting and Filtering:

Sort data by specific columns to organize the records for better readability and analysis.
Filter records to focus on particular locations (e.g., countries containing 'states').

Calculating Death Percentages:

Calculate the death percentage for specific locations by converting and dividing total deaths by total cases, handling zero values to avoid division errors.
Population and Case Comparisons:

Compare the total cases to the population size to determine the percentage of the population affected by COVID-19.
Use offset and fetch methods to navigate through the dataset for more specific analysis.
Identifying High Infection and Death Rates:

Identify countries with the highest infection rates compared to their population.
Determine countries and continents with the highest total death counts, excluding non-country locations.

Global Overview and Trend Analysis:

Provide a global overview by aggregating daily new cases and deaths.
Calculate death-to-case ratios for a comprehensive understanding of global trends.

Vaccination Analysis:

Analyze vaccination data to determine the percentage of the global population vaccinated.
Use Common Table Expressions (CTEs) and temporary tables to manage and calculate rolling vaccination totals and percentages.

## Results
Organized Data: The data was successfully retrieved, sorted, and filtered to focus on relevant records for analysis.
Death Percentage Calculation: Accurate death percentages were calculated, highlighting the severity of the pandemic in specific locations.
Population and Case Comparison: The analysis revealed the extent of infections in relation to population sizes, providing insights into the spread of the virus.
High Infection and Death Rates: Countries with the highest infection and death rates were identified, allowing for targeted analysis of these regions.
Global Trends: A comprehensive global overview showed daily trends in new cases and deaths, along with death-to-case ratios.
Vaccination Impact: The project provided a detailed analysis of vaccination rates and their impact on populations, showing the progress of vaccination efforts globally.
