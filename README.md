# bintel-01-intro

[![Workflow Guide](https://img.shields.io/badge/Pro--Guide-pro--analytics--02-green)](https://denisecase.github.io/pro-analytics-02/workflow-b-apply-example-project/)
[![Python 3.14](https://img.shields.io/badge/python-3.14%2B-blue?logo=python)](./pyproject.toml)
[![MIT](https://img.shields.io/badge/license-see%20LICENSE-yellow.svg)](./LICENSE)

> Professional Python project: introducing business intelligence and smart sales data.


# Project Description

## Business Problem

The original project analyzed **total sales by region** and **total sales by product category** to identify which regions and product categories generated the most revenue.

For this custom project, the focus was changed to answer a different business question:

**Which regions and product categories have the highest average sale amount per transaction?**

Average transaction value provides insight into customer spending behavior rather than overall sales volume. This helps identify where customers make larger purchases, even if those regions or product categories do not generate the highest total revenue.

## Project Modifications

The following changes were made to the original application:

* Renamed the analysis functions to reflect the new purpose.
* Changed the aggregation method from `.sum()` to `.mean()` to calculate the average sale amount per transaction.
* Updated the Region visualization from **Total Sales by Region** to **Average Sale Amount per Transaction by Region**.
* Updated the Product Category visualization from **Total Sales by Product Category** to **Average Sale Amount per Transaction by Product Category**.
* Updated chart titles, axis labels, log messages, and documentation to reflect the new analysis.

## Business Value

This analysis helps identify where customers spend the most money during individual purchases instead of simply identifying where the highest overall sales occur. Understanding average transaction value can support business decisions related to pricing strategies, promotions, merchandising, and customer purchasing behavior.




## Working Files

You'll work with these areas:

- **data/raw** - raw smart sales CSV files (customers, products, sales)
- **docs/** - project narrative and documentation
- **src/bizintel/** - the app is an example; run only (no need to modify)
- **pyproject.toml** - update authorship & links
- **zensical.toml** - update authorship & links

## Run script
```shell
uv run python -m bizintel.app_wmiller
uv run python -m bizintel.app_stellar_analytics
```
