# MIS505 Portfolio Project: Belgium Education Enrollment and GDP

April M. Vuylsteke  
Colorado State University Global  
MIS505: Data Wrangling  
Instructor: Dr. Emmanuel Tsukerman  
Module 8 Portfolio Project

## Project Overview

This project combines Belgium's primary school enrollment and GDP per capita data from 2001 to 2020. Both datasets come from the World Bank.

I used Python to clean, organize, and merge the data. I saved the results in CSV and SQLite formats. I also created a JSON file to describe the dataset.

## Data Sources

The project uses two World Bank indicators:

- [Primary school enrollment (SE.PRM.ENRL)](https://data.worldbank.org/indicator/SE.PRM.ENRL): Number of pupils enrolled in primary education.
- [GDP per capita (NY.GDP.PCAP.CD)](https://data.worldbank.org/indicator/NY.GDP.PCAP.CD): GDP per capita in current US dollars.

## Data Processing

I used Python and pandas to read, filter, and clean the source files. I checked for missing values and merged the datasets by year.

The final dataset contains 20 records and three columns: Year, Primary Enrollment, and GDP.

The source data lacks a primary enrollment value for 2020. I kept this value missing rather than estimating it.

## Project Files

| File | Description |
|---|---|
| `Belgium_Education_GDP.csv` | Final merged dataset |
| `Belgium_Education_GDP.db` | SQLite database with 20 records |
| `Belgium_Education_GDP_description.json` | JSON data dictionary |
| `MIS505_Module8_PortfolioProject_AprilVuylsteke.ipynb` | Python notebook |
| `MIS505_Module8_PortfolioProject_AprilVuylsteke.html` | Notebook with code and results |

## Tools

I used Python, pandas, SQLite, JSON, and JupyterLab to complete the project.

## Notes

The project prepares data for future analysis. It does not test whether GDP affects school enrollment.

The notebook uses local Windows file paths. Users must update these paths before running the code.

## References

World Bank. (n.d.). *School enrollment, primary (number)*. https://data.worldbank.org/indicator/SE.PRM.ENRL

World Bank. (n.d.). *GDP per capita (current US$)*. https://data.worldbank.org/indicator/NY.GDP.PCAP.CD