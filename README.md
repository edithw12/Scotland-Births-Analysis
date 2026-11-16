# Scotland-Births-Analysis
A data analysis project exploring births registration statistics in Scotland, examine trends by mother's age at birth, sex, council area and registration seasonality.

# The Project Question
How have demographic shifts in birth patterns (mother's age, sex, seasonality) varied across Scotland's Council areas over the last 30 years, and how can these trends inform local public service planning (e.g., maternity ward staffing and school cap[acity)? 

# Data Sources
Data sourced form the National Records of Scotland (NRS):
Dataset, Coverage, 
Births by council area, year and mother's age, 1991-2024 
Births by council area and sex, 1997-2024
Births registered by month of registration, 1954-2024

Original Data Source:https://www.nrscotland.gov.uk/

Data Set: https://1drv.ms/x/c/d2948d152b4496c4/IQAjKmlwsvjHSpivD8PnHfbcATtfMRhfB5PPCG5eeNfvJE0?e=rHdNnk

Data Selection: I obtained the original dataset from National Records of Scotland and extracted a subset of relevant data for this project. I selected only the fields and records needed to answer the project's analytical questions.

File format: Excel

# Purpose
This dataset was prepared and used for educational purposes as part of my data analytics portfolio.

# Data Cleaning and Preparation
Before importing the data into SQL, the following steps were taken in Excel:
a. Removed unnecessary title rows and metadata from the top of each sheet so column headers moved to Row 1
b. Standardised column names (such as "Year", "Area Name", "All Ages").
c. Split the single Excel workbook into three separate CSV files ('births_age.csv', 'births_sex.csv', 'births_month.csv') to prepare them for SQL database import.





