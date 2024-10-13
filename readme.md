# Chicago Crimes Data Analysis

This project is focused on analyzing and visualizing crime data in Chicago. The data was sourced from a public dataset and has been cleaned and transformed to reveal insights such as crime trends, types of crimes and geographical hotspots.

## Project Overview

The objective of this project is to provide an in-depth analysis of crimes committed in Chicago using Power BI for visualization. The analysis covers the most common crimes, geographic crime hotspots, arrest patterns, and trends over time. The dataset includes information on crime types, locations, and arrest statuses from various years, with a focus on the most recent data for 2024.

### Key Questions Addressed:

- What are the most common crimes committed in Chicago?
- Which areas in Chicago experience the highest concentration of crimes?

## Dataset Source:

The dataset is sourced from [**Google BigQuery**](https://console.cloud.google.com/bigquery?p=bigquery-public-data&d=crypto_sui_mainnet_us&page=dataset&project=versatile-field-438118-t7&ws=!1m5!1m4!4m3!1sbigquery-public-data!2schicago_crime!3scrime) and was extracted via **Google BigQuery**. It includes crimes from 2021-2024, with detailed records of each crime including:

- **Crime Type** (Primary Type)
- **Description** of Crime
- **Date** and Time
- **Location** (Block, Community Area, Ward)
- **Arrest Status** (Whether an arrest was made)
- **Geographical Coordinates** (Latitude, Longitude)

### Data Cleaning:

The data was cleaned and transformed to remove null values, fix date formats, and ensure consistency in crime categories. The cleaned dataset is included in this repository for further analysis and visualization.

**Before: Getting the dataset**

![getting data from BigQuery](<Images/0. Getting dataset from Big Query.png>)

**After: Extracting the data**

![data extraction](<Images/1. Querying dataset on Big Query.png>)

**Before: Removing null values**

![removing null values in power bi](<Images/2.1 null values - before.png>)

**After: Removing null values**

![removing null values in power bi](<Images/2.2 null values - after.png>)

**Before: Cleaning up date column**

![data cleaning in power bi](<Images/2.5 date column - before.png>)

**Before: Cleaning up date column**

![data cleaning in power bi](<Images/2.6 date column - before.png>)

**After: Cleaning up date column**

![data cleaning in power bi](<Images/2.7 date column - after - extracted only the date values and changed data type to date.png>)

**After: Renaming columns**

![renaming columns in power bi](<Images/4.1 changing column names.png>)

## Tools Used

- **Power BI Desktop**: For data cleaning and transformation, data visualization and reporting.
- **BigQuery**: For data extraction.
- **GitHub**: For version control and collaboration.

## Key Visualizations and Insights

1. **Most Common Crimes in Chicago**:

   - Theft, battery, and deceptive practices were found to be the most common crimes in Chicago, based on 2024 data.

2. **Crime Hotspots**:

   - Geographical mapping revealed hotspots in downtown areas, especially near **Fulton River District** and **West Loop**.

![chicago crimes data analysis](<Images/5. crimes in chicago.png>)
