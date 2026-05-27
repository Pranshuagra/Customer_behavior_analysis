# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview
This project focuses on analyzing customer shopping behavior using transactional purchase data to uncover business insights and support data-driven decision making.

The analysis covers customer demographics, purchase patterns, subscription behavior, product performance, and revenue trends using Python, PostgreSQL, and Power BI.

The complete workflow includes:
- Data Cleaning & Preprocessing (Python)
- Exploratory Data Analysis (EDA)
- SQL-Based Business Analysis
- Interactive Dashboard Development (Power BI)
- Business Recommendations

---

## 🚀 Objective
The goal of this project is to:

- Understand customer purchasing patterns
- Identify high-value customer segments
- Analyze product performance
- Evaluate subscription behavior
- Generate actionable business recommendations

---

## 📂 Dataset Information

| Feature | Details |
|----------|---------|
| Total Records | 3,900 |
| Total Columns | 18 |
| Missing Values | 37 (Review Rating) |

### Dataset Includes:
- Customer Demographics
  - Age
  - Gender
  - Location
  - Subscription Status

- Purchase Details
  - Item Purchased
  - Category
  - Purchase Amount
  - Season
  - Size
  - Color

- Shopping Behavior
  - Discount Applied
  - Previous Purchases
  - Review Rating
  - Shipping Type
  - Frequency of Purchases

---

# 🧹 Data Cleaning & Preprocessing

### Performed in Python

✔ Data Loading using Pandas  
✔ Exploratory Data Analysis  
✔ Missing Value Treatment  
✔ Column Standardization  
✔ Feature Engineering  
✔ Database Integration with PostgreSQL  

### Key Transformations:
- Missing Review Ratings filled using category median
- Converted columns into snake_case
- Created:
  - `age_group`
  - `purchase_frequency_days`
- Removed redundant feature:
  - `promo_code_used`

---

# 📊 Business Analysis (SQL)

Several business questions were answered using PostgreSQL.

### Key Insights:

### 1. Revenue Analysis by Gender
Compared total revenue contribution between customer groups.

### 2. High-Spending Discount Users
Identified customers who used discounts but still generated higher purchase values.

### 3. Top Rated Products
Extracted products with highest customer satisfaction.

### 4. Shipping Behavior Analysis
Compared spending across shipping types.

### 5. Subscription Insights
Evaluated subscriber vs non-subscriber purchasing behavior.

### 6. Discount Dependency Analysis
Identified products highly dependent on discounts.

### 7. Customer Segmentation
Grouped customers into:
- New
- Returning
- Loyal

### 8. Category-wise Product Ranking
Top products identified across categories.

### 9. Repeat Buyer Analysis
Measured subscription tendency among frequent buyers.

### 10. Revenue Contribution by Age Group
Determined most valuable customer segments.

---

# 📈 Dashboard (Power BI)

Interactive dashboard created to visualize:

- Revenue Metrics
- Customer Distribution
- Sales Performance
- Subscription Analysis
- Revenue by Category
- Revenue by Age Group
- Customer Behavior Trends

### Dashboard KPIs
- Total Customers
- Average Purchase Amount
- Average Review Rating
- Revenue Distribution

---

# 🛠 Tech Stack

| Category | Tools |
|----------|-------|
| Programming | Python |
| Analysis | Pandas, NumPy |
| Database | PostgreSQL |
| Visualization | Power BI |
| IDE | Jupyter Notebook |

---

# 📌 Business Recommendations

✅ Increase subscriber conversion through exclusive offers  

✅ Introduce customer loyalty rewards  

✅ Optimize discount strategy  

✅ Promote top-rated products  

✅ Run targeted marketing campaigns for high-value segments  

---

# 📷 Project Screenshots

Add screenshots here:

```
images/
│
├── dashboard.png
├── sql_analysis.png
├── python_eda.png
```

---

# 📁 Project Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── dataset/
├── notebooks/
├── sql_queries/
├── powerbi_dashboard/
├── images/
├── README.md
└── requirements.txt
```

---

# ⭐ Results

This project demonstrates an end-to-end data analytics workflow combining:

✔ Data Cleaning  
✔ SQL Analytics  
✔ Dashboarding  
✔ Business Decision Support  

---

## 👨‍💻 Author

**Pranshu Agrahari**

Data Analytics | Machine Learning | Power BI | SQL

LinkedIn: Add Your Profile  
GitHub: Add Your Profile
