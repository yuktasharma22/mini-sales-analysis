# 🛍️ Sales Trends & Insights – Project Summary

**Dataset:** Mini Retail Sales Dataset (500 Transactions)  
**Period Covered:** January 2023 – May 2024  

---

## 📌 Overview

This project analyzes 500 retail transactions to uncover key patterns in revenue, product performance, regional sales, payment preferences, and profitability. Visualizations and metrics are used to generate actionable insights for business optimization.

---

## 🔍 Business Questions & Key Findings

### 1. Which Product Line Generates the Highest Revenue?

| S.No. | Product Line   | Total Revenue (₹) | Insight                                      |
|-------|----------------|-------------------|----------------------------------------------|
| 1     | Home Decor     | ₹310,205           | Highest earner – prioritize marketing        |
| 2     | Electronics    | ₹286,558           | Strong performance, steady demand            |
| 3     | Groceries      | ₹262,648           | High volume, daily necessity                 |
| 4     | Clothing       | ₹237,623           | Consistent sales, moderate profitability     |
| 5     | Stationery     | ₹217,166           | Lowest revenue – consider bundling/promos    |

### 2. Which City Has the Most Transactions?

| S.No. | City      | Transaction Count |
|-------|-----------|-------------------|
| 1     | Mumbai    | 168               |
| 2     | Delhi     | 167               |
| 3     | Bangalore | 165               |

- **Insight:** Mumbai has the most transactions — indicating a larger customer base or higher frequency.  
- **However**, Delhi has the **highest Average Order Value (₹)**, suggesting fewer but higher-value purchases.

### 3. What is the Busiest Day of the Week?

| S.No. | Weekday   | Sales Count |
|-------|-----------|-------------|
| 1     | Sunday    | 72          |
| 2     | Monday    | 72          |
| 3     | Tuesday   | 72          |

- **Insight:** Weekends and early weekdays are peak sales periods.  
  Promotions during these days can increase engagement and conversions.

### 4. What is the Average Profit Margin Across Cities?

| S.No. | City      | Avg. Profit Margin |
|-------|-----------|--------------------|
| 1     | Delhi     | 10.25%             |
| 2     | Bangalore | 10.10%             |
| 3     | Mumbai    | 9.75%              |

- **Insight:** Delhi yields the highest profit margin despite fewer transactions — likely due to better product mix or pricing.

---

## 📊 Additional Exploratory Insights

### ✅ Quantity Sold by Product Line

- **Objective:** Understand volume of sales regardless of price.
- **Insight:** Groceries lead in quantity sold — ideal for operational planning & inventory restocking.

### ✅ Average Order Value (AOV) by City

| City      | AOV (₹) |
|-----------|---------|
| Delhi     | Highest |
| Mumbai    | Medium  |
| Bangalore | Lowest  |

- **Recommendation:**  
  - Upsell in Mumbai to increase AOV  
  - Push premium products in Delhi where high-ticket orders already perform well

### ✅ Most Popular Payment Methods

| Payment Method | Transaction Count | Total Revenue (₹) |
|----------------|-------------------|--------------------|
| Credit Card    | 175                | ₹477,916           |
| Cash           | 170                | ₹466,160           |
| E-Wallet       | 155                | ₹370,123           |

- **Insight:** Credit Cards are the most used and generate the highest revenue — consider exclusive card offers or cashback incentives.
- **Cash** is still relevant with comparable usage — ensure smooth offline POS handling.
- **E-Wallets**, though third in usage, represent a significant digital share — optimize mobile UX and enable wallet-based offers.


### ✅ Monthly Revenue Trend

| Month       | Revenue (₹) |
|-------------|-------------|
| June 2023   | ₹105,408    |
| May 2024    | ₹48,253     |

- **Insight:** Revenue shows clear peaks and troughs — consider aligning campaigns with these patterns.
- **Visualization:** Trends plotted over 17 months to monitor seasonality and growth.

### ✅ Daily Revenue (with 7-Day Rolling Average)

| Date         | Revenue (₹) | Insight                                     |
|--------------|-------------|---------------------------------------------|
| Jun 09, 2023 | ₹8,900      | Highest revenue – possible sales event      |
| Apr 21, 2024 | ₹11         | Lowest revenue – low activity/engagement    |

- **Insight:** Peak days suggest campaign performance; dips may indicate inactivity or technical gaps.

---

## 📌 Executive Summary & Recommendations

### Key Takeaways:
- Home Decor is the highest revenue-generating product line.
- Mumbai leads in transaction count; Delhi leads in order value and profit margin.
- Sundays to Tuesdays are the busiest sales days.
- Credit Cards are the most preferred payment method.
- Seasonal peaks (June 2023) and dips (May 2024) exist in revenue flow.

### Actionable Insights:
- Double down on Home Decor and Groceries through tailored promotions.
- Apply upselling and loyalty programs in Mumbai to raise AOV.
- Expand Delhi’s pricing/product approach to other metros.
- Focus campaigns on weekends and early weekdays to match user behavior.
- Credit Cards generate the highest revenue — consider exclusive offers or loyalty points to drive continued usage.  
- Monitor inventory on fast-selling product lines such as Groceries.

### Suggested Improvement in Sales Strategy:
**Stationery underperforms** in both revenue and quantity — consider bundling, pricing changes, or promotional offers to boost engagement.

---

*This report was prepared in Jupyter Notebook using Python (Pandas, Seaborn, Matplotlib) and rendered through Visual Studio Code.*
