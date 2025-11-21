# Superstore Sales Performance Dashboard

## Overview

This repository contains a Power BI dashboard designed for comprehensive analysis of Superstore sales data. The project provides an interactive and dynamic way to visualize key performance indicators (KPIs) and supports data-informed decision-making across various customer segments, regions, and product categories.

## Key Features and Metrics

The dashboard is built around a set of explicit measures and key dimensions, making it highly interactive and optimized for the Power BI Q&A feature.

### Core Metrics (KPIs)
| Metric | Calculation | Purpose |
| :--- | :--- | :--- |
| **Total Sales** | SUM of Sales | Core revenue metric. |
| **Total Profit** | SUM of Profit | Core profitability metric. |
| **Total Quantity** | SUM of Quantity | Measures total volume of items sold. |
| **Profit Margin (%)** | Total Profit / Total Sales | Key efficiency ratio. |

### Key Dimensions (Slicers)
The dashboard allows slicing of data based on the following dimensions:
* **Region:** Breakdown by geographical region (e.g., West, East).
* **Segment:** Analysis by customer segment (Consumer, Corporate, Home Office).
* **Sub-Category:** Performance analysis for specific product types.
* **State:** Geographical distribution of sales and profit (Map Visual).
* **Order Date:** Trend analysis over time (Line Chart).

## Data Source

The project utilizes the `Superstore.csv` file, which is a standard transactional sales dataset. The file is located in the root of this repository.

## Setup and Usage

### Prerequisites

* **Power BI Desktop:** Required to view and interact with the `.pbix` file.
* **Git:** Required for cloning and updating the repository files.

### Steps to Run the Dashboard

1.  **Clone the Repository:**
    Navigate to the directory where you want to store the project and run:
    ```bash
    git clone [https://github.com/prathamesh-satav/Superstore-Sales-Performance-Dashboard.git](https://github.com/prathamesh-satav/Superstore-Sales-Performance-Dashboard.git)
    cd Superstore-Sales-Performance-Dashboard
    ```
2.  **Open the Project:**
    Locate the Power BI file (`.pbix`) within the cloned directory and open it with Power BI Desktop.
3.  **Refresh Data:**
    If the underlying `Superstore.csv` file is updated, open the Power BI file and click **Refresh** on the **Home** tab to load the latest data.

## Power BI Q&A Optimization

The model is optimized for natural language querying. You can generate quick visualizations using the format: **`[Dimension] [Metric] [Visual Type]`**.

* **Example Query 1:** `Region Total Sales Donut`
* **Example Query 2:** `Sub-Category Profit Margin Funnel Chart`
