# athletic_sales_analysis# Sales Data Analysis Project

## Overview
This project focuses on analyzing sales data to uncover insights into sales trends, customer behaviors, and product performance. The analysis involves working with sales data from different months, with a focus on understanding patterns and trends in sales activities.

## Data Preparation
- Sales data for different months (January, February, and March 2019) was imported and read into pandas DataFrames.
- The 'order_date' column was converted to a datetime datatype to facilitate time-series analysis.
- The data was then combined to form a comprehensive dataset encompassing sales from all months.

## Analysis Conducted

### General Sales Analysis
- Sales data was analyzed to understand trends and patterns.
- Key metrics such as total sales, average prices, and item quantities were calculated using both `groupby` and `pivot_table` methods.

### Product-Specific Analysis
- The dataset was filtered to focus on specific product sales, such as the iPhone.
- Analysis on the filtered dataset included understanding sales distribution across different regions (state, city, and zip code).

### Temporal Analysis
- Sales data was resampled to understand daily and weekly trends.
- This involved creating pivot tables indexed on the 'order_date' and analyzing total sales on a daily and weekly basis.

## Conclusions
- The project provided valuable insights into sales trends over different time periods and for various products.
- It highlighted key areas and products driving sales, offering actionable insights for business strategy and decision-making.

## Future Work
- Further analysis can be extended to include more products and additional time frames.
- Comparative analysis across different years or quarters could provide deeper insights into sales trends and customer preferences.
