This repository contains SQL scripts for cleaning and preparing a housing dataset. The scripts demonstrate best practices for data cleaning and preprocessing, making the data ready for analysis and visualization.

Project Overview

The `Nashville Housing Data Cleaning` project is based on a real-world housing dataset. It includes the following steps:

1. Standardizing Date Formats:
   - Converts date fields into a standard format for consistency.
   - Adds new columns if required to ensure the dataset is properly updated.

2. Populating Missing Data:
   - Fills in missing property addresses using logical joins and conditional updates.

3. Splitting Address Components:
   - Breaks down address fields into separate columns (Address, City, State) for better organization.

4. Transforming Categorical Data:
   - Converts binary fields (`Y` and `N`) into more descriptive values (`Yes` and `No`).

5. Removing Duplicates:
   - Identifies and removes duplicate rows using a Common Table Expression (CTE).

6. Dropping Unused Columns:
   - Eliminates irrelevant columns to streamline the dataset.

Getting Started

To run the scripts:
1. Clone this repository.
2. Import the `NashvilleHousing` dataset into your SQL Server.
3. Execute the scripts in the provided order.

File Structure

- `01_Cleaning_Data.sql`: Main script for all cleaning operations.

Tools and Environment

- SQL Server Management Studio (SSMS): Recommended IDE.
- SQL Language Version: T-SQL.

