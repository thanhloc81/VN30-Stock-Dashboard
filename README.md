# VN30-Stock-Dashboard
<a href="https://project.novypro.com/4JPpvp" target="_blank"> Click here to View the Dashboard!</a>

## Introduction:
VIB Bank - one of the leading banks in Vietnam, wants to assess the situation of
stocks in the Vietnamese market, particularly those in the VN30 group as these are the
top large-cap stocks reflecting the current state of the stock market. They will decide to
invest in several stocks within the VN30 group on the Vietnamese stock market.
Besides the goal of diversifying their investment portfolio, the bank aims to select
the most potential stocks to focus on. VIB Bank has utilized a Business Intelligence
(BI) solution to support the stock selection and investment process.

## Objective:
The objective of the BI solution is to facilitate users in effortlessly and
conveniently assessing the financial status of companies by examining the metrics
within the financial module.

## Tools:
- **Azure databricks:** Get data from VNstocks library in python, then ETL
- **Azure Data Blob Storage:** Store Data in cloud
- **PowerBI:** Visualization.

## Process:
- Process visualization and connection verification between Databricks and Azure Blob Storage is crucial.
- Azure Key Vault used for securing secrets (e.g., Databricks’s secret scope, Azure Blob Storage’s account key).
- ETL process involves extracting data from vnstock3, transforming with Python, and storing in warehouse.
- Data updated daily at 6AM for PowerBI integration to create updated dashboards.

![BI Process drawio](https://github.com/thanhloc81/VN30-Stock-Dashboard/assets/151768013/e4c8de04-e9a3-4353-a1b1-874cf6c9185a)
