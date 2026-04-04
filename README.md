# Chocolate Sales Dataset – Description

## Dataset Source
- **Platform:** Kaggle
- **Title:** Chocolate Sales Dataset
- **File:** Chocolate_Sales_2.csv

## Dataset Dimensions
- **Rows:** 3,284 (raw) → 3,282 after cleaning
- **Columns:** 6

## Description of Features (Columns)

| Column | Data Type | Description |
|---|---|---|
| Sales Person | String | Full name of the sales representative who made the sale |
| Country | String | Country where the sale transaction took place (6 unique: Australia, Canada, India, New Zealand, UK, USA) |
| Product | String | Name of the chocolate product sold (22 unique products) |
| Date | String → DateTime | Transaction date in DD-MM-YYYY format (range: Jan 2022 – Aug 2024) |
| Amount | String → Float | Sale value in USD, originally stored as formatted string (e.g., "$5,320.00") |
| Boxes Shipped | Integer | Number of chocolate boxes shipped for the transaction |

## Purpose of Using This Dataset

This dataset was selected for the ARTI406 Machine Learning assignment because:

1. **Real-world structure** – It contains a mix of data types (text, numbers, dates, currency strings) requiring realistic data cleaning steps.
2. **Multiple analytical dimensions** – Sales can be analysed by geography, product, salesperson, and time — enabling diverse and meaningful visualisations.
3. **Clear business context** – The chocolate sales domain is easy to interpret, making insights straightforward to explain.
4. **Appropriate size** – With ~3,280 transactions across 3 years and 6 countries, it is large enough for meaningful EDA but not overwhelming.
5. **ML potential** – After cleaning, this data is suitable for regression (predict Amount), classification (high/low value deal), or time-series forecasting.

## Key Statistics (after cleaning)
- Total Revenue: $19,791,571.86
- Average Sale: $6,030.34
- Date Range: 2022-01-03 to 2024-08-31
- Unique Sales Persons: 25
- Unique Products: 22
- Countries: Australia, Canada, India, New Zealand, UK, USA
