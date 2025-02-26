# Exploratory Data Analysis (EDA) on Layoff Trends Using SQL
## Project Overview
This project explores global layoff trends using SQL to analyse key patterns in employment reductions. The dataset, layoffs_staging2, contains information on layoffs across different companies, countries, and time periods. The analysis uncovers trends, identifies companies with the highest layoffs, and evaluates the impact of layoffs over time.

## Key Analyses & Queries
**Dataset Overview**: Displays the full dataset to understand its structure.
**Max Layoffs & Percentage Laid Off**: Identifies the highest recorded layoffs and companies where 100% of employees were laid off.
**Layoffs by Company**: Aggregates total layoffs per company, ranking them in descending order.
**Time-Based Analysis**: Analyses layoffs by year and month to detect spikes and long-term trends.
**Country-Wise Layoffs**: Summarises layoffs by country to compare regional impacts.
**Startup Stage Analysis**: Groups layoffs by company funding stage to see which types of companies faced the most reductions.
**Rolling Total Analysis**: Uses window functions to calculate cumulative layoffs over time.

## Tools & Technologies Used
SQL (Aggregations, Window Functions, Grouping, and Date Manipulation)
MySQL (Compatible with most SQL databases)

## Insights & Findings
Companies in later funding stages tend to have higher total layoffs.
The most significant layoffs occurred in specific months/years, hinting at industry-wide downturns.
Some companies had 100% layoffs, indicating complete shutdowns.
Layoffs are not evenly distributed across industries or regions, with some countries experiencing significantly higher job cuts.

## How to Use
Load the layoffs_staging2 dataset into a SQL database.
Run the SQL queries in the script to explore different aspects of layoff trends.
Modify the queries to dig deeper into specific industries, countries, or company sizes.
