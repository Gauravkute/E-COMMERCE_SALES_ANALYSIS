# E-COMMERCE_SALES_ANALYSIS-SQL-POWER_BI
End-to-End E-Commerce Sales Analytics project using PostgreSQL and Power BI. This project analyses sales performance, customer behaviour, product categories, marketing channels, customer satisfaction, and revenue trends using advanced SQL queries and interactive dashboards.

# 🛒 End-to-End E-Commerce Sales Analytics using PostgreSQL  & Power BI

This project analyzes 10,000 e-commerce transactions across 38 fields to uncover sales, customer, marketing, and operational insights. Using PostgreSQL for data analysis and Power BI for visualization, the project identifies Electronics as the top-performing product category by revenue and India as the highest-revenue country, while evaluating customer purchasing behaviour across different customer segments. The analysis also identifies key patterns in product returns, delivery performance, customer satisfaction, and marketing channel performance.

The resulting 3-page dashboard is designed to support business decisions around marketing performance, customer retention, product strategy, and operational efficiency.


## 📌 Project Overview

This project focuses on analyzing an E-Commerce sales dataset using PostgreSQL and Power BI to uncover meaningful business insights. The analysis covers sales performance, customer behaviour, marketing effectiveness, product performance, shipping efficiency, and customer satisfaction.

The project demonstrates advanced SQL concepts such as Window Functions, CTEs, Views, Aggregate Functions, Ranking Functions, and analytical queries while creating an interactive Power BI dashboard for business reporting.

---

## 🎯 Project Objectives

- - Analyze revenue and order trends
- Identify top-performing products and categories
- Analyze customer purchasing behavior
- Identify repeat and high-value customers
- Evaluate marketing channel performance
- Analyze return patterns
- Evaluate shipping and delivery performance
- Build an interactive Power BI dashboard
- Generate actionable business recommendations
---

## 🗂 Dataset Information

| Feature | Details |
|----------|---------|
| Dataset | E-Commerce Sales |
| Records | 10,000 |
| Columns | 38 |
| Database | PostgreSQL |
| Visualization | Power BI |
| Language | SQL |

---

## 🛠 Tools & Technologies

- PostgreSQL
- SQL
- Power BI
- DAX
- GitHub

---

## 📊 SQL Concepts Used

- Data Definition Language (DDL)
- Aggregate Functions
- GROUP BY & HAVING
- CASE Statements
- Window Functions
- ROW_NUMBER()
- RANK()
- DENSE_RANK()
- LAG()
- NTILE()
- CTE (Common Table Expressions)
- Views
- Subqueries

---

## 📈 Business Analysis Performed

### Basic Analysis
- Total Orders
- Total Revenue
- Average Order Value
- Average Discount
- Average Delivery Time
- Total Tax Collected

### Sales Analysis
- Revenue by Year
- Revenue by Month
- Revenue by Quarter
- Revenue by Country
- Revenue by Product Category
- Revenue by Platform

### Customer Analysis
- Customer Segments
- Repeat Purchases
- Loyalty Analysis
- Customer Satisfaction
- Highest Spending Customers

### Marketing Analysis
- Acquisition Channel Performance
- Coupon Usage
- Wishlist Usage
- Platform Performance

### Shipping Analysis
- Delivery Performance
- Shipping Method Analysis

### Advanced SQL Analysis
- Running Revenue
- Monthly Growth
- Revenue Contribution
- Ranking Analysis
- Window Functions
- Sales View Creation

---

## 📊 Power BI Dashboard

### Dashboard 1 – Executive Overview
- Total Revenue
- Total Orders
- Average Shipping Days
- Average Discount
- Revenue Trend
- Revenue by Country
- Revenue by Product Category
  
<img width="1217" height="850" alt="Screenshot 2026-08-26 164351" src="https://github.com/user-attachments/assets/7bdbde39-818d-404f-bc4e-d9ce2e32c9ee" />

### Dashboard 2 – Customer Analytics
- Customer Segments
- Gender Distribution
- Age Group Distribution
- Subscription Members
- Payment method
- Repeat Purchases

- <img width="1571" height="747" alt="Screenshot 2026-08-26 164406" src="https://github.com/user-attachments/assets/dbd2e24e-353f-44cc-8455-65f026e1600c" />

