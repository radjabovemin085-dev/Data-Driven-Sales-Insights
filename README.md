# 📊 Adventure Works: Executive Sales & Deep Analysis Intelligence

## 📝 Project Overview
This repository features a comprehensive, end-to-end Power BI solution based on the **Adventure Works** dataset. The project transitions from high-level executive reporting to granular, AI-driven data exploration, providing a 360-degree view of sales performance, regional trends, and product profitability.

The core objective was to move beyond static charts and build a dynamic **Analytical Application** that allows stakeholders to uncover the **"Why"** behind the numbers.

---

## 🛠️ Technical Stack & Implementation
* **Power BI Desktop:** Advanced data visualization and UI/UX design.
* **DAX (Data Analysis Expressions):** * Time Intelligence (YoY Growth, Revenue Previous Year).
    * Dynamic filtering and ranking.
* **Data Modeling:** Implementation of a **Star Schema** to ensure high-performance reporting and filter integrity.

---

## 🚀 Key Features & Navigation
The dashboard is structured into two main analytical layers accessible via custom **Bookmark Navigation**:

### 1. General Report (Strategic View)
Focused on "What happened?".
* **Executive KPIs:** Real-time tracking of Total Revenue ($109.85M), Revenue Previous Year ($64.84M), and a 69% Growth trajectory.
* **Top 5 Regions:** A dynamic Bar Chart highlighting the top-performing territories like Southwest ($24.2M).
* **Heat Map Matrix:** A detailed cross-analysis of Regions vs. Categories (Customer, Reseller, No Discount).

### 2. Deep Analysis (Tactical & AI View)
Focused on "Why did it happen?".
* **Decomposition Tree (AI Powered):** A machine learning-backed visual that allows users to drill down into the root causes of revenue fluctuations across Groups and Regions.
* **Dynamic Line Chart:** Equipped with **Drill-Down** capabilities to analyze sales volatility from years down to months.

---

## 📸 Dashboard Preview

### **General Report View**
![General Report](111.png)

### **Deep Analysis View**
![Deep Analysis](222.png)

---

## 💡 Key Business Insights
* **Regional Dominance:** The **Southwest** region remains the primary revenue driver, contributing significantly to the total portfolio.
* **Growth Trajectory:** The business experienced a massive **69% YoY growth**, showcasing strong performance in the current period.
* **Granular Exploration:** Using the Decomposition Tree, we can identify that **North America** (specifically the Southwest) is the core pillar of the sales structure.

---

## 📂 How to Use
1. Clone this repository.
2. Open the `.pbix` file using Power BI Desktop.
3. Use the **"General Report"** and **"Deep Analysis"** buttons at the top right to switch between views.
4. Interact with the **Decomposition Tree** by clicking the **"+"** icons to explore data layers.
