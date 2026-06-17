# Customer Behaviour Analysis

## Overview

This Data Analytics project focuses on analyzing customer shopping behaviour using Python, PostgreSQL, and Power BI. The goal is to uncover purchasing patterns, customer preferences, revenue trends, and key business insights through data analysis and visualization.

---

## Dataset

The project uses a customer shopping behaviour dataset containing information such as:

* Customer demographics (Age, Gender)
* Product categories and items purchased
* Purchase amounts
* Subscription status
* Shipping methods
* Payment methods
* Review ratings
* Purchase frequency
* Customer locations

---

## Tools & Technologies

* **Python**

  * Pandas
  * NumPy
  * Matplotlib

* **PostgreSQL**

  * Data storage
  * SQL-based analysis

* **Power BI**

  * Interactive dashboard creation
  * Data visualization

---

## Project Steps

### 1. Data Loading & Exploration

* Imported dataset using Pandas
* Reviewed dataset structure and data types
* Explored key variables and distributions

### 2. Data Cleaning

* Checked for missing values
* Verified data consistency
* Prepared data for analysis

### 3. Exploratory Data Analysis (EDA)

* Analyzed customer demographics
* Examined purchasing behaviour
* Identified revenue trends across categories and age groups
* Explored customer subscription patterns

### 4. SQL Analysis (PostgreSQL)

Performed SQL queries to answer business questions such as:

* Revenue by category
* Revenue by age group
* Customer subscription analysis
* Top-performing products
* Geographic revenue analysis
* Customer purchase behaviour trends

### 5. Power BI Dashboard

Created an interactive dashboard to visualize:

* Total Customers
* Average Purchase Value
* Average Review Rating
* Revenue by Category
* Revenue by Age Group
* Top 3 States by Revenue
* Top 5 Most Purchased Products
* Subscription Status Distribution

---

## Dashboard Highlights

The dashboard provides a quick overview of customer behaviour through:

* KPI Cards
* Bar Charts
* Donut Charts
* Interactive Filters and Slicers

Users can filter results by:

* Subscription Status
* Gender
* Category
* Shipping Type

---

## Key Results

* Clothing generated the highest revenue among product categories.
* Customer spending patterns varied across age groups.
* A small number of states contributed significantly to total revenue.
* Certain products consistently appeared among the most purchased items.
* Most customers were non-subscribers, while subscribers represented a smaller segment of the customer base.

---

## How to Run

### Python Analysis

1. Open the Jupyter Notebook file.
2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib
   ```
3. Run all notebook cells.

### PostgreSQL Analysis

1. Create a PostgreSQL database.
2. Import the dataset.
3. Execute the SQL queries provided in the `.sql` file.

### Power BI Dashboard

1. Open the `.pbix` file in Power BI Desktop.
2. Refresh the data source if required.
3. Explore the interactive dashboard.

---

## Repository Structure

```text
customer_behaviour_analysis/
│
├── customer_shopping_behaviour_dataset.csv
├── customer_behaviour_analysis_jupyter_notebook.ipynb
├── customer_behaviour_analysis_sql.sql
├── customer_behaviour_analysis_dashboard.pbix
└── README.md
```

## Author

Satyam Ghai

Data Analytics Project demonstrating the integration of Python, PostgreSQL, and Power BI for end-to-end data analysis and visualization.

