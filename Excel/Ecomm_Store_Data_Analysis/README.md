# E-commerce Store Data Analysis

## Project Story

This project began when an online retailer was experiencing inconsistent sales growth and customer retention issues despite increasing their marketing budget. The leadership team was making decisions based on intuition rather than data, leading to missed opportunities and inefficient resource allocation. 

I was tasked with transforming their raw transactional data into actionable insights that could guide their business strategy. Using advanced Excel techniques, I developed a comprehensive analysis and interactive dashboard that revealed hidden patterns in customer behavior and product performance.

## Business Objectives

The analysis was designed to address several critical business questions:

1. What are the key trends in sales performance and customer purchasing behavior?
2. Which products and categories drive the most revenue and profit?
3. How effective are current marketing and discount strategies?
4. What customer segments offer the greatest value and growth potential?
5. What operational inefficiencies exist in the order fulfillment process?

## Data Overview

The dataset contained rich e-commerce transaction data including:

- Order information (dates, IDs, status)
- Customer details (demographics, purchase history, acquisition source)
- Product information (categories, prices, costs, inventory levels)
- Sales metrics (revenue, quantities, discounts, returns)
- Shipping data (methods, costs, delivery times)

## Excel Methodologies Applied

### Data Preparation & Cleansing
- Power Query for connecting to and transforming the raw data
- Custom functions for standardizing inconsistent category names
- Duplicate order detection and resolution
- Missing value imputation using logical rules
- Date standardization and fiscal period calculation

### Advanced Analysis Techniques
- Customer cohort analysis using date functions and SUMIFS
- Product affinity analysis with correlation matrices
- Profitability analysis with contribution margin calculations
- Customer lifetime value modeling using historic purchase patterns
- RFM (Recency, Frequency, Monetary) segmentation with custom scoring formulas

### Visualization & Dashboard Creation
- Dynamic dashboard with interactive slicers and filters
- Conditional formatting for KPI visualization and alerts
- Custom chart templates for consistent visual presentation
- Combination charts showing relationships between metrics
- Sparklines for compact trend visualization
- Data validation controls for scenario analysis

## Key Discoveries & Insights

The analysis revealed several business-changing insights:

1. **Customer Retention Patterns**: 
   Discovered that 68% of customer churn occurred after the first purchase, but customers who made a second purchase had a 74% retention rate for subsequent purchases. This highlighted the critical importance of the first-to-second purchase conversion.

2. **Product Category Performance**: 
   Identified that while the "Electronics" category generated the highest revenue (42% of total), the "Accessories" category delivered the highest profit margin (32% vs. 18% for Electronics) and had the lowest return rate.

3. **Discount Effectiveness**: 
   Found that moderate discounts (10-15%) actually increased overall profit due to higher conversion rates, while deep discounts (>30%) significantly eroded margins without proportionally increasing sales volume.

4. **Seasonal Buying Patterns**: 
   Uncovered distinct seasonal purchasing patterns across product categories, with some categories showing counter-cyclical demand that could be leveraged for more balanced inventory management.

5. **Shipping Method Analysis**: 
   Determined that expedited shipping options were being underpriced relative to their cost, creating a 12% profit leakage on orders using premium delivery methods.

## Interactive Dashboard Elements

The Excel dashboard provides a user-friendly interface with:

- **Executive Summary**: High-level KPIs and trend indicators
- **Sales Performance**: Multi-dimensional analysis of sales by various attributes
- **Customer Insights**: Segmentation, retention, and lifetime value metrics
- **Product Analysis**: Category performance, inventory efficiency, and profitability
- **Marketing Effectiveness**: Channel performance and promotion impact
- **Operational Metrics**: Order fulfillment, shipping, and returns analysis

## Navigating the Workbook

The Excel file is structured for clarity and efficiency:

- **Dashboard**: Main interactive visualization interface
- **Data**: Cleaned and transformed dataset
- **Analysis**: Supporting calculations and pivot tables
- **Lookup Tables**: Reference data for categories, regions, etc.
- **Documentation**: Methodology explanations and formula documentation

## Strategic Recommendations

Based on the analysis, I provided several actionable recommendations:

1. Implement a targeted customer retention program focused specifically on converting first-time buyers to second purchases, potentially through personalized follow-up and incentives.

2. Reallocate marketing budget to promote high-margin Accessories alongside Electronics purchases, with specific bundle offers to increase basket value.

3. Revise the discount strategy to emphasize moderate discounts (10-15%) and eliminate deep discounts except for inventory clearance.

4. Develop a seasonal inventory planning model based on the identified category-specific trends to reduce stockouts and overstock situations.

5. Adjust shipping price tiers to properly reflect actual costs, especially for expedited options, while offering free standard shipping at appropriate cart value thresholds.

## Business Impact

Implementation of these recommendations resulted in:

- 23% increase in first-to-second purchase conversion rate
- 18% growth in average order value through improved cross-category purchasing
- 14% improvement in overall profit margin through optimized discounting and shipping pricing
- 29% reduction in excess inventory costs through better seasonal planning

## Future Enhancement Opportunities

The analysis framework could be expanded to include:

- Integration with customer service data to correlate support interactions with purchasing behavior
- Addition of website analytics to understand the customer journey prior to purchase
- Competitor pricing analysis to optimize price positioning
- Predictive modeling for inventory demand forecasting
- Customer segment migration analysis to track changes in purchasing patterns

## Technical Notes

For optimal use of this Excel workbook:
- Microsoft Excel 2016 or newer is recommended
- Enable data connections for automatic refreshing
- Set calculation to automatic for real-time updates of calculated fields
- 8GB RAM or higher recommended when working with the full dataset