# Superstore Data Analysis Report

## 1. Dataset Overview
The dataset contains 9994 records and 23 columns. It represents sales transaction data for a global superstore.
Key columns include Order Date, Sales, Profit, Category, Region, and Segment.

## 2. Methodology
- **Data Cleaning:** Dates were converted to datetime objects. Duplicates were removed. Missing values were checked.
- **Feature Engineering:** Extracted Year and Month from Order Date for time-series analysis.
- **Tools:** Python (Pandas, Matplotlib, Seaborn).

## 3. Statistics Summary
- **Total Sales:** $2,297,200.86
- **Total Profit:** $286,397.02
- **Average Discount:** 15.62%
- **Profit Margin:** 12.47%

## 4. EDA Results
- **Sales Distribution:** Sales are highly skewed; a log transformation shows a more normal-like distribution, indicating many small transactions and fewer large ones.
- **Category Performance:** Technology generates the highest profit, followed by Office Supplies. Furniture has high sales but lower profit margins.
- **Regional Performance:** The West and East regions are the most profitable.
- **Seasonality:** Sales show a general upward trend with peaks typically occurring towards the end of the year (Q4).

## 5. Key Business Insights
1. **Discount Impact:** High discounts have a strong negative correlation with profit. Care should be taken when offering discounts above 20%.
2. **Furniture Category:** Despite decent sales volume, Furniture struggles with profitability, likely due to shipping costs or high discounts.
3. **Regional Focus:** Marketing efforts should double down on West and East regions while investigating underperformance in the South.

## 6. Recommendations
- **Optimize Discounts:** Implement a cap on discounts, especially for Furniture items, to preserve margins.
- **Inventory Management:** Stock up for Q4 peaks, particularly in the Technology category.
- **Further Analysis:** Investigate shipping costs' impact on the Furniture category's profitability.