### Dashboard 3 – Customer Experience
- Product Ratings
- Customer Satisfaction
- Return Reasons
- Delivery Days
- Coupon Usage
- Wishlist Usage

<img width="1150" height="642" alt="Screenshot 2026-08-26 164417" src="https://github.com/user-attachments/assets/9f983ec4-5885-423f-a212-05781b601c65" />

---

## 📌 Key Findings

- Electronics was the top-performing category by revenue (~$2.98M), 
  nearly 3x the next-highest category (Mobile & Tablets, ~$1.02M)
- India was the highest-revenue country (~$886K), narrowly ahead of 
  USA ($860K) and Pakistan ($760K)
- Amazon led all platforms in revenue (~$1.47M) — roughly double the 
  next-best platform, Shopify Store (~$755K)
- Only 6.4% of orders were returned; top return reasons were 
  "Wrong Item" and "Changed Mind"
- 71% of customers were repeat purchasers, indicating strong retention
- Organic Search was the top-performing acquisition channel by 
  revenue (~$1.42M), ahead of Social Media and Paid Ads


---

## 📁 Project Structure

```
E-Commerce-Sales-Analytics
│
├── Dataset
├── SQL Scripts
├── Power BI Dashboard
├── Dashboard Screenshots
├── Report
└── README.md
```

---

## 🚀 Skills Demonstrated

- SQL Query Writing
- PostgreSQL
- Data Cleaning
- Data Analysis
- Business Intelligence
- Window Functions
- CTE
- Views
- Dashboard Design
- Data Storytelling

  ## 💡 Business Recommendations

### 1. Strengthen the Electronics Category

Electronics generated approximately $2.98M in revenue, making it the strongest-performing product category.

**Recommendation:**
Prioritize high-performing electronics products through inventory planning, targeted promotions, and cross-selling opportunities. The business should also monitor product-level return rates to ensure that high sales volume is not accompanied by excessive returns.

---

### 2. Focus on High-Revenue Markets

India generated approximately $886K in revenue, making it the highest-revenue country in the analysis.

**Recommendation:**
Increase marketing and customer-retention efforts in high-performing markets such as India. Analyze customer preferences and purchasing patterns in these markets to identify opportunities for localized promotions and product offerings.

---

### 3. Optimize the Amazon Sales Channel

Amazon generated approximately $1.47M in revenue, significantly outperforming the next-highest platform.

**Recommendation:**
Investigate the factors driving Amazon's stronger performance, including product visibility, customer reach, pricing, promotions, and conversion rates. Successful strategies from this channel could potentially be applied to lower-performing platforms.

---

### 4. Improve Customer Retention

Approximately 71% of customers were repeat purchasers, indicating strong customer retention.

**Recommendation:**
Develop loyalty-focused strategies such as personalized offers, targeted recommendations, repeat-purchase incentives, and membership benefits to encourage existing customers to purchase more frequently.

---

### 5. Reduce Product Returns

Approximately 6.4% of orders were returned, with "Wrong Item" and "Changed Mind" identified as major return reasons.

**Recommendation:**
Improve product descriptions, images, specifications, and order-fulfillment checks to reduce incorrect-item returns. For "Changed Mind" returns, clearer product information and better expectation-setting may help reduce avoidable returns.

---

### 6. Invest in Organic Search

Organic Search generated approximately $1.42M in revenue, making it the strongest acquisition channel in the analysis.

**Recommendation:**
Continue investing in SEO and identify the products, categories, and customer segments contributing most to organic-search revenue. High-performing organic-search strategies can be expanded to increase customer acquisition efficiently.

---

### 7. Monitor Delivery Performance

The analysis includes delivery time and shipping-method performance.

**Recommendation:**
Monitor average delivery time by country, shipping method, and platform to identify operational bottlenecks. Improving delivery reliability could contribute to higher customer satisfaction and potentially reduce delivery-related complaints and returns.


## 📌 Conclusion

This project demonstrates how SQL and Power BI can be used together to transform raw transactional data into insights that support pricing, marketing, and operational decisions — including identifying top revenue by product category as well as low performing category , number of members as well as the reason of return  as the actionable findings for the business.
