# Marketing Campaign Data Cleaning and Preprocessing

## 📝 Project Objective

This project focuses on the essential data cleaning and preprocessing of a raw marketing campaign dataset. The primary goal is to transform the messy, raw data into a clean, well-structured, and reliable dataset that is ready for exploratory data analysis and visualization.

This task was completed as part of the Elevate Labs Data Analyst Internship program.

---

## 📊 Dataset

The dataset used is the "Customer Personality Analysis" dataset, which contains information about customers of a company. The data includes:

* *Customer Demographics:* Year of birth, education, marital status, income.
* *Household Information:* Number of children and teenagers at home.
* *Purchase History:* Amounts spent on various product categories (wine, fruit, meat, etc.).
* *Promotional Campaign Responses:* Acceptance of offers in several campaigns.
* *Customer Engagement:* Date of enrollment, recency of last purchase, and number of purchases through different channels.

The repository contains two versions of the dataset:
* Raw_data.csv: The original, untouched data with inconsistencies.
* Cleaned_marketing_campaign.xlsx: The final, cleaned version of the dataset.

---

## 🧹 Data Cleaning and Preprocessing Steps

The raw dataset was cleaned and preprocessed to address common data quality issues. The following steps were performed:

1.  *Handled Missing Values:* Identified and addressed missing values, particularly in the Income column. The missing entries were filled with the column's average income to maintain the integrity of the dataset without losing valuable records.

2.  *Removed Duplicate Rows:* Scanned the entire dataset for duplicate entries and removed them to prevent bias in any future analysis.

3.  *Standardized Text Values:* Corrected inconsistencies in categorical columns. For example, in the Education column, values like "Graduation", "graduation", and "GRADUATION" were all standardized to a single format ("Graduation").

4.  *Corrected Date Formats:* The Dt_Customer column, which indicates the customer's enrollment date, was formatted to a consistent dd-mm-yyyy format.

5.  *Renamed Column Headers:* Column names were made more descriptive and uniform for better readability. For example, MntWines was renamed to Amount_Spent_on_Wines.

6.  *Ensured Correct Data Types:* Verified that each column had the appropriate data type (e.g., numerical columns like Income and Year_Birth were set to a number format, and categorical data was set to text).

---

## 🛠 Tools Used

* *Microsoft Excel:* The primary tool used for all data cleaning and preprocessing tasks, utilizing features like 'Go To Special', 'Remove Duplicates', 'Find and Replace', and cell formatting.
* *Python (Pandas):* This project can also be replicated using the Pandas library in Python, which offers powerful functions like isnull(), fillna(), drop_duplicates(), and to_datetime() for efficient data manipulation.

---
