# SQL Project - Data Cleaning and Exploratory Data Analysis #

## Overview
This project involves cleaning and analyzing the Layoffs from 2020 to 2023 dataset obtained from Kaggle. The objective is to prepare the data for analysis and gain insights into layoffs trends in various industries.

## Dataset Source
The dataset used for this project is from Kaggle: [Layoffs Dataset](https://www.kaggle.com/datasets/swaptr/layoffs-2022).

## SQL Project
- The SQL file provided contains the code for data cleaning and exploratory data analysis.
- Steps include creating a staging table, removing duplicates, standardizing data, examining null values, and removing unnecessary data.

## Documentation of Steps
1. **Create Staging Table**: 
   - A staging table named `layoffs_staging` is created to work with the raw data. This allows us to maintain the original data intact.

2. **Remove Duplicates**: 
   - Duplicate rows are identified and removed from the staging table to ensure data integrity.

3. **Standardize Data**: 
   - Data standardization techniques are applied to fields such as industry names and country names to ensure consistency and uniformity.

4. **Handle Null Values**: 
   - Null values are examined and handled appropriately. Blank values are converted to null, and missing values in certain fields are populated based on other entries.

5. **Data Cleanup**: 
   - Unnecessary columns and rows are removed from the dataset to streamline further analysis.

  **Exploratory Data Analysis (EDA)**
   - Explored the dataset to find trends, patterns, and outliers.
   - Investigated the extent of layoffs by analyzing total numbers and percentages.
   - Examined companies with significant layoffs, both in terms of absolute numbers and percentages.
   - Explored trends over time by analyzing layoffs per year and per month.
   - Investigated layoffs based on location, country, industry, and company stage.

## Results
- Identified companies with the largest layoffs and observed trends over time.
- Analyzed the impact of layoffs on different industries and geographic regions.
- Explored outliers, such as companies with high percentages of employees laid off.
- Gained insights into the scale and distribution of layoffs, providing valuable information for further analysis or decision-making processes.

## Conclusion
- This README provides an overview of the data cleaning process for the Layoffs 2022 dataset. By following systematic steps, the dataset is now ready for exploratory data analysis and further insights into layoffs trends across industries. .


