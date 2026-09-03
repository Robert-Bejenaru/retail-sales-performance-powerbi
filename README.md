# Retail Sales Performance Analysis — Power BI

## Objective

Build a Power BI report for senior management to monitor sales performance, identify trends, compare regions and product categories, and understand the impact of discounts and costs.

## Dataset

The analysis uses transaction-level retail sales records containing:

- Order information: `OrderID`, `OrderDate`, `ShipMode`
- Customer segmentation: `CustomerSegment`
- Geography: `Country`, `State`, `City`, `Region`
- Product hierarchy: `Category`, `SubCategory`
- Numeric measures: `Quantity`, `UnitPrice`, `Discount`, `Unit_Cost`

The presentation reports **900 distinct and unique OrderID values** and no blank values, data errors or duplicate rows.

## Tools

- Power BI Desktop
- Power Query
- DAX
- Data visualisation and dashboard design

## Analysis Completed

1. Corrected data types and formats for dates, quantity, discounts, unit prices and unit costs.
2. Categorised geographic fields for mapping.
3. Validated data quality and checked for nulls, errors, duplicates and invalid numeric values.
4. Built core DAX calculations.
5. Analysed revenue and profit by year.
6. Compared profit by category and subcategory.
7. Analysed state-level profit.
8. Investigated the relationship between discount bands and profit margin.
9. Produced a senior-management report page.
10. Documented limitations and next-step analysis.

## Key Findings

- Total revenue: **861.15K**
- Total orders: **900**
- Total quantity sold: **2K**
- Total profit: **216.74K**
- Total cost: **644.41K**
- Profit margin: **0.25**
- Revenue declined from **$264,594.06 in 2022 to $261,342.66 in 2023**.
- Profit increased from **$65,398.45 in 2022 to $68,273.75 in 2023**.
- Technology is the leading category by total profit at **$76,911.04**.
- The **21–30% discount band** had the highest overall profit margin, but the effect differed by category.
- The analysis identified potentially inefficient discount bands worth investigating further, including lower-margin bands for specific categories.

## Business Recommendations

- Investigate the reasons for the revenue decline after 2021.
- Review discounting by category/subcategory rather than applying a one-size-fits-all strategy.
- Extend the analysis to customer retention and behaviour.
- Add external market or competitor data before attributing performance changes to internal factors alone.

## Output

![Power BI senior management report](../assets/powerbi-senior-management-report.png)

## Source Material

The dashboard image above is extracted from the project presentation and represents the project output.
