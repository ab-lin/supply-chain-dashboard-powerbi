# Supply Chain Analysis using Power BI

The objective of this project is to perform a comprehensive analysis of global supply chain operations using Power BI. Through data modeling, DAX calculations, and interactive dashboards, this analysis helps stakeholders make informed decisions for operational improvements.

## Dataset Description
The dataset used in this project is DataCoSupplyChainDataset sourced from [Kaggle](https://www.kaggle.com/code/adityabatsexemplary/supply-chain). It represents supply chain operations managed by DataCo Global and contains:

- 53 columns with detailed attributes such as:
    - Sales values
    - Shipment modes and dates
    - Item IDs and customer IDs
    - Country, city, region, and segment information
    - Order processing time, delivery status, delivery dates, and more
- 180,519 rows, where each row represents one transaction involving one item and one customer.

This dataset enables a rich, transaction-level view of global supply chain behavior and performance.

## Project Description
This repository includes all the Power BI files and resources needed to conduct a full-scale analysis of the supply chain data. Using Power Query, the data was preprocessed and cleaned, while DAX was used to generate advanced metrics. A robust data model was built to reflect relationships between key supply chain entities (suppliers, customers, items, shipments).

Key visualizations and KPIs were developed in Power BI to reveal patterns, trends, and operational inefficiencies. The result is a set of interactive dashboards that can be used by business users to drive supply chain optimization strategies.

### Key Features
- Power Query for transforming, merging, and cleaning large datasets
- DAX for creating KPIs and calculations such as: Year-over-Year (YoY) Sales Growth, Orders YoY Change, Total Profits, Delivery Time.
- Data modeling to define relationships across orders, products, customers, and suppliers
- Interactive dashboards including:
    - Delivery timeline analysis
    - Supplier performance comparisons
    - Geographic breakdowns of supply chain activity

## Impact
- In 2017, sales dropped by 4% compared to 2016, but profit increased by 48%, indicating higher profit margins despite the decline in revenue.
- Product Trends
    - Fishing was the top sales category from 2015 to October 2017, averaging over 400 orders/month.
    - No fishing orders after Oct 2017 raises questions—this could indicate a data error, discontinuation, or seasonal/product change.
    - Despite fishing being the leading category, the top product was from the Cleats category, showing that popular products don’t always align with dominant categories.
- 2017 saw 21.87K sales from 11.81M orders, but 54.45% were delivered late, showing a persistent logistics issues.
- This data suggests that while the business made profitability gains, it continues to face serious operational and fulfillment challenges. There's room for improvement in supplier diversification, logistics efficiency, inventory planning, and data quality control. Product-level performance and category dynamics also reveal opportunities for more targeted strategies.


## Dashboards
![dashboard-2015](https://github.com/ab-lin/supply-chain-dashboard-powerbi/blob/main/dashboard-2015.png)
![dashboard-2016](https://github.com/ab-lin/supply-chain-dashboard-powerbi/blob/main/dashboard-2016.png)
![dashboard-2017](https://github.com/ab-lin/supply-chain-dashboard-powerbi/blob/main/dashboard-2017.png)
![dashboard-2018](https://github.com/ab-lin/supply-chain-dashboard-powerbi/blob/main/dashboard-2018.png)
