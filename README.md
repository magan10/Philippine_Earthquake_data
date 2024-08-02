# Analyzing Seismic Activity: A Study of Earthquakes in the Philippines (2020-2024)

## Introduction
This project provides an in-depth analysis of seismic activity in the Philippines from 2020 to 2024. The analysis focuses on understanding patterns and trends in earthquake occurrences.

## Table of Contents
- [Introduction](#introduction)
- [Data Sources](#data-sources)
- [Methodology](#methodology)
  - [Data Collection](#data-collection)
  - [Data Cleaning](#data-cleaning)
- [Visualization](#visualization)

## Data Sources
The data used in this analysis is sourced from:
- [Philippine Institute of Volcanology and Seismology (PHIVOLCS)](https://www.phivolcs.dost.gov.ph/index.php/earthquake/earthquake-information3)

## Methodology

### Data Collection
The data was collected using web scraping techniques. Here’s a brief overview of the process:
1. **Data Scraping**: We used Python libraries such as `BeautifulSoup` and `Requests` to scrape earthquake data from various online sources.
   - **BeautifulSoup** was used to parse HTML and extract relevant data from web pages.
   - **Requests** was used to send HTTP requests and retrieve the raw HTML content.
2. **Data Aggregation**: The scraped data was then aggregated and structured into a usable format.

### Data Cleaning
After collecting the data, the next step was data cleaning:
1. **Cleaning Process**: We used the `Pandas` library to clean and preprocess the data. This included tasks such as:
   - Handling missing values
   - Removing duplicates
   - Standardizing data formats
2. **Exporting Data**: Once cleaned, the data was exported to a CSV file for use in subsequent analysis and visualization.
   - The cleaned data can be found in the `cleaned_data.csv` file.

### Analysis
Analysis was conducted using Tableau to visualize trends and patterns in the data.

## Visualization
The results of the analysis are visualized using Tableau. View the interactive dashboards and visualizations below:
![Sample Visualization](https://public.tableau.com/app/profile/restituto.rodeo/viz/Philippine_Earthquake_Data2020-2024/Dashboard1)
