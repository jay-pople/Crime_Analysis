## Overview:
This project provides an in-depth analysis of U.S. crime trends from 2020 to 2024, aiming to offer valuable insights to law enforcement agencies, policymakers, researchers, and the general public.
By examining crime patterns across different cities, demographics, and case statuses, the project seeks to support data-driven decisions that enhance public safety and crime prevention strategies.

## Files:
us_crime_dataset.xlsx
Crime_Analysis.pbix

## Requirements:
Power BI Desktop
crime dataset (included in repository)

## Questions:
Q1.By what percentage has the crime rate increased or decreased in different cities over the past five years?

Q2.Which crime is happend most serious or less serious?also show the crime the crime catagory of eac

Q3.At what time crime is happend most day or night ? also show for each city.

Q4. In which area most of crime happed? as per seriousness or crime catgory.

Q5.Is there any pattern of crime in year, eg. increases in certain period and decreases in certain period? for different crime category.

Q6.show year wise case status, wheather pending or close?

Q7. which weapon is widly used for different crime category? 

## Data Preparation: 

1) Import the data : Import the us_crime_dataset.xlsx into power BI
   
2) Data Transformation :
  a)Handling Missing and Null Values:
  Identified missing values in critical columns, including incident details, demographics, and location information.
  For fields with essential missing data, used imputation methods when feasible; otherwise, omitted entries with incomplete records.

  b)Standardizing Data Formats:
  Converted dates to a standardized date-time format for accurate time-based analysis.
  Ensured categorical fields, like crime categories, locations, and case statuses, followed consistent naming conventions for easier grouping and analysis.

  c)Categorical Consistency:
  Merged similar or redundant categories, aligning alternate labels (e.g., different names for similar crimes or locations) into a unified format.
  Ensured weapon descriptions and crime types were standardized to prevent duplication and inconsistencies.
  Outlier Analysis and Correction:

  d)Time-Based Classification:
  Added columns to classify incidents by time of day (e.g., day/night) based on time stamps, which supports time-specific crime analysis.

## Conclusion: 


