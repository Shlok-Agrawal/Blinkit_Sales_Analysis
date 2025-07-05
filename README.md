# 🛒 Blinkit Sales Analysis – Pandas & Matplotlib Project

This project dives into order-level sales data from Blinkit to extract actionable business insights using Python’s pandas and matplotlib libraries.
---

## 🧰 Tools & Libraries Used

- **Python (Jupyter Notebook)**
- **Pandas** – For data wrangling, grouping, and KPI computation
- **Matplotlib** – For professional and customizable visualizations

---

## 📊 Data Preparation & EDA

Performed exploratory analysis using `pandas`:

- Cleaned the dataset by handling null values and checking for duplicates
- Used `groupby()` to calculate total sales across Outlet Size, Fat Content, Item Type, Location, and Establishment Year
- Applied `sort_values()` to identify top-performing categories
- Generated descriptive stats like total and average sales to support visual analysis

---

## 📌 Key Performance Indicators (KPIs)

| KPI | Description |
|-----|-------------|
| 💰 Total Sales (₹) | Aggregated revenue across dimensions |
| 🏬 Outlet Size Contribution | Sales distribution across Small, Medium, and High outlets |
| 🍶 Fat Content Preference | Breakdown of Low Fat vs Regular product sales |
| 🏙️ Location Tier Performance | Sales by Tier 1, Tier 2, and Tier 3 cities |
| 📅 Sales by Establishment Year | Trend of outlet performance over time |
| 🧺 Top Product Categories | Item types driving the most revenue |

---

## 📊 Visual Insights

### 1. **Total Sales by Outlet Size**
- **Medium-sized outlets lead with 42.3%** of total sales, suggesting optimal operational scale.
  
### 2. **Total Sales by Fat Content**
- **Low Fat products dominate (64.6%)**, indicating a strong preference for healthier alternatives.

### 3. **Sales by Outlet Establishment Year**
- Outlets established **before 2000 show peak sales**.
- Sharp dip around 2011 could indicate underperformance due to operational or economic factors.

### 4. **Sales by Outlet Location & Fat Content**
- **Tier 3 outlets outperform Tier 1 and Tier 2** in overall sales.
- Across all tiers, **Low Fat products consistently outsell Regular items**.

### 5. **Sales by Item Type**
- **Top-selling categories**: *Fruits & Vegetables*, *Snack Foods*, and *Household Items*.
- **Low-performing categories**: *Seafood*, *Breakfast*, *Starchy Foods*.

---

## 🧠 Business Concepts Used

- **Customer Preference Profiling** – Based on fat content and item category trends.
- **Market Segmentation** – Tier-wise and outlet-size-based revenue insights.
- **Product Performance Analysis** – Ranking item types by revenue contribution.
- **Trend Analysis** – Linking outlet age to sales behavior.
