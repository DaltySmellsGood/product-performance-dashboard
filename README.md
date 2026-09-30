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
- [Dashboard](#dashboard)
- [Key Results](#key-results)
- [Business Recommendations](#business-recommendations)
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

## Dashboard


---

## Key Results

- **Copiers** were the most profitable product sub-category, contributing over **$55K in profit** despite accounting for less than **1% of total units sold**.
- **Furniture** generated roughly **32% of total revenue** but only **6% of total profit**, resulting in a profit margin of approximately **2.5%**.
- **Tables** and **Bookcases** were unprofitable Furniture sub-categories, producing over **$320K in combined revenue** while generating a combined loss of approximately **$21K**.
- Average transaction profit became negative when discounts reached approximately **30% or greater**, suggesting that aggressive discounting was associated with reduced profitability.
- **Technology** was the strongest-performing category, generating approximately **$836K in revenue** and **$145K in profit** despite selling fewer units than Office Supplies.
- **Office Supplies** accounted for the highest sales volume (**22,906 units sold**) but generated less revenue and profit than Technology, demonstrating that sales volume alone was not the primary driver of profitability.
- The **West** region achieved the strongest financial performance, producing the highest revenue, profit, and profit margin (**14.94%**).
- The **Central** region was the weakest-performing region, generating a profit margin of only **7.92%**, substantially below the overall average (**12.47%**).

---

## Business Recommendations

### 1. Review the Furniture Product Category

Furniture generated approximately **32% of total revenue** but only **6% of total profit**, indicating significantly lower profitability than other categories. Further investigation into pricing, supplier costs, and product mix may help identify opportunities to improve margins.

### 2. Evaluate Underperforming Furniture Sub-Categories

**Tables** and **Bookcases** generated more than **$320K in combined revenue** but resulted in an estimated **$21K loss**. Management should review these product lines to determine whether pricing adjustments, cost reductions, or inventory changes are warranted.

### 3. Monitor High Discount Levels

Average transaction profit became negative when discounts reached approximately **30% or greater**. Implementing discount guidelines or requiring additional review for higher discount levels may help protect profitability while maintaining sales volume.

### 4. Investigate High-Margin Product Segments

**Copiers** generated over **$55K in profit** despite representing less than **1% of total units sold**, suggesting that certain products contribute disproportionately to overall profitability. Similar high-margin products may present opportunities for targeted marketing or sales efforts.

### 5. Analyze Drivers of Technology Category Performance

The **Technology** category generated the highest revenue and profit across all categories. Understanding the factors contributing to this performance—including product mix, pricing strategy, and customer demand—may provide insights that can be applied to other product categories.

### 6. Examine Regional Performance Differences

The **West** region achieved the highest profit margin (**14.94%**), while the **Central** region produced the lowest (**7.92%**). Additional analysis of regional sales practices, customer behavior, and product mix may help explain these differences and identify opportunities for improvement.

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

Through this project, I strengthened my ability to move from raw data to actionable business insights using a combination of Excel, Power BI, and Git.

Key skills developed include:

- Using **Power Query** to validate datasets by checking data types, missing values, and duplicate records.
- Performing exploratory and profitability analysis in **Excel** using Pivot Tables, Pivot Charts, calculated fields, and conditional formulas.
- Creating and interpreting business metrics such as **profit margin**, category performance, and discount impact.
- Designing interactive **Power BI dashboards** with KPI cards, visualizations, and slicers to communicate findings effectively.
- Improving dashboard development efficiency by applying lessons learned from previous Power BI projects.
- Using **Git Bash** and GitHub to track project progress, commit changes incrementally, and maintain version control throughout the project.
- Translating analytical findings into business insights and recommendations supported by data.

This project reinforced the importance of looking beyond revenue alone and demonstrated how profitability, product mix, discounting practices, and regional performance can significantly influence business outcomes.

---