# 🌾 Agricultural Price Volatility & Market Efficiency Dashboard

This project presents a **data-driven analysis of agricultural mandi prices in India**, focusing on **price volatility, seasonal risk, market fairness, and regional instability**. The dashboards are designed to convert raw price data into **actionable insights** for farmers, analysts, and policymakers.

---

## 📊 Project Overview

Agricultural prices in India fluctuate due to seasonality, weather, supply-demand mismatches, and market inefficiencies. This project answers key questions such as:

* Are agricultural prices becoming more unstable over time?
* Which crops are the most volatile?
* When do price shocks occur?
* Which markets consistently overpay or underpay farmers?
* Which states face the highest price instability?

The analysis is presented through **two interactive Power BI dashboards**:

1. **Dashboard 1: Overview & Key Insights**
2. **Dashboard 2: Market Risk & Efficiency Analysis**

---

## 🧩 Data & Metrics Used

### Key Metrics

* **Modal Price (₹/Quintal)** – Most frequently traded price
* **Rolling 7-Day Volatility** – Short-term price instability indicator
* **Daily Price Change** – Day-to-day price movement
* **Price Spread** – Difference between max and min prices within a market
* **Market Average Price** – Typical price level of a market
* **Price Deviation** – Difference between market price and market average price

These metrics together help measure **instability, risk, and market efficiency**.

---

## 📘 Dashboard 1: Overview & Key Insights

### 🎯 Purpose

High-level, executive-friendly view of **overall price behaviour and risk patterns**.

### 🔍 Visuals & Insights

#### 1️⃣ Price Volatility Over Time

* Line chart showing **Average Rolling 7-Day Volatility by Date**
* Includes a trend line to identify long-term movement

**Insight:**

> Overall agricultural price volatility shows an upward trend with sharp seasonal spikes, indicating increasing market instability.

---

#### 2️⃣ Commodity-Level Volatility

* Bar chart comparing **average volatility across commodities**

**Insight:**

> Tomato and onion are the most volatile commodities, while wheat and rice remain relatively stable.

---

#### 3️⃣ Price Volatility Risk Heatmap (2023–2025)

* Heatmap showing **commodity-wise volatility across years**

**Insight:**

> Market-wide volatility has increased from 2023 to 2025, driven mainly by perishable crops.

---

#### 4️⃣ Key KPI Cards

* Average Modal Price
* Average Price Volatility
* Average Price Spread
* Total Daily Price Change

**Purpose:**

> Provides a quick numerical summary of the overall market condition.

---

## 📙 Dashboard 2: Market Risk & Efficiency Analysis

### 🎯 Purpose

Identify **where risks are concentrated** and **how fair and efficient markets are**.

---

### 🔍 Visuals & Insights

#### 1️⃣ Top 10 Overpaying Markets

* Markets consistently paying **above the market average price**

**Insight:**

> These markets offer better price realization and are more attractive selling destinations for farmers.

---

#### 2️⃣ Bottom 10 Underpaying Markets

* Markets consistently paying **below the market average price**

**Insight:**

> These markets pose income risk to farmers due to persistent underpayment.

---

#### 3️⃣ Top 10 States by Price Volatility

* State-wise comparison of average price instability

**Insight:**

> Price instability is concentrated in select states, indicating higher regional market risk.

---

#### 4️⃣ Market Efficiency Logic (Underlying Analysis)

Markets are evaluated using:

* **Price Spread** → Internal market inconsistency
* **Price Deviation** → Fairness relative to other markets

This helps identify:

* Efficient & fair markets
* Inefficient markets
* Underpaying or high-risk markets

---

## 📌 Key Takeaways

* **Perishable crops** (Tomato, Onion) drive most price instability
* **Price shocks are seasonal**, not random
* **Market fairness varies significantly** across regions
* **A small number of markets and states account for most risk**

---

## 🧠 Use Cases

* **Farmers:** Decide *where and when* to sell
* **Policymakers:** Identify regions needing intervention
* **Analysts:** Study volatility, risk, and efficiency patterns
* **Students:** Example of real-world data analysis using Power BI

---

## 🛠 Tools Used

* **Power BI** – Data modeling & visualization
* **Power Query** – Data cleaning & feature engineering
* **DAX** – Rolling volatility, deviation & aggregation logic

---

## ✅ Conclusion

This project demonstrates how agricultural price data can be transformed into **clear, actionable insights** using data analysis and visualization. By focusing on volatility, seasonality, and market efficiency, the dashboards provide a **practical decision-support tool** rather than just descriptive charts.

---

📌 *Designed for clarity, interpretability, and real-world relevance.*
