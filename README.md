## Project Title
Data-Cleaning-in-Sql

## Demo-Link
N/A


## Table of Contents
[About The Project] (#about—the—project)
[Screenshots] (#screenshots)
[Technologies] (#technologies)
[Approach] (#approach)
[Key Features] (#key features)
[Benefits] (#benefits)
[Status] (#status)
[Credits] (#credits)
[License] (#license)

## About The Project
This project demonstrates various techniques to clean and transform data in a SQL database. The dataset used is from PortfolioProject..Nashvillehousing. The cleaning process includes converting date formats, populating missing data, splitting address columns, standardizing column values, removing duplicates, and deleting unused columns.

## Screenshots
**Screenshots**
![image](https://github.com/user-attachments/assets/abf0d0dc-7aba-496e-9077-51abcde3e6ce)
![image](https://github.com/user-attachments/assets/4d543f8f-16ba-42ba-9da9-9756ec9d1e7c)
![image](https://github.com/user-attachments/assets/4a271434-a336-4e4a-8134-e4bd1885bc42)
![image](https://github.com/user-attachments/assets/6a7dccc7-99cf-423d-890a-a25dd4d87805)
![image](https://github.com/user-attachments/assets/667adf10-8082-4b5b-bd61-54a78c8d19b9)
![image](https://github.com/user-attachments/assets/61dd3686-05f3-4c91-bca1-d810d3ae1856)




## Technologies
- **Microsoft Excel:** A source file which is loaded into the SSMS- Sql server management Studio for cleaning the data 
- **SQL:** Utilized to extract, transform, and analyze housing data data from Excel, to clean the data which includes - Splitting the columns and changing the format and removing the redundancies

## Approach 
- **Data Collection, Preparation, Transformation and Structuring:** SQL was used to extract the excel data which is futher used for running scripts for cleanning, and organizing raw data, removing duplicates and standardizing formats to ensure accuracy. SQL was used to query and aggregate data from Excel, allowing efficient structuring of the housing data.

## Key features
- **Date Format Standardization:** Conversion and alignment of inconsistent date formats for uniformity.
- **Handling Missing Data:** Populating null values in columns like PropertyAddress based on related data (e.g., ParcelID).
- **Data Transformation:** Splitting compound columns (e.g., PropertyAddress and OwnerAddress) into separate fields for better granularity.
- **Value Standardization:** Replacing ambiguous values (e.g., Y/N to Yes/No) for improved readability and consistency.
- **Duplicate Removal:** Identifying and removing duplicate records using ROW_NUMBER with Common Table Expressions (CTEs).
- **Column Optimization:** Deleting unused columns to declutter the dataset and improve performance.
- 
## Benefits 
- **Improved Consistency:** Standardized formats (e.g., dates and categorical values) ensure uniformity across the dataset, reducing errors in analysis.
- **Enhanced Completeness:** Filling missing data and splitting compound columns make the dataset more comprehensive and detailed.
- **Easier Analysis:** Cleaned and organized data simplifies grouping, filtering, and reporting for insights and decision-making.
- **Better Integration:** Consistent and accurate data facilitates seamless integration with other systems and tools.

## Status 
- Data Cleaning in SQL **Completed**

## Credits 
Tools- Microsoft Excel, Microsoft SSMS 


## Contributions:
- Contributions, feedback, and suggestions for improvements are welcome! Whether you have ideas for enhancing visualizations, optimizing data models, or expanding data sources, your contributions are valuable to the ongoing development and enhancement of this project.
