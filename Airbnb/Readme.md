# Airbnb Data Cleaning and Dashboard Project

## 📄 Project Overview

This project involves cleaning and analyzing Airbnb dataset using Microsoft Excel. The goal was to transform raw data into meaningful insights and visualize key metrics through a dashboard.

## 📊 Dataset

The dataset used in this project is `airbnb.xlsx`, which includes various listings and associated information such as:

- Listing ID
- Room Type
- Price
- Minimum Nights
- Number of Reviews
- Availability
- Neighbourhood

## 🧹 Data Cleaning Steps

The following steps were performed to clean the dataset:

1. **Removed Duplicates:** Ensured that there are no repeated rows in the dataset.
2. **Handled Missing Values:** Replaced or removed any cells with missing or NA values.
3. **Formatted Data Types:** Converted columns to appropriate data types (e.g., price to currency, dates to proper format).
4. **Trimmed Whitespace:** Removed extra spaces from text fields.
5. **Renamed Columns:** Renamed headers for clarity and consistency.
6. **Created Calculated Columns:** Added new columns for metrics like total revenue (`Price * Minimum Nights`) and review rate per month.

## 📈 Dashboard Features

The final dashboard was created using Excel Pivot Tables and Charts. It includes:

- **Total Listings by Neighbourhood**
- **Average Price by Room Type**
- **Availability Heatmap**
- **Top Reviewed Listings**
- **Revenue Estimations**

## 🧰 Tools Used

- Microsoft Excel
  - Pivot Tables
  - Pivot Charts
  - Conditional Formatting
  - Data Cleaning Functions
