# Excel Dashboard Project

This repository contains an Excel dashboard project designed to provide insights and visualizations from a sales dataset. The Excel file (`Excel Dashboard.xlsm`) includes multiple sheets with source data, wireframing, and dashboard components.

## Table of Contents

- [Data Sheets](#data-sheets)
  - [Source Data](#source-data)
  - [Wireframing](#wireframing)
  - [Working Sheet](#working-sheet)
  - [Dashboard](#wireframing-dashboard)

## Project Overview

The Excel Dashboard project aims to deliver a comprehensive view of sales data, including key metrics, trends, and performance indicators.

## Data Sheets

### Source Data

The `Source_data` sheet contains the raw sales data, which includes information such as Order ID, Order Date, Ship Date, Customer ID, Product ID, Sales, Quantity, Discount, and Profit.

Example data from `Source_data`:

| Row ID | Order ID       | Order Date | Ship Date  | Ship Mode    | Customer ID | Customer Name | Segment   | Country      | City           | Sales    | Quantity | Discount | Profit   |
|--------|----------------|------------|------------|--------------|-------------|---------------|-----------|--------------|----------------|----------|----------|----------|----------|
| 1      | CA-2016-152156 | 2016-11-08 | 2016-11-11 | Second Class | CG-12520    | Claire Gute   | Consumer  | United States| Henderson      | 261.9600 | 2        | 0.00     | 41.9136  |
| 2      | CA-2016-152156 | 2016-11-08 | 2016-11-11 | Second Class | CG-12520    | Claire Gute   | Consumer  | United States| Henderson      | 731.9400 | 3        | 0.00     | 219.582  |


### Wireframing

The `Wireframing` sheet is used for planning the layout and structure of the dashboard. It includes preliminary designs and notes to guide the development of the dashboard components.

### Working Sheet

The `Working Sheet` is used for data transformation and calculations that feed into the dashboard. This sheet processes raw data into meaningful metrics and visual elements.

### Wireframing Dashboard

The `Dashboard` sheet contains the final dashboard layout with charts, tables, and interactive elements to visualize the sales data. This sheet leverages Excel's charting capabilities and VBA macros to create a dynamic user experience.

Example data from `Dashboard`:

| Category         | Sales         | Profit        | ... |
|------------------|---------------|---------------|-----|
| Total Sales      | 2,297,201.094 | 286,397.0217  | ... |
| Profit vs PY     | 0.142357      |               | ... |
| ...              | ...           | ...           | ... |

## Usage Instructions

1. **Download the Excel file**: [Excel Dashboard.xlsm](./Excel%20Dashboard.xlsm)
2. **Enable Macros**: Ensure that macros are enabled in your Excel settings to allow the interactive features to function.
3. **Explore the Dashboard**: Navigate through the various sheets to explore the raw data, wireframes, and the interactive dashboard.
4. **Interact with Visualizations**: Use the interactive elements within the `Wireframing_Dashboard` to filter and drill down into the sales data.
