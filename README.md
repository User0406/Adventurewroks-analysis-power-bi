# 🏷️ AdventureWorks Sales Analysis

## 📊 Project Overview
The **AdventureWorks Sales Analysis** Power BI project provides a detailed exploration of sales performance, product profitability, and customer order behavior using data sourced from the AdventureWorks dataset.  
This end-to-end BI solution demonstrates the complete analytics workflow — from data cleaning and modeling to DAX-based measure creation and interactive dashboard development.

---

## 🎯 Business Objective
The primary goal of this project is to:
- Identify top-performing products and categories.
- Understand sales trends across regions and time periods.
- Analyze customer behavior and order distribution.
- Provide actionable insights for management to optimize pricing, inventory, and marketing decisions.

---

## 🧾 Dataset
**Source:** [Kaggle – AdventureWorks Dataset](https://www.kaggle.com/datasets)  
The dataset contains multiple CSV files related to:
- **Sales**: Transactional sales data  
- **Products**: Product categories, subcategories, and pricing  
- **Customers**: Customer demographics and territories  
- **Orders**: Quantity, order date, and order amount  

Each file was imported into Power BI and modeled into a star schema for efficient analysis.

---

## 🧰 Tools & Technologies
- **Power BI** – Data cleaning, modeling, DAX calculations, and visualization  
- **Power Query Editor** – Data transformation and preparation  
- **DAX (Data Analysis Expressions)** – Creation of KPIs and calculated metrics  
- **Microsoft Excel / CSV** – Data source format  
- **Kaggle** – Dataset sourcing  

---

## 🗂️ Project Structure
```
AdventureWorks-Sales-Analysis/
│
├── AdventureWorks_Sales_Analysis_Report_Detailed.pdf
├── AW_project.pbix
├── images/
│   ├── dashboard_summary.png
│   ├── dashboard_product_details.png
│   └── dashboard_order_details.png
├── README.md
└── dataset/
```

---

## 🧹 Data Cleaning & Preparation
Performed in **Power Query Editor**, the following transformations were applied:
- Removed duplicates and null records  
- Standardized column names  
- Converted data types (numeric, date, text)  
- Created calculated columns such as `Total Sales = Quantity × Unit Price`  
- Merged lookup tables to form a complete sales model  
- Extracted year, month, and quarter fields for time-based analysis  

---

## 🔍 Exploratory Data Analysis (EDA)
The data was explored using Power BI visualizations to identify:
- Sales distribution by product category  
- Monthly and quarterly sales trends  
- Regional revenue performance  
- Profit margin fluctuations  
- Customer order behavior and average purchase size  

---

## ❓ Research Questions & Key Findings
1. **Which product categories drive the highest revenue?**  
   → Electronics and Bikes dominate total sales contribution.  
2. **Which regions perform best in terms of revenue and profit?**  
   → North America shows the strongest performance followed by Europe.  
3. **Are there seasonal trends in sales?**  
   → Sales peak during Q3 and Q4, indicating seasonal buying behavior.  
4. **Who are the top customers contributing to total revenue?**  
   → A small percentage of repeat customers drive a large portion of sales.  
5. **What are the key profitability insights?**  
   → Some high-selling products show low profit margins, suggesting opportunities for pricing adjustments.

---

## 📈 Dashboard
The project includes **three interactive dashboards**:

### 1️⃣ Summary Dashboard
- Displays overall KPIs: Total Sales, Total Orders, Profit Margin, Average Sales per Customer  
- Monthly sales trend visual  
- Category-wise performance bar chart  
- Revenue distribution via pie/donut chart  
- Filters for year, region, and category  

![Summary Dashboard](images/dashboard_summary.png)

---

### 2️⃣ Product Detail Dashboard
- Product-level KPIs: Quantity Sold, Revenue, Profit Margin  
- Top & Bottom 5 Products using DAX ranking  
- Stacked column chart for product subcategory performance  
- Scatter plot comparing sales vs profit  
- Interactive slicers for category and brand  

![Product Detail Dashboard](images/dashboard_product_details.png)

---

### 3️⃣ Order Detail Dashboard
- Order Quantity by Territory and Customer Segment  
- Regional performance visualized via map chart  
- Trend line for daily/weekly orders  
- Detailed order table with customer drill-down  
- KPIs: Total Orders, Average Order Value  

![Order Detail Dashboard](images/dashboard_order_details.png)

---

## ⚙️ How to Run This Project
1. Download the repository or clone it:
   ```bash
   git clone https://github.com/<your-username>/AdventureWorks-Sales-Analysis.git
   ```
2. Open the file `AW_project.pbix` in **Microsoft Power BI Desktop**.
3. If necessary, update dataset paths in **Power Query**.
4. Explore the dashboards interactively and filter insights as needed.

---

## 💡 Final Recommendations
- Focus on high-margin products to maximize profitability.  
- Strengthen marketing in underperforming regions.  
- Develop targeted loyalty programs for repeat customers.  
- Optimize pricing strategy for low-margin, high-sales items.  
- Maintain inventory planning around seasonal sales trends.  

---

## 👤 Author & Contact
**Author:** Lakshay Sharma  
📧 **Email:** [lakshaysharma406@gmail.com]  
💼 **LinkedIn:** [https://www.linkedin.com/in/lakshay-sharma-6a5365299/]
📂 **GitHub:** [https://github.com/User0406]

---

✨ *This project demonstrates data modeling, DAX implementation, and visualization skills using Power BI for real-world business intelligence scenarios.*
