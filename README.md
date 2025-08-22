# InsightX-E-Commerce-Sales-Analytics-Dashboard

This repository hosts a comprehensive end-to-end project that analyzes customer purchase behavior and sentiment using SQL, Python, and Power BI. The project combines structured data on customer transactions and reviews to deliver actionable insights for businesses.

## Project Overview

### Objective
The primary objective of this project is to identify patterns in customer purchase behavior and analyze customer sentiment based on product reviews. These insights will empower businesses to make informed decisions about marketing, product development, and customer engagement strategies.

###

<div align="center">
  <img src="https://github.com/RafiQamar/Customer-Purchase-Behavior-and-Sentiment-Analysis/blob/main/Ecommerce%20Dashboard.gif?raw=true" height="300" alt="IMDB Dashboard gif" />
</div>

###

### Datasets

1. **Customer Purchase Data:**
   - Fields:
     - `Transaction ID`
     - `Customer ID`
     - `Customer Name`
     - `Product ID`
     - `Product Name`
     - `Product Category`
     - `Purchase Quantity`
     - `Purchase Price`
     - `Purchase Date`
     - `Country`

2. **Customer Reviews Data:**
   - Fields:
     - `Review ID`
     - `Customer ID`
     - `Product ID`
     - `Review Text`
     - `Review Date`

## Key Features

This project involves three core components:

### 1. Data Extraction and Transformation (SQL)
- **Database Setup:**
  - Created a MySQL database schema to store and manage the datasets.
  - Established relationships between tables to maintain referential integrity.

- **Data Ingestion:**
  - Imported purchase and review datasets into the database using SQL scripts.

- **Data Cleaning and Normalization:**
  - Addressed missing or inconsistent data.
  - Normalized the database to eliminate redundancy and ensure scalability.

- **Aggregation and Insights:**
  - Designed advanced SQL queries to generate metrics, including:
    - Total purchases and revenue by customer.
    - Total sales and quantities by product.
    - Purchase trends over time.

### 2. Data Analysis (Python)
- **Data Extraction:**
  - Connected to the SQL database using Python’s `pymysql` library to fetch normalized and cleaned data.

- **Sentiment Analysis:**
  - Performed sentiment classification on review text using the `TextBlob` library.
  - Categorized reviews into Positive, Neutral, and Negative sentiments.

- **Advanced Analysis:**
  - Metrics and visualizations generated include:
    - Total purchases, revenue, and average purchase value.
    - Top customers and their purchasing patterns.
    - Purchase trends over time (monthly, quarterly, yearly).
    - Top-performing product categories based on revenue and volume.
    - Sentiment distribution across products and categories.

- **Visualization:**
  - Utilized `matplotlib` and `seaborn` to create detailed plots.
  - Generated insights such as purchase trends and sentiment breakdowns.

### 3. Data Visualization and Reporting (Power BI)
- **Interactive Dashboard:**
  - Built an intuitive and interactive Power BI dashboard showcasing:
    - Purchase trends over different timeframes.
    - Top-performing products and categories.
    - Customer segmentation based on purchasing behavior.
    - Sentiment analysis insights with breakdowns by product and category.

- **Dynamic Reports:**
  - Enabled users to filter the data dynamically by date, product category, or customer segment.

## Project Deliverables

### 1. SQL Scripts
- **File:** `cust_pur_details.sql`
- Contains SQL commands for database creation, data ingestion, and transformations.

### 2. Python Notebook
- **File:** `Customer Purchase Behavior and Sentiment Analysis.ipynb`
- Includes data extraction, cleaning, sentiment analysis, and visualization.

### 3. Power BI Dashboard
- **File:** `Ecommerce Analytics Dashboard.pbix`
- Provides an interactive interface for exploring insights derived from the datasets.

## Tools and Technologies

- **Database:** MySQL
- **Programming Language:** Python
  - Libraries: `pandas`, `numpy`, `TextBlob`, `matplotlib`, `seaborn`, `pymysql`
- **Visualization Tool:** Power BI

## 🚀 How to Run the Dashboard

### 🔹 Option A: Run Locally with Power BI Desktop
1. **Download Power BI Desktop** (free) from the [official site](https://powerbi.microsoft.com/desktop/).  
2. **Download the file**: `Ecommerce Analytics Dashboard.pbix`.  
3. **Open the file** by:
   - Double-clicking it, or  
   - Opening Power BI Desktop → `File → Open → Browse` → select the `.pbix` file.  
4. Wait a few seconds for the visuals and data model to load.  
5. Start exploring the dashboard (filters, slicers, drill-downs, etc.).  

### 🔹 Option B: View Online (Demo Link)
If you don’t want to run it locally, view the **live dashboard** online here:  

👉 [View Online Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZmVlNTUwMzItYjYzOC00ZjQ5LTkwZDYtMmZjOTBkZDU0NmY0IiwidCI6IjZjZTcwOTA0LTUwOWMtNGI0Zi1iNjc2LTJiMGRlZjA3M2U2YyJ9)
ps:keep clicking next to see all dashboards

---

## 🛠️ Tech Used
- **Power BI Desktop**  
- **Power BI Service (Online)**  

---

## 📌 Note
- Use the `.pbix` file if you want to customize/edit the dashboard.  
- Use the **online demo link** if you just want to interact with it.  










