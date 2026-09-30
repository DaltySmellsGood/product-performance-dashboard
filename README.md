# Product Performance Dashboard

## Project Overview

This project analyzes how products perform in the "Superstore Dataset" to reach actionable conclusions regarding the products that produce the highest profit. This project utilizes Power Query, Microsoft Excel, and Power BI to create an interactive dashboard examining how products perform from this dataset. The product category "Furniture" performed significantly worse despite each category contributing roughly the same amount of revenue. It is suggested that more resources should be put towards a higher performing category (i.e. Technology) and less towards the furniture category.

## Table of Contents

- [Business Questions](#business-questions)
- [Dataset](#dataset)
- [Tools Used](#tools-used)
- [Step 1: Data Validation and Preparation](#step-1-data-validation-and-preparation)
- [Step 2: Exploratory Data Analysis (EDA)](#step-2-exploratory-data-analysis-eda)
- [Step 3: Profitability Analysis](#step-3-profitability-analysis)
- [Step 4: Power BI Dashboard](#step-4-power-bi-dashboard)
- [Key Results](#key-results)
- [Business Recommendations](#business-recommendations)
- [Dashboard](#dashboard)
- [Repository Structure](#repository-structure)
- [What I learned](#what-i-learned)

---

## Business Questions

1. Which product category generates the highest revenue?
2. Which product category returns the most profit?
3. Which product category sells the most volume?
4. Does the product category with the most revenue/volume produce the most profit?
5. Which product categories should management prioritize?
6. What factors contribute to the success of a product category?

---

## Dataset

**Source:** Superstore Dataset

**Time Period:** January 2014 - December 2017

**Records:** 9,994

The Superstore Dataset contains transactional data. Information includes: products sold, quantity, sales, and profit. Each record has a unique Row ID value, which acts as the primary key in the dataset.

---

## Tools Used
- Power Query
- Excel
- Power BI

---

## Methodology

### Step 1: Data Validation and Preparation

The dataset was imported into Microsoft Excel and reviewed using Power Query to ensure data quality before analysis. The validatioin process included:

- Verifying data types for all variables
- Checking for missing or null values
- Reviewing the dataset for duplicate records
- Confirming date fields imported correctly
- Examining sales, profit, quantity, and discount variables for unusual values

The dataset contained 9,994 transaction records spanning multiple years of retail sales activity.



*This screenshot shows how the data was validated using Power Query*

### Step 2: Exploratory Data Analysis (EDA)

An exploratory analysis was conducted to better understand the structure of the dataset and identify potential areas for investigation.

Key metrics examined included:

- Date range of transactions
- Product categories and sub-categories
- Regional distribution
- Sales volume
- Profitability patterns
- Frequency of negative-profit transactions

This phase helped establish a foundation for subsequent business analysis.



*This screenshot shows the Excel sheet where the key metrics were recorded*

### Step 3: Profitability Analysis

Pivot Tables and Pivot Charts were used to summarize performance across multiple business dimensions.

This analysis focused on:

- Revenue by product category
- Profit by product category
- Quantity sold by product category
- Profitability by product sub-category
- Regional performance comparisons
- Discount-level performance

A Profit Margin metric was calculated using:
```text
Profit Margin = Total Profit / Total Sales
```
This metric was used to evaluate how effectively sales revenue translated into profit.



*This screenshot the Excel sheet where the Pivot Tables and Charts were created*

### Step 4: Power BI Dashboard

Findings from the previous analysis were documented and used to guide dashboard development. Power BI was used to create an interactive dashboard that allows users to explore sales performance through filters and visualizations.

The dashboard includes:

- Total Revenue
- Total Profit
- Quantity Sold
- Profit Margin
- Revenue by Category
- Profit by Category
- Profit by Product Sub-Category
- Impact of Discount Rate on Profitability

Interactive Slivers were added for:
- Date Range
- Product Category
- Region

These features allow users to explore trend and compare performance across different segments of the business.

---

## Key Results
- Copiers contributed over $55,000 in profits, but accounted for less than a percent in total volume sold.
- Furniture contributed about a third of total revenue, but had a profit margin of ~2.5%
- Bookcases and tables accounted for about $320,000 in revenue for furniture, but resulted in a loss of $20,000 in profits.
- Technology generated the highest revenue and profit despite selling the fewest units.
- Average profit becomes negative once discounts reach approximately 30%
- The central region performs the poorest as indicated by the profit margin of 7.92%
- The west region produced the strongest overall profitability

---

## Business Recommendations


---

## Dashboard


---

## Repository Structure

```text
Product-Performance-Dashboard/
│
├── data/        # Raw and exported datasets used in Excel analysis
├── Excel/       # Excel spreadsheet where data analysis occured      
├── Power BI/    # Power BI dashboard file
└── README.md    # Project documentation
```

---

## What I Learned


---