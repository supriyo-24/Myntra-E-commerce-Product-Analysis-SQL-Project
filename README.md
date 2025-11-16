## 🛍️ Myntra E-commerce Product Analysis — Comprehensive SQL Project Overview

This project provides a detailed SQL-based analysis of product data from **Myntra**, one of India’s most popular online fashion marketplaces. Using **MySQL Workbench**, the project explores how brands perform across key business metrics such as **ratings, pricing strategies, discounts, customer engagement, and product popularity**.

The goal is to transform raw e-commerce product listings into meaningful business insights that highlight trends in customer behavior, brand quality, and pricing efficiency.

---

## 🔍 Project Focus

The analysis centers around understanding:

- **Brand performance** through customer ratings  
- **Patterns in discounting and pricing**  
- **Customer engagement** using number of ratings  
- **Revenue estimation by brand**  
- **Premium vs budget product positioning**  
- **Brand consistency** (both high-rated and poorly-rated products)  
- **Correlation between discounts and quality perception**  

By using SQL queries and analytical logic, the project uncovers insights essential for e-commerce decision-making.

---

## 📂 Dataset Summary

The dataset contains rich product information across multiple attributes:

- Brand Name  
- Product Description  
- Selling Price  
- MRP (Original Price)  
- Discount Percentage  
- Average Customer Rating  
- Number of Ratings  

These attributes provide a strong foundation for evaluating brand trust, pricing behavior, value perception, and product quality.

---

## 🧱 SQL Database Schema

The project uses a structured MySQL table `project_myntra` containing all product attributes.  
This schema supports advanced SQL operations such as window functions, ranking, aggregation, and correlation analysis.

---

## 📊 Key Business Questions & Insights

The project answers **10 essential business questions**, each supported by SQL queries:

### ⭐ 1. Highest Rated Brands  
Identifies brands with consistently strong customer satisfaction based on average ratings and sufficient product volume.

### 💸 2. High Discount but Low Rating Products  
Finds items with deep discounts but poor ratings — often linked to overstock or low product quality.

### 💰 3. Top Revenue-Generating Brands  
Uses `price × number_of_ratings` as a proxy for revenue to determine financially successful brands.

### 🎯 4. Premium Pricing with Poor Ratings  
Highlights brands that price above the market average but perform below the rating average — indicating overpricing issues.

### 🏷️ 5. Product Price vs Brand Average  
Shows whether individual products are priced higher or lower compared to their brand’s average price, identifying premium or budget product lines.

### 🔥 6. Most Rated Product per Brand  
Finds each brand’s most popular product based on customer engagement.

### 📉 7. Discount–Rating Correlation  
Calculates whether higher discounts correlate with better or worse ratings.  
This helps determine whether customers value discounts or product quality more.

### 🟡 8. Mixed-Quality Brands  
Shows brands that have both highly-rated and poorly-rated products — indicating inconsistency in product quality.

### 🏷️ 9. Value-for-Money Products  
Identifies products priced below **50% of MRP** yet rated above **4.0**, highlighting strong deals.

### 🏆 10. Highest Discount Brands  
Ranks brands by their average discount, considering product count and engagement thresholds.

---

## 📈 Insights Summary

| Category | Finding | Insight |
|----------|---------|---------|
| **Brand Performance** | Some brands consistently enjoy high ratings | Strong customer trust |
| **Discount Behavior** | High discounts don’t always improve ratings | Quality matters more than discount |
| **Pricing** | Some brands charge premium rates despite low ratings | Possible price–value mismatch |
| **Revenue** | Brands with high engagement dominate revenue | Customer popularity drives financial success |
| **Customer Trends** | Highly rated products show strong consistency | Good quality aligns with strong ratings |
| **Value Products** | Several items priced below 50% of MRP score high | Attractive deals exist across brands |

---

## 🔧 SQL Techniques Used

This project demonstrates advanced SQL skills, including:

- Aggregate functions (AVG, COUNT, SUM)  
- Window functions (`ROW_NUMBER`, `DENSE_RANK`)  
- CTEs (`WITH` clauses) for structured queries  
- Correlation calculation  
- Ranking and sorting for business intelligence  
- Data-driven revenue estimation  
- Brand-level and product-level comparative analysis  

These techniques combine to produce actionable insights useful in real-world e-commerce analytics.

---

## 📘 Learnings & Applications

This SQL project demonstrates how raw marketplace data can be transformed into powerful business insights.  
The findings support decision-making in:

- **Pricing optimization**  
- **Discount strategy improvements**  
- **Product quality evaluation**  
- **Brand performance tracking**  
- **Customer engagement analysis**  

By applying SQL to solve business problems, the project showcases practical data analytics ability and strong problem-solving skills with relational data.

---

## 🏁 Conclusion

The Myntra SQL analysis highlights how structured queries can reveal patterns in customer behavior, product quality, and pricing effectiveness.  
From identifying top brands to analyzing value-for-money deals, the project provides clear, data-backed insights.

This project demonstrates the power of SQL for **real-world business intelligence**, especially in e-commerce environments where data drives strategy and growth.

