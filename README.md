# Retail-Sales-ETL-PySpark
# 🛒 Retail Sales ETL Pipeline using PySpark & Power BI

## 📌 Project Overview
This project focuses on building an end-to-end Retail Sales ETL Pipeline using PySpark in Databricks and creating an interactive Power BI dashboard for business insights.

The project demonstrates:
- Data Extraction
- Data Cleaning
- Data Transformation
- Data Quality Validation
- Business Intelligence Reporting

The cleaned dataset was processed using PySpark and visualized using Power BI dashboards.

---

# 🚀 Tech Stack

- Python
- PySpark
- Databricks
- Power BI
- DAX
- Power Query
- Pandas

---

# 📂 Project Structure

```bash
Retail-Sales-ETL-PySpark/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
    ├── images/
    └──pyspark_etl.ipynb
│
├── powerbi/
│   └── Retail_Sales_Dashboard.pbix
│
├── screenshots/
│
├── README.md
└── requirements.txt
```

---

# 🔄 ETL Workflow

## 1️⃣ Extract
- Loaded retail sales dataset into PySpark DataFrame
- Imported dataset into Databricks environment

## 2️⃣ Transform
Performed multiple transformation steps:
- Removed null values
- Standardized column formats
- Extracted Year from Date column
- Created calculated fields
- Added data quality validation columns

## 3️⃣ Load
- Exported cleaned dataset as CSV
- Connected processed dataset to Power BI
- Built interactive dashboards

---

# 🧹 Data Cleaning & Transformation

The following transformations were applied:

- Null value handling
- Duplicate removal
- Date formatting
- Revenue calculations
- Category standardization
- Payment method validation
- Mismatch detection using `Mismatch_Flag`

---

# 📊 Power BI Dashboard Pages

## 📌 Page 1: Executive Overview
- Total Revenue
- Total Orders
- Profit Analysis
- Sales Trends

## 📌 Page 2: Product Performance
- Top Selling Categories
- Product Revenue Analysis
- Quantity Sold Metrics

## 📌 Page 3: Customer Analysis
- Customer Segmentation
- Revenue by Customer Type
- Regional Analysis

## 📌 Page 4: Payment & Channel Analysis
- Payment Method Distribution
- Online vs Offline Sales
- Digital Payment %

## 📌 Page 5: Time Analysis
- Monthly Sales Trends
- Year-wise Analysis
- Seasonal Insights


---

# 📈 Key Insights

- Identified the highest revenue-generating product categories and products
- Analyzed customer purchasing behavior across different locations
- Compared online and offline sales performance
- Observed cash payments as the dominant payment method in the dataset
- Tracked monthly and yearly sales trends for business growth analysis
- Evaluated category-wise sales contribution and order volume
- Built KPI-driven dashboards for executive-level business monitoring
- Improved reporting efficiency through interactive Power BI visualizations

---

# ⚙️ How to Run the Project

## Clone Repository

https://github.com/Rithika-1408/Retail-Sales-ETL-PySpark.git


## Install Dependencies

pip install -r requirements.txt

## Run PySpark Notebooks
Open notebooks in:
- Databricks
You can also use:
- Jupyter Notebook
- Google Colab

---

# 📌 Future Improvements

- Real-time data pipeline integration
- Advanced anomaly detection
- Cloud deployment
- Machine learning sales forecasting

---

# 👩‍💻 Author

Rithika N

- Email: rithirenu14@gmail.com
- LinkedIn: https://www.linkedin.com/in/rithika-n-a70753233/
- Role: Data Analyst | AI Data Analyst | Chennai

---
