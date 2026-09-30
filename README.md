# Product Performance Dashboard

## Project Overview

This project analyzes how products perform in the "Superstore Dataset" to reach actionable conclusions regarding the products that produce the highest profit. This project utilizes Power Query, Microsoft Excel, and Power BI to create an interactive dashboard examining how products perform from this dataset. The product category "Furniture" performed significantly worse despite each category contributing roughly the same amount of revenue. It is suggested that more resources should be put towards a higher performing category (i.e. Technology) and less towards the furniture category.

## Table of Contents

- [Business Questions](#business-questions)
- [Dataset](#dataset)
- [Tools Used](#tools-used)
- [Step 1: Data Validation](#step-1-data-validation)
- [Step 2: Exploratory Data Analysis](#step-2-exploratory-data-analysis)
- [Step 3: Category Analysis](#step-3-category-analysis)
- [Step 4: Sub-Category Analysis](#step-4-sub-category-analysis)
- [Step 5: Discount Analysis](#step-5-discount-analysis)
- [Step 6: Region Analysis](#step-6-region-analysis)
- [Step 7: Power BI Dashboard](#step-7-power-bi-dashboard)
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

### Step 1: Data Validation

- Utilized Power Query to check for missing, duplicate, and concerning values
- No apparent concerns were found resulting in a validated data set of 9,994 values


*This screenshot shows how the data was validated using Power Query*

### Step 2: Exploratory Data Analysis (EDA)
- Examine 

### Step 3: Category Analysis


### Step 4: Sub-Category Analysis


### Step 5: Discount Analysis


### Step 6: Region Analysis


### Step 7: Power BI Dashboard

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