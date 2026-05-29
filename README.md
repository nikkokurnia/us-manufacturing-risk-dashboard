# US Manufacturing Supply Chain Risk Dashboard
## Project Overview

This project analyzes U.S. manufacturing data to forecast demand and monitor supply chain risk. The goal is to create a business-style analytics project using Python, Excel, and Power BI.

The project uses manufacturing time-series data such as new orders, shipments, inventories, and unfilled orders. Python was used for data cleaning, forecasting, model comparison, and risk scoring. Power BI was used to build an interactive dashboard, and Excel was used to create a scenario model for testing supply chain risk assumptions.

## Business Problem

Manufacturing companies need to monitor demand changes, shipment activity, inventory buildup, and backlog pressure. When demand drops while inventory or backlog rises, companies may face higher operational risk.

This project answers:

How can manufacturing demand trends and supply chain risk be monitored using historical data, forecasting models, and interactive dashboards?

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Excel
- Power BI

## Project Workflow

1. Cleaned historical manufacturing data using Python.
2. Created supply chain KPIs from new orders, shipments, inventories, and unfilled orders.
3. Built demand forecasting models using a 12-month moving average and linear trend model.
4. Compared forecast accuracy using MAE, RMSE, and MAPE.
5. Created supply chain risk scores based on demand, inventory, backlog, and shipment pressure.
6. Built an interactive Power BI dashboard.
7. Built an Excel scenario model to test how demand changes, inventory buildup, and backlog pressure affect risk.

## Key Features

- Demand forecasting for manufacturing new orders
- Forecast model comparison using MAE, RMSE, and MAPE
- Supply chain risk scoring by manufacturing category
- Interactive Power BI dashboard with slicers
- Excel scenario analysis model
- Risk detail table for drilling into specific manufacturing records

## Main Outputs

### Python Outputs

- `powerbi_demand_forecast_clean.csv`
- `powerbi_model_comparison_clean.csv`
- `supply_chain_risk_output.csv`

### Power BI Output

- `manufacturing_supply_chain_dashboard.pbix`

### Excel Output

- `manufacturing_scenario_model.xlsx`

## Key Findings

The 12-month moving average model performed better than the linear trend model in the final forecast comparison because it had lower forecast error.

The risk scoring model classified manufacturing observations into Low, Medium, and High risk. Most observations were Low risk, which is expected because the model is designed as an early warning system. Medium and High risk records identify periods where demand, inventory, backlog, or shipment pressure may require attention.

## Dashboard Preview

This project includes an interactive Power BI dashboard saved in the `powerbi` folder and an Excel scenario model saved in the `excel_model` folder.

## Data Source

Data used in this project comes from the U.S. Census Bureau Manufacturers' Shipments, Inventories, and Orders (M3) Survey, including historical time-series data for new orders, shipments, inventories, and unfilled orders.

Source: U.S. Census Bureau M3 Survey  
https://www.census.gov/manufacturing/m3
Historical data:
https://www.census.gov/manufacturing/m3/historical/timeseries.html
