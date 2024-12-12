## Overview:
This project provides an in-depth analysis of U.S. crime trends from 2020 to 2024, aiming to offer valuable insights to law enforcement agencies, policymakers, researchers, and the general public.  
By examining crime patterns across different cities, demographics, and case statuses, the project seeks to support data-driven decisions that enhance public safety and crime prevention strategies.

---

## Files:
## Crime Dataset
This dataset contains detailed information on U.S. crime data from 2020 to 2024, used in the analysis presented in this repository. You can download it [here](https://drive.google.com/file/d/1S9rWsjTjEpK8K5BFx7JnAKnDzHqgbjvh/view?usp=drive_link).

**Note:** The file is hosted on Google Drive due to its size.

- **Crime_Analysis.pbix**

---

## Requirements:
- **Power BI Desktop**  
- **Crime dataset** (included in repository)

---

## Analysis Conducted (Questions):
1. By what percentage has the crime rate increased or decreased in different cities over the past five years?  
2. Which crimes are the most serious or least serious? Also, show the crime category for each.  
3. At what time does crime happen most—day or night? Also, show this for each city.  
4. In which areas do most crimes occur? Analyze this as per seriousness or crime category.  
5. Is there any pattern of crime throughout the year (e.g., increases or decreases during certain periods) for different crime categories?  
6. Show year-wise case statuses, indicating whether cases are pending or closed.  
7. Which weapon is widely used for different crime categories?  

---

## Snapshot:
![image](https://github.com/user-attachments/assets/6a4ccdf0-4897-4fcc-ad01-f54af79201e3)  
![image](https://github.com/user-attachments/assets/c407a20f-7226-43c4-8df9-709f98a3fb52)  
![image](https://github.com/user-attachments/assets/2a7b3742-72a9-48ab-9dea-793e7af902d1)  

---

## Data Preparation:

### 1. Import the Data:
- Import the `us_crime_dataset.xlsx` into Power BI.

### 2. Data Transformation:

#### a) **Handling Missing and Null Values**:
- Identified missing values in critical columns, including incident details, demographics, and location information.  
- Used imputation methods for fields with essential missing data when feasible; otherwise, omitted entries with incomplete records.

#### b) **Standardizing Data Formats**:
- Converted dates to a standardized date-time format for accurate time-based analysis.  
- Ensured categorical fields like crime categories, locations, and case statuses followed consistent naming conventions for easier grouping and analysis.

#### c) **Categorical Consistency**:
- Merged similar or redundant categories, aligning alternate labels (e.g., different names for similar crimes or locations) into a unified format.  
- Standardized weapon descriptions and crime types to prevent duplication and inconsistencies.

#### d) **Outlier Analysis and Correction**:
- Conducted outlier detection for key metrics to ensure reliable insights.

#### e) **Time-Based Classification**:
- Added columns to classify incidents by time of day (e.g., day/night) based on timestamps to support time-specific crime analysis.

## Conclusion:

This project successfully analyzed U.S. crime trends from 2020 to 2024, uncovering critical insights into crime patterns, case statuses, and weapon usage. A key observation highlights the prevalence of crimes in specific geographic regions, emphasizing the need for targeted safety measures and strategic resource allocation.

Additionally, variations in crime rates by city, time of day, and seasonal patterns provide valuable information for law enforcement agencies to address high-risk areas effectively. These insights pave the way for data-driven decisions that enhance public safety and foster proactive crime prevention strategies.
