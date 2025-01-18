DATA CLEANING USING SQL 

Data Cleaning is like the most boring part of being an 
individual in any data related field.
I decided to get out of my comfort zone and put myself in 
the frying pan and did a data cleaning project on a dataset called layoffs 😂😭.
It was tiresome but thank God I'm still alive.

Objective:

The goal is to import the layoffs dataset to
MySQL server and clean the dataset so that we can 
be able to use it for exploratory data analysis 
or advanced data analysis.

Methodology:
I achieved a clean dataset using SQL by:

1.Creating a new table(staging table) identical to the layoffs dataset 
since we can not perform data cleaning on the original table as it not best practice.

I then created a column with row numbers since there was no columns with unique idenfiers for each row in the dataset.

2.Removing duplicates on the staging table.

3.Standardizing the data.

3.Dealing with null or blank values.

4.Removing any columns that are irrelevant.
