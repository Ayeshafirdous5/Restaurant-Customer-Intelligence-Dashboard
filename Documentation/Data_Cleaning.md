# Data Cleaning & Preparation

## Dataset Overview

Five source datasets from the Maven Analytics Restaurant Ratings dataset were used for this project:

- `consumers.csv`
- `restaurants.csv`
- `ratings.csv`
- `restaurant_cuisines.csv`
- `consumer_preferences.csv`

The datasets were imported into Excel and converted into structured Excel Tables for analysis.

## Data Cleaning Steps

### 1. Dataset Import

- Imported all five source datasets into the Excel working file.
- Reviewed the structure, columns, and key fields of each dataset.

### 2. Excel Table Conversion

- Converted all datasets into named Excel Tables.
- Used structured references for lookup and analysis operations.

### 3. Duplicate Check

- Checked all source tables for duplicate records.
- **2 duplicate records were identified and removed from Consumer Preferences.**
- Other source tables did not contain duplicate records requiring removal.

### 4. Missing Values

- Missing categorical values were reviewed and standardized as **Unknown** where appropriate.
- Missing values were identified in consumer-related fields such as:
  - Smoker
  - Transportation Method
  - Marital Status
  - Children
  - Occupation
  - Budget
- Restaurant ZIP Code blanks were retained because they did not affect the core analysis.

### 5. Data Types

- Reviewed and verified data types across all source tables.
- Ensured numerical, text, and categorical fields were suitable for analysis.

### 6. Text Standardization

- Reviewed categorical values for consistency.
- Standardized category labels and text values to avoid inconsistent grouping during analysis.

### 7. Relationship Validation

- Verified relationships using key fields:
  - `Consumer_ID`
  - `Restaurant_ID`
- Used these relationships to combine relevant consumer, restaurant, cuisine, and rating information for analysis.

### 8. Category Review

- Reviewed categorical values across the datasets.
- Documented important categories and reference values in the workbook's `Category_Reference` sheet.

## Analysis Preparation

After cleaning and validation, the datasets were prepared for:

- PivotTable analysis
- KPI calculations
- Dashboard creation
- Consumer behavior analysis
- Restaurant performance analysis
- Cuisine demand and supply analysis
- Market gap analysis