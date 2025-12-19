# Customer Churn Analysis

## 📌 Project Description
This project focuses on analyzing customer churn behavior using order, delivery, and product-level data from an e-commerce platform. The goal is to identify the key factors driving customer churn and provide data-driven recommendations to improve customer retention and overall business performance.

The analysis emphasizes delivery delays, freight costs, regional logistics performance, and product-level revenue patterns to understand why customers leave the platform.

---

## 🎯 Business Objective
- Identify major drivers of customer churn
- Understand the impact of delivery delays on retention
- Analyze freight cost sensitivity
- Improve customer experience and loyalty
- Support strategic decisions in logistics and marketing

---

## 📊 Dataset Overview
- Dataset size (after cleaning): **96,096 records × 13 features**
- Domain: E-commerce / Customer Analytics
- Target variable: Customer churn status (Churned vs Retained)

### Key Features Used
- Delivery delay (in days)
- Freight value
- Product price
- Product category
- Order purchase date
- Customer location (state)
- Revenue
- Churn status

---

## 🛠 Tools & Technologies Used
- SQL
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 🔍 Exploratory Data Analysis (EDA)
The following analyses were performed:
- Monthly sales (revenue) trend analysis
- On-time vs late delivery comparison
- Top product categories by revenue
- Impact of delivery delay on customer churn
- Freight cost comparison between churned and retained customers
- Churn rate vs delivery delay by state
- Distribution of churned vs retained customers

---

## 📈 Key Insights
- Seasonal events (such as holidays and sales campaigns) show a strong spike in revenue
- Around **8% of orders are delivered late**, impacting nearly 8,000 customers per 100k orders
- Delivery delays greater than **5 days** significantly increase customer churn
- Customers paying **high freight for low-priced products** are more likely to churn
- Northern and Northeastern regions show higher churn due to poor delivery performance
- Only **29% of customers are retained**, while **71% churn**, indicating a serious retention issue

---

## ✅ Business Recommendations
- Improve delivery speed by partnering with reliable logistics providers
- Provide realistic delivery timelines and proactive communication for delays
- Reduce freight charges or offer free shipping above a minimum order value
- Pause marketing in regions with extreme delivery delays until logistics improve
- Run retention campaigns such as discounts, free shipping, cashback, and “welcome back” offers
- Focus on improving customer experience before acquiring new customers

---

## 📌 Conclusion
This analysis shows that customer churn is mainly driven by delivery-related issues and high freight costs. Improving logistics performance and shipping fairness can significantly increase customer retention, reduce churn, and strengthen long-term business sustainability.
