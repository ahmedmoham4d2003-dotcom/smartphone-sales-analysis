# Phone-Research-Analysis
Data cleaning using Python and interactive dashboard creation using Power BI for sales analysis.
# 📱 Phone Market Analysis & Sales Dashboard

## 📌 Overview
This project analyzes mobile phone product data collected from an e-commerce platform (Amazon). The goal is to clean the raw dataset using Python, then build an interactive dashboard in Power BI to extract meaningful business insights and support decision-making.


## 📊 Dataset Description
The dataset contains over **315 phone products** with mixed data types (numerical, categorical, and text).

### Key Features:
- Product Title
- Price & Original Price
- Sales Volume
- Ratings
- Discount Status
- Best Seller / Amazon Choice
- Prime Availability
- Climate-Friendly Indicator


##  Data Cleaning (Python)
Data preprocessing was performed using Python (Pandas & NumPy):

### Main Steps:
- Removed columns with more than 75% missing values
- Cleaned price columns (removed symbols, converted to float)
- Handled missing values:
  - Median for price-related columns
  - Mean (4.08) for ratings
- Converted sales volume from text (e.g., 1.2K → 1200)
- Created new feature:
  - **Discount Value = Original Price - Price**


## 📈 Dashboard (Power BI)

### 🔹 Market Overview
- Total Products: 315
- Avg Price: $171
- Avg Rating: 4.08
- Discounted Products: 43%

### 🔹 Discount & Sustainability Analysis
- Discounted products achieve higher sales
- Climate-friendly products have competitive performance

### 🔹 Sales Performance
- Strong correlation between ratings and sales
- Best Seller & Amazon Choice significantly boost sales
- Top 10 products dominate total sales

---

## 🔍 Key Insights
- Discounts increase sales performance
- Higher-rated products sell more
- Best Seller and Amazon Choice labels improve visibility and sales
- Sales are concentrated in a small number of products
- Climate-friendly products perform similarly to others

---

## ✅ Recommendations
- Apply discounts strategically on high-performing products
- Improve product ratings through customer engagement
- Optimize listings to achieve Best Seller / Amazon Choice badges
- Promote sustainable products more effectively
- Analyze top-selling products to replicate success factors

---

## 🛠 Tools & Technologies
- Python (Pandas, NumPy)
- Power BI
- PowerPoint

---

## 📂 Project Files
-  Dataset (Raw & Cleaned)
- 🐍 Python Data Cleaning Script
- 📊 Power BI Dashboard (.pbix)
- 📽 Presentation (.pptx)

---

## 👤 Author
Ahmed Mohammad  
Data Analyst
