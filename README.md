# Sales & Stock Analysis – BottleNeck Wine Retailer

## Context
Freelance Data Analyst mission for BottleNeck, a premium wine merchant.
The company operated two disconnected systems — an ERP and an online 
shop — with no automated data bridge between them. The goal was to 
manually reconcile both sources and deliver actionable sales insights.

## Objectives
- Merge ERP product data (references, prices, stock status) with 
  online shop data (product descriptions, sales volume) using a 
  liaison table
- Calculate revenue per product and total online revenue
- Detect pricing anomalies and outliers in the product price variable

## Data Sources
- **erp.xlsx** – Internal ERP export: product references, prices, stock
- **web.xlsx** – Online shop export: product info, cumulative sales
- **liaison.xlsx** – Manual mapping table linking ERP product_id to 
  web SKU references

## Deliverables
- Cleaned and merged dataset reconciling both systems
- Revenue breakdown per product + total online revenue
- Outlier analysis on prices with visualizations
- Jupyter Notebook presented at COPIL steering committee meeting

## Tools & Skills
- Python (pandas, matplotlib)
- Data merging and reconciliation
- Outlier detection and statistical analysis
- Exploratory data analysis (EDA)

## Key Learnings
Handling imperfect real-world data (incomplete mapping table, naming 
inconsistencies), reconciling heterogeneous sources and communicating 
findings through a clean, documented notebook.
