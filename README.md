# Data Cleaning Using SQL

## Introduction

Data cleaning might be the least glamorous part of any data professional’s work, but it’s the backbone of quality analysis! Determined to challenge myself, I embarked on a data cleaning project using a dataset called "Layoffs". It was a tiresome journey, but I made it through—alive and with a clean dataset! 


## Objective

To import the Layoffs dataset into a MySQL server, clean it, and prepare it for exploratory or advanced data analysis.


## Methodology

Using SQL, I systematically transformed the raw dataset into a clean, ready-to-analyze version by:


1. Creating a staging table:

Copied the structure of the original dataset into a new staging table.
Ensured the original dataset remained untouched, adhering to best practices.

2. Adding unique identifiers:

Created a column with row numbers since the dataset lacked unique identifiers.
This was essential for identifying and managing duplicate records.

3. Removing duplicates:

Identified and deleted duplicate rows in the staging table.

4. Standardizing data:

Ensured consistency across the dataset, such as formatting dates and normalizing text.

5. Handling missing values:

Replaced null or blank values with appropriate placeholders or removed incomplete rows where necessary.

6. Removing irrelevant columns:

Dropped unnecessary fields that added no value to the analysis.

This project was a great reminder of the importance of clean data in analytics and how SQL can be a powerful tool for the job. If you're interested in the details, check out the code and dataset transformations in the repository!

