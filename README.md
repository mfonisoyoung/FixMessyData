## FixMessyData

FixMessyData is an automation workflow built with Make.com that cleans and standardizes messy data in Google Sheets.
It detects inconsistencies, fixes formatting issues, fills missing values, and updates your sheet automatically—so you can work with reliable, structured data without manual cleanup.

## Features
-Detects inconsistent or messy data
-Automated data cleaning and standardization
-Supports rule-based transformations (example NG → Nigeria)
-Handles missing values and basic data enrichment
-Removes or flags duplicate entries
-Maintains a simple audit trail of changes
-Works directly with Google Sheets
-Easy to extend with APIs or additional logic

## How It Works
1. Data Input
Connects to Google Sheets
Retrieves raw data from selected rows or columns

3. Preprocessing
Normalizes raw input (trims spaces, formats values)
Detects column types (text, number, date, etc.)
Converts data into a structured format for processing

4. Issue Detection: The system scans for common data problems:
-Missing values
-Duplicate rows
-Inconsistent formats (e.g., USA to United States)
-Invalid entries (emails, phone numbers, etc.)

5. Cleaning Layer
Data is cleaned using a hybrid approach:
-Rule-based logic:
-Predefined mappings (example: country codes)
-Format standardization
-Validation rules

Optional AI support:
Fixes messy or unstructured text
Corrects typos
Infers missing context (when applicable)

5. Validation

Before updating the sheet:
-Compares original vs cleaned values
-Ensures only valid transformations are applied

6. Update Engine
Writes cleaned data back to Google Sheets
Can overwrite or highlight updated values
Supports manual or automated triggers

## Workflow Overview
Google Sheets → Data Processing → Cleaning → Validation → Update Sheet
 
  Use Cases
-Cleaning user-submitted form data
-Standardizing location or country fields
-Preparing datasets for analysis
-Automating repetitive spreadsheet cleanup tasks
