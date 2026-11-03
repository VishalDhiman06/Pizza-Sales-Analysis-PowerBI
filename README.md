<div align="center">

# 🍕 Pizza Sales Analysis

### Interactive Power BI Report to Uncover Order Trends, Best Sellers and Worst Sellers

</div>

---

## 📝 Description & Purpose

An interactive two-page Power BI report that analyzes **pizza orders, revenue and customer buying patterns** for 2015. It helps a pizza business understand when it is busiest, which categories and sizes sell best, and which individual pizzas drive or drag down performance.

**Problem statement:** Which days, months, pizza categories, sizes and individual pizzas drive the most orders and revenue, and how can a pizza business use this to plan staffing, stock, menu and promotions?

---

## 🛠️ Tech Stack

- 🟨 **Microsoft Power BI Desktop**
- 🧹 **Power Query:** data cleaning and transformation
- 🧱 **Data modeling**
- 🧮 **DAX:** KPI measures and Top/Bottom 5 rankings
- 🎨 **Dashboard design and data storytelling**

---

## 📂 Data Source

Pizza sales dataset for **January to December 2015**, loaded into Power BI and cleaned in Power Query. It covers **21,350 orders** and **49,574 pizzas sold**, with fields such as:

- 🍕 **Pizza details:** pizza name, category and size
- 🧾 **Order details:** order date, quantity and order value
- 💰 **Performance:** revenue, quantity and total orders

---

## ✨ Features & Highlights

### 📈 KPIs tracked

| 💰 Total Revenue | 🧾 Avg Order Value | 🍕 Avg Pizzas Per Order | 🛒 Total Orders | 📦 Total Pizzas Sold |
|:---:|:---:|:---:|:---:|:---:|
| **817.86K** | **38.31** | **2.32** | **21,350** | **49,574** |

### 🧩 Page 1: Home

| # | Analysis | Chart Type |
|:---:|---|---|
| 1️⃣ | Daily Trend for Total Orders | 📊 Column Chart |
| 2️⃣ | Monthly Trends for Total Orders | 📈 Area / Line Chart |
| 3️⃣ | % of Sales by Pizza Category | 🍩 Donut Chart |
| 4️⃣ | % of Sales by Pizza Size | 🍩 Donut Chart |
| 5️⃣ | Total Pizzas Sold by Pizza Category | 🔻 Funnel Chart |

### 🏆 Page 2: Best / Worst Sellers

| Ranking | By Revenue | By Quantity | By Total Orders |
|---|:---:|:---:|:---:|
| **Top 5** | 📊 Bar Chart | 📊 Bar Chart | 📊 Bar Chart |
| **Bottom 5** | 📊 Bar Chart | 📊 Bar Chart | 📊 Bar Chart |

### 🎛️ Interactive features

- 🎚️ **Slicers:** Pizza Category and a date range, applied across both pages
- 🧭 **Navigation buttons** between the Home and Best/Worst Sellers pages
- 📝 **Insight panels** summarizing busiest days and months, sales performance, best sellers and worst sellers
- 🖌️ Clean purple and blue theme with a pizza-themed header

### 💡 Key insights

| 🔍 Area | 📌 Finding |
|---|---|
| 📅 **Busiest Day** | **Friday** has the most orders, followed by Thursday and Saturday. **Sunday** is the quietest |
| 🗓️ **Busiest Month** | **July** peaks for orders, while **January** is the lowest |
| 🍕 **Category** | **Classic** leads with about **27%** of sales, then Supreme, Chicken and Veggie at about 24 to 25% each |
| 📏 **Size** | **Large** pizzas make up about **46%** of sales, Medium about 31% and Small about 22% |
| 💰 **Top Revenue** | **The Thai Chicken Pizza** and **The Barbecue Chicken Pizza** lead at about 43K each. Three of the top 5 are chicken pizzas |
| 📦 **Top Quantity and Orders** | **The Classic Deluxe Pizza** sells the most (about 2.5K) and gets the most orders (about 2.3K) |
| ⚠️ **Worst Seller** | **The Brie Carre Pizza** is last on all three measures: about 12K revenue, 490 pizzas and 480 orders, roughly half of the next lowest pizza |
| 🧾 **Basket** | Customers order about **2.3 pizzas** per order, with an average order value of **38.31** |

<details>
<summary><b>👉 Click to see recommendations</b></summary>

<br>

- **Staffing and stock:** plan extra staff and ingredients for Thursday to Saturday, the busiest period.
- **Quiet days:** run Sunday and Monday offers to lift low order days.
- **Seasonality:** use the January dip and the September to October dip for promotions.
- **Menu:** keep Classic Deluxe as the volume leader and promote Thai Chicken and Barbecue Chicken, which earn the most revenue.
- **Menu review:** The Brie Carre Pizza sells about half as much as the next worst pizza, so consider removing it or relaunching it with a promotion.
- **Sizes:** X-Large and XX-Large sell very little (under 2%), so review whether they are worth stocking.

</details>

---

## 🖼️ Screenshots

### Home

![Home Page](pizza-home.png)

### Best / Worst Sellers

![Best and Worst Sellers Page](pizza-best-worst.png)

▶️ **How to open the report**

1. Install the free [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
2. Download the `.pbix` file from this repository
3. Open it and use the slicers and page buttons to explore

---

<div align="center">

### 📬 Let's Connect

**Vishal Dhiman**

[🔗 Connect with me on LinkedIn](https://www.linkedin.com/in/vishal-dhiman-16306331a/)

⭐ **If you found this project useful, give it a star!** ⭐

</div>
