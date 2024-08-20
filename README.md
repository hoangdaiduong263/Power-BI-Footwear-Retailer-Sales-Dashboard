# Power-BI-Footwear-Retailer-Sales-Dashboard
Welcome to the PowerBI Footwear Retailer Sales Dashboard project! This dashboard is designed to help footwear retailers analyze and visualize their sales data in an interactive and user-friendly manner. It leverages Power BI's powerful data visualization capabilities to provide insights into sales performance, trends, and key metrics, enabling better decision-making.

**1. Features**

- General View:
  - Visualize Sales, COGS, and Margin for selected categories or all categories over time.
  - Gain insights into the overall financial performance of the retail business.
- Comparative Yearly and Quarterly Analysis:
  - Year-on-Year Sales Comparison: Compare sales performance across different years for selected categories or all categories.
  - Quarter-on-Quarter Sales Comparison: Analyze quarterly sales trends and compare them across multiple quarters.
- Comparative Subcategory Analysis:
  - Compare Sales, Share of Business (SOB%), Gross Margin, and the number of different subcategories within a selected category.
  - Identify which subcategories are driving sales and profitability within a larger product category.

**2. Tools used**

- Google Cloud
  - Cloud Storage (data warehouse):
    - Master data: DistributionChannel.csv (distribution channel information), Master_Calendar.csv (timeframe information), Product.arvo (product features information)
    - Transactional data: Sales.arvo (sales data)
- Power Query and Power BI
  - After the inital cleaning step, the data are loaded into Power Query to recheck if any errors and missing points still exist
  - Finally the data model is setup between tables and dashboard is built
