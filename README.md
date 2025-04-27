# Adidas U.S. Sales Analysis 

## Overview

This project analyzes Adidas’s U.S. sales data to uncover actionable insights and business recommendations for optimizing product mix, marketing spend, and city/retailer-specific growth. The work is part of the DATACRUX challenge hosted by Analytical Arena – The Data Science Club, IIT Patna.

## Problem Statement

Adidas has observed fluctuating profits and uneven performance across product categories and regions in the U.S. The leadership team seeks to identify:
- Areas with high growth potential
- Underperforming categories
- Patterns in consumer behavior

**Your role:** Act as a data analyst/scientist to help Adidas:
- Reallocate marketing budgets more effectively
- Optimize the product mix for better profitability
- Recommend city or retailer-specific growth strategies

## Dataset

The dataset contains Adidas U.S. sales transactions with fields such as:
- Retailer, State, City
- Product Category (Apparel, Street Footwear, Athletic Footwear)
- Units Sold, Price, Total Sales, Operating Margin
- Sales Method (Online, Outlet, In-store)
- Gender Type

**Source:** [AdidasSalesdata-1.xlsx](https://tinyurl.com/data-crux)

## Project Structure

```
adidas-sales-analysis/
│
├── AdidasSalesdata-1.xlsx       # Dataset
├── analysis.py                  # Main analysis and visualization code
├── avg_margin_by_category.png   # Visualization output
├── total_sales_by_category.png  # Additional visualization (optional)
└── README.md                    # Project documentation (this file)
```

## How to Run

1. **Install dependencies**
   ```bash
   pip install pandas matplotlib openpyxl
   ```

2. **Place the dataset**  
   Ensure `AdidasSalesdata-1.xlsx` is in your working directory.

3. **Run the analysis**
   ```bash
   python analysis.py
   ```

4. **Outputs**
   - Console: Key insights and business recommendation
   - Files: Bar charts (`avg_margin_by_category.png`, `total_sales_by_category.png`)

## Deliverables

- **3 Key Insights** (clear, concise, impactful)
- **1 Visualization** (chart screenshot)
- **1 Business Recommendation** (under 100 words)

## Sample Insights

1. Street Footwear drives the highest profits across regions, with margins often 0.4–0.55 and large sales volumes.
2. Retailer and channel performance is uneven; outlet and online channels for footwear have higher margins than apparel.
3. Apparel underperforms in margin and volume, especially women’s apparel, indicating a need for product refresh or marketing repositioning.

## Sample Business Recommendation

> Focus marketing and inventory investment on Street Footwear, especially in urban centers and through outlet and online channels, as these yield highest profits and sales growth. Reallocate budget from underperforming Apparel lines to support new product launches or targeted campaigns in footwear. Pilot city-specific promotions in Philadelphia and Houston where Street Footwear dominates, and consider a product refresh or promotional push for Apparel to boost profitability.

## License

This project is for educational and competition use only.

