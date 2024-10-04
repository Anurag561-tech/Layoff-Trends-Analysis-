# Layoffs Dataset Analysis

## Introduction

In this project, we analyze a layoffs dataset to uncover insights related to layoffs across various companies over the past few years. The dataset includes details on the number of employees laid off, the percentage of layoffs relative to the workforce, the industry, and additional contextual information about the companies. The analysis is structured into two main components: Data Cleaning and Exploratory Data Analysis (EDA). 

The objective of this project is to clean the dataset to ensure its quality and integrity, followed by a thorough exploration of the data to extract meaningful insights and trends that can inform stakeholders about the impacts of layoffs in different sectors.

## Process

### Data Cleaning

The data cleaning process consists of several key steps:

1. **Data Inspection:**
   - An initial selection of records was made from the `layoffs` table to understand the structure and contents of the data.

2. **Creating a Staging Table:**
   - A staging table (`layoffs_staging`) was created to hold a copy of the original dataset for cleaning.

3. **Removing Duplicates:**
   - Duplicate records were identified and removed based on several columns to maintain data integrity.

4. **Handling Null Values:**
   - Rows with NULL values in important columns were updated, and empty strings were standardized to ensure consistency.

5. **Standardizing Data Types:**
   - The data types were ensured to be appropriate, particularly for the `date` column, to facilitate analysis.

### Exploratory Data Analysis (EDA)

After cleaning the data, various exploratory analyses were performed to derive insights:

1. **Basic Statistics:**
   - Maximum layoffs and percentage laid off were calculated to understand the scale of the layoffs.

2. **Identifying Companies with Complete Layoffs:**
   - Companies with 100% layoffs were filtered for further analysis to understand the extreme cases.

3. **Companies with the Most Layoffs:**
   - Companies were ranked based on total layoffs to identify which companies experienced the most significant impacts.

4. **Annual Layoff Trends:**
   - Analysis of total layoffs per year revealed trends over time, helping to visualize how layoffs have changed.

5. **Rolling Total of Layoffs:**
   - A rolling total of layoffs per month was calculated to visualize trends and understand the fluctuations in layoffs.

## Conclusion

This project successfully demonstrates a comprehensive approach to data cleaning and exploratory analysis using SQL. The cleaning process ensured the quality and reliability of the data, while the exploratory analysis revealed significant trends and insights related to layoffs across various industries and regions. 

The findings from this analysis can provide valuable context for stakeholders looking to understand the implications of layoffs in today's economic landscape. Future work could involve further analysis or visualization of the data to enhance insights and support decision-making.
