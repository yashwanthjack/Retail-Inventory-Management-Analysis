# Retail Inventory Management Analysis

This project provides a comprehensive analysis of retail inventory data to help businesses manage stock levels and identify high-performing products.

## Overview

Efficient inventory management is crucial for retail success. This project analyzes a retail dataset to:
- Monitor stock levels across different stores.
- Identify "fast-moving" items based on weekly sales volume.
- Perform Time-Series Trend Analysis to understand purchasing behavior.
- Extract correlation matrices using multi-dimensional heatmaps.
- Evaluate existing demand forecasting accuracy against historical performance.
## Dataset

The analysis is based on `Retail inventory.csv`, which includes the following features:
- **Store**: The identifier for the retail outlet.
- **Product**: The name of the item.
- **Weekly_Sales**: Total sales revenue for the week.
- **inventory level**: Categorical indicator of current stock (0 for low, 1 for adequate).
- **Temperature**: Prevailing temperature during the sales week.
- **Past promotion**: Promotional spend in lacs.
- **demand forecast**: Expected demand.

## Analysis Steps

1. **Data Cleaning & Processing**: Handling missing values, ensuring correct data types, and scaling dates to chronologically valid datetime objects for time-series extraction.
2. **Exploratory Data Analysis (EDA)**: Visualizing inventory distribution and store performance.
3. **Speed Metrics**: Ranking products by sales velocity to identify top-performing (fast-moving) items.
4. **Summary Statistics**: Generating descriptive counts and means for key variables.
5. **Time-Series Analysis**: Examining temporal fluctuations in overall weekly sales, spotting periodicity or unique spikes.
6. **Correlation & Relationships**: Presenting a Pearson correlation matrix formatted as a heatmap to observe how factors like temperature, prior promotion spend, and demand metrics act on product sales.
7. **Demand Forecast Evaluation**: Validating the alignment of historical demand predictability versus actual historical execution scaling.

## How to Run

1. Ensure you have Python installed.
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open `inventory-data-analysis.ipynb` in Jupyter Notebook or VS Code to view the complete analysis.

---
*Created as part of the Retail Inventory Management Analysis Project.*
