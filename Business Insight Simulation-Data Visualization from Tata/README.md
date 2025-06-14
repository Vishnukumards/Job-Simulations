# 🛍️ Online Retail Store Business Analysis – 2011

This project focuses on analyzing business performance data of an online retail store in the year 2011. The goal is to deliver actionable insights through data cleaning, visualization, and storytelling for a strategic meeting with the CEO and CMO.

---

## 🎯 Project Goals

- Evaluate current business performance using retail data
- Identify top contributing factors to business growth
- Assist CEO in planning for business expansion
- Help CMO understand product, region, and customer-level behaviors
- Combine qualitative and quantitative insights for strategic decision-making

---

## 🧠 Business Questions Addressed

### CEO-Oriented Analysis
- 📈 **Monthly revenue trends** to understand seasonality and growth
- 👥 **Customer lifetime value** by repeat purchases (`CustomerID`)
- 📦 **Top product categories** driving profitability
- 🌍 **Country-level revenue** insights for future expansion (excluding UK)

### CMO-Oriented Analysis
- 🥇 **Top-performing products** by revenue and quantity
- 🧠 **Customer segmentation** based on purchasing behavior
- 🕒 **Time and seasonal trends** for optimized campaign timing
- 🌐 **Regional preferences** to guide localized marketing

---

## 🧹 Data Cleaning & Preparation

- Removed records with missing `CustomerID`, `Quantity`, or `UnitPrice`
- Created a `Revenue` column (`Revenue = Quantity × UnitPrice`)
- Filtered data to include only **year 2011**
- Standardized date fields for monthly grouping
- Excluded the **United Kingdom** where appropriate

---

## 📊 Visualizations & Insights

### 📌 Question 1: Monthly Revenue Trend (2011)
- **Chart Type**: Line Chart
- **X-Axis**: Month (`InvoiceDate`)
- **Y-Axis**: Revenue
- **Insight**: Revealed seasonal spikes and consistent monthly growth

### 📌 Question 2: Revenue & Quantity by Country (Excl. UK)
- **Chart Type**: Side-by-Side Bar Chart
- **Insight**: Identified top 10 countries contributing most to sales volume and revenue, ideal for expansion targeting

### 📌 Question 3: Top 10 Customers by Revenue
- **Chart Type**: Vertical Bar Chart
- **Insight**: Showcased high-value repeat customers, useful for loyalty campaigns

### 📌 Question 4: Global Sales Distribution (Excl. UK)
- **Chart Type**: Map Chart
- **Insight**: Highlighted international sales spread, supporting geographic marketing strategy

---

## 🧭 Storytelling Summary

> “Analysis of 2011 retail data shows strong monthly revenue growth, with seasonal peaks during Q4. Our top 10 customers contribute over 25% of total revenue, indicating the importance of loyalty-driven retention strategies. Excluding the UK, countries like Germany, Netherlands, and France show high sales volume—prime candidates for international expansion. The CMO can leverage insights from product-level and seasonal trends to refine marketing campaigns by region and time. These visual insights will guide leadership in both operational and marketing strategies moving forward.”

---

## 📚 What I Learned

- ✅ How to define and track **business success metrics**
- 📈 The importance of **KPIs** in strategic decision-making
- 🛠 Cleaned, prepared, and analyzed large datasets
- 📊 Matched **data visualization types** to business problems
- 🎤 Practiced **storytelling with data** for executive communication

---

## 🗂️ Project Structure

