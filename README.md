# Retail_Customer_Behavior_analysis

# Data Analytics Project

## Overview

This project demonstrates an end-to-end **data analytics workflow**, from loading and cleaning raw data to extracting insights using SQL and presenting findings through an interactive **Power BI dashboard**.

The project focuses on transforming raw data into meaningful business insights using **Python, SQL, and Power BI**, followed by a detailed report and presentation.

### Key Objectives

* Load and understand the dataset using Python
* Perform Exploratory Data Analysis (EDA)
* Clean and prepare the data for analysis
* Perform business-focused analysis using SQL
* Create an interactive Power BI dashboard
* Identify key trends, patterns, and insights
* Prepare a final analytical report
* Present findings through a professional PPT created using Gamma

---

## Dataset

The dataset contains structured business data used to analyze trends, performance, and key metrics.

**Dataset format:** CSV / Excel
**Data processing:** Python
**Database:** MySQL 

---

## Tools & Technologies

| Tool                                | Purpose                                 |
| ----------------------------------- | --------------------------------------- |
| **Python**                          | Data loading, cleaning, and EDA         |
| **Pandas**                          | Data manipulation and analysis          |
| **SQL**                             | Data querying and business analysis     |
| **MySQL**                           | Database management                     |
| **Power BI**                        | Interactive dashboard and visualization |
| **Gamma**                           | Presentation/PPT creation               |

---

## Project Workflow

```text
Raw Dataset
     ↓
Load Data using Python
     ↓
Data Exploration
     ↓
Data Cleaning & Preprocessing
     ↓
EDA & Visualization
     ↓
Load Data into SQL Database
     ↓
SQL Analysis & Business Queries
     ↓
Power BI Dashboard
     ↓
Insights & Recommendations
     ↓
Final Report
     ↓
Presentation using Gamma
```

---

```
<img width="1466" height="805" alt="image" src="https://github.com/user-attachments/assets/f71042b2-db59-4dc1-a84b-66c4fa2a3dbb" />

## Key Insights from Dashboard

Subscription Status:-
Only 27% of customers are subscribed, while 73% are not.
Opportunity: Focus on subscription campaigns to convert non‑subscribers, as this could drive recurring revenue.

Revenue by Category:-
Clothing generates the highest revenue and sales, followed by Accessories.
Footwear and Outerwear lag behind → marketing or bundling strategies could boost these categories.

Customer Demographics:-
Young Adults contribute the highest revenue and sales.
Middle‑aged customers are the second largest group.
Seniors and Adults show lower engagement → targeted campaigns could increase their participation.

Average Metrics:-
Average Purchase Amount: $59.76 → indicates mid‑range spending behavior.
Average Review Rating: 3.75 → slightly below “good,” suggesting room for product/service improvement.

Shipping Preferences:-
Multiple shipping options are available, but analysis could reveal which drives higher satisfaction or repeat purchases.
Free shipping or faster delivery may improve ratings and retention.

## Suggested Color Palette for Dashboard
<img width="1536" height="1024" alt="Copilot_20260922_091308" src="https://github.com/user-attachments/assets/8fd9a36b-6042-4f99-bd62-7fd910261d21" />
Primary Blue: #1E88E5
Emerald Green: #43A047
Amber Yellow: #FDD835
Crimson Red: #E53935

## Steps Performed

### 1. Data Loading

The dataset was imported into Python using Pandas.

Key activities:

* Loaded CSV/Excel data
* Inspected rows and columns
* Checked data types
* Reviewed dataset structure
* Identified important variables

---

### 2. Exploratory Data Analysis (EDA)

EDA was performed to understand the dataset and identify trends and potential data-quality issues.

Analysis included:

* Dataset dimensions
* Descriptive statistics
* Missing-value analysis
* Duplicate-value analysis
* Unique-value analysis
* Distribution of numerical variables
* Analysis of categorical variables
* Outlier identification
* Correlation analysis
* Visual exploration of important variables

---

### 3. Data Cleaning

The raw dataset was cleaned before further analysis.

Cleaning activities included:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Standardizing column names
* Handling inconsistent values
* Treating outliers where appropriate
* Formatting dates and numerical fields
* Preparing clean data for SQL and Power BI

---

### 4. SQL Analysis

The cleaned dataset was loaded into a relational database and analyzed using SQL.

**Database options used:**

* MySQL

SQL analysis included:

* Filtering and sorting data
* Aggregations
* `GROUP BY`
* `HAVING`
* `JOIN`
* Subqueries
* Common Table Expressions (CTEs)
* Window functions
* Date-based analysis
* Ranking
* Business KPI calculations

Example business questions:

```sql
-- Example: Total sales by category

SELECT
    category,
    SUM(sales) AS total_sales
FROM sales_data
GROUP BY category
ORDER BY total_sales DESC;

## How to Run

### Step 1: Clone the Repository

```bash
git clone https://github.com/NitishJasrotia/data-analytics-project.git
cd data-analytics-project
```

### Step 2: Install Python Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 3: Run the Python Analysis

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebook in:

```text
python/data_analysis.ipynb
```

### Step 4: Set Up the SQL Database

Create a database using **PostgreSQL, MySQL, or SQL Server** and import the cleaned dataset.

Then execute the queries available in:

```text
sql/analysis_queries.sql
```

### Step 5: Open the Power BI Dashboard

Open:

```text
powerbi/dashboard.pbix
```

in Power BI Desktop.

Update the data source/database connection if required.

---

## Skills Demonstrated

This project demonstrates practical experience in:

* **Python for Data Analysis**
* **Pandas & NumPy**
* **Exploratory Data Analysis**
* **Data Cleaning & Preprocessing**
* **SQL**
* **PostgreSQL / MySQL / SQL Server**
* **Data Visualization**
* **Power BI**
* **Business Intelligence**
* **KPI Analysis**
* **Business Insights & Recommendations**
---

## Project Goal

The goal of this project is to demonstrate how raw data can be transformed into **actionable business insights** using a complete data analytics pipeline from **Python and SQL analysis to Power BI visualization and business reporting**.
