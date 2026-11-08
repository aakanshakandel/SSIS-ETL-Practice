# SSIS-ETL-Practice
# SSIS ETL Assessment – SQL Server Integration Services

## Project Overview

This project involved developing ETL (Extract, Transform, Load) workflows using SQL Server Integration Services (SSIS), SQL Server Management Studio (SSMS) and Excel.

Using FAA Wildlife Strikes data, I completed three tasks focused on data extraction, cleaning, automated file processing, SQL Server integration and data aggregation.

## Question 1 – Extracting and Creating Dimension-Style Lookup Files

The first task focused on extracting relevant information from the original FAA Wildlife Strikes dataset and creating separate, cleaned lookup files.

Using SSIS, I:
- Extracted data from the source Excel dataset.
- Selected relevant columns for different categories, including Airports, Runways, Operators, Species and Aircraft.
- Removed duplicate records to ensure each lookup file contained unique values.
- Sorted the extracted data.
- Exported the transformed results into separate Excel files.

**Outcome:** Produced five cleaned, dimension-style Excel lookup files that could be used for further data processing and analysis, including AIRCRAFTS, SPECIES, RUNWAYS, OPERATORS, AIRPORTS.

## Question 2 – Data Aggregation and Reporting Using SQL

The final task focused on transforming and analysing the loaded data to produce an aggregated report.

I:
- Used SQL queries to group wildlife strike records by species.
- Calculated the total number of strikes recorded for each species.
- Sorted the results in descending order to identify species associated with the highest number of strikes.
- Exported the aggregated results into a new Excel file for reporting.

**Outcome:** Generated a summary report showing wildlife strike counts by species, demonstrating how SQL can be used to transform raw records into meaningful analytical information.

## Question 3 - Error Output and Error Handling in SSIS

This task focused on implementing error handling within an SSIS Data Flow using the **Error Output** functionality.

The objective was to manage records that encountered errors during data transformation or loading, rather than allowing them to cause the entire ETL process to fail.

Using SSIS Error Output, problematic records could be redirected to a separate output for further investigation, while valid records continued through the main data flow.

**Key Skills Demonstrated:**
- Configuring Error Output in SSIS.
- Redirecting rows that fail during data processing.
- Separating valid and invalid records.
- Understanding data validation and error handling in ETL pipelines.

**Outcome:** Demonstrated how SSIS Error Output can help identify problematic records and improve the reliability of ETL workflows.

## Skills Demonstrated

- **ETL Development:** Designing workflows to extract, transform and load data.
- **Data Cleaning:** Removing duplicates, selecting relevant fields and sorting datasets.
- **SSIS Automation:** Using loop containers to automate multiple file imports.
- **SQL Server Integration:** Loading and managing data within SQL Server.
- **SQL Analysis:** Using GROUP BY, COUNT and ORDER BY to aggregate data.
- **Reporting:** Exporting processed data into Excel for further analysis.

**Technologies Used:** SSIS, SQL Server, SSMS, SQL, Microsoft Excel.



