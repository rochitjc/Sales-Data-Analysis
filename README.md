# 📊 SuperMart Sales Analysis (2020–2023)

## 🏢 Project Background

SuperMart, established in 2018, is a U.S.-based national retailer specializing in office supplies, furniture, and technology products. It serves both businesses and individual consumers through  offline channel. The company has accumulated a rich dataset encompassing sales, product performance, and regional trends.

As a data analyst at SuperMart, this project analyzes sales data from 2020 to 2023 to uncover patterns, identify risks, and recommend actions that can optimize sales strategy, product assortment, and regional focus.

---

## 🔍 Focus Areas

Insights and recommendations are provided across the following categories:

- **Category 1: Yearly KPI Trends**
- **Category 2: Monthly and Weekly Sales Patterns**
- **Category 3: Product Subcategory Performance**
- **Category 4: Profit Margin Analysis**

- Dataset:  
- [Tableau dashboard for interactive exploration](https://public.tableau.com/app/profile/rochit.choudhary8883/viz/Dashboard_17467052469810/SalesDashboard?publish=yes)

---

## 🗃️ Data Structure & Initial Checks

SuperMart’s sales data is structured into three main tables:

### Table 1: Orders
> Contains transactional-level sales data  
**Key Fields:** Row ID, Order ID, Order Date, Ship Mode, Customer ID, Segment, Postal Code, Product ID, Sales, Quantity, Discount, Profit

### Table 2: Products
> Contains product catalog and classification  
**Key Fields:** Product ID (PK), Category, Sub-Category, Product Name

### Table 3: Location
> Geographic mapping of sales orders  
**Key Fields:** Postal Code (PK), City, State, Region, Country/Region

### Entity Relationships
- Orders ↔ Products (via Product ID)  
- Orders ↔ Location (via Postal Code)

📌 *Entity Relationship Diagram:*  


---

## 🧠 Executive Summary

Between 2020 and 2023, SuperMart saw strong revenue and profit growth, nearly doubling both. However, profit margins peaked in 2022 and declined in 2023, highlighting emerging challenges.

### Top 3 Takeaways:
1. 📈 **Consistent growth** in sales and profit, especially post-2021.
2. ⚠️ **Profit margin decline in 2023**, despite revenue growth.
3. ❗ **Persistent loss-makers** in subcategories like Tables and Bookcases need urgent attention.

---

## 📌 Overview of Findings

- **Sales Growth:** From $484K (2020) to $733K (2023)
- **Profit Growth:** From $50K to $93K
- **Profit Margin:** Rose from 10.23% (2020) to 13.43% (2022), dropped to 12.74% (2023) 
- **Seasonality:** December consistently highest sales month; January the lowest
- **Risk Areas:** Losses in Tables, Bookcases, and new 2023 drop-offs (e.g., Envelopes, Machines)

📊 *Overall Trend Snapshot:*  
[Overall KPI Trends](#)

---

## 🔬 Insights Deep Dive

### 📆 Category 1: Yearly KPI Trends

- Sales and profit grew each year, except a slight dip in 2021 sales (-2.8%) despite a margin jump (+28%).
- 2022 was the most efficient year: +29.5% sales, +32.7% profit, 13.43% margin.
- 2023 saw growth (+20.4% sales) but declining margin (–5.09%).
- Weekly averages steadily increased across KPIs.

📊 *Visualization:* KPI trends dashboard top row  
![KPI Trends](#) all year photos kpi

---

### 📅 Category 2: Monthly and Weekly Sales Patterns

- December = peak month every year; January = lowest.
- February often sees highest profit margins, while March–April show dips.
- Weekly trends reveal volatility, especially in 2021 and 2023.
- Q4 clusters strong performance—room to capitalize further.

📊 *Visualization:* Sales & profit trends over time  
![Monthly and Weekly Trends](#)spot

---

### 📦 Category 3: Product Subcategory Performance

- Phones, Copiers, and Labels are top performers. Labels had >40% margin in 2022–2023.
- Tables and Bookcases = consistent loss-makers.
- Envelopes, Fasteners, and Machines flipped to negative in 2023.
- Binders, Chairs, and Storage show promising growth.

📊 *Visualization:* Sales & profit by subcategory  
![Subcategory Comparison](#)

---

### 💰 Category 4: Profit Margin Analysis

- Margin gains in 2021–2022 reflect cost control and product strategy.
- 2023’s margin decline likely due to rising costs or discounting.
- Weekly margin volatility decreased post-2021 but still needs work.
- High-margin categories help offset weak performers.

📊 *Visualization:* Profit margin analysis  
![Profit Margin Trends](#)

---

## ✅ Recommendations

### 1. Address Loss-Making Subcategories
> Reassess pricing and sourcing for Tables, Bookcases, and 2023’s new loss-makers.

### 2. Investigate 2023 Margin Decline
> Analyze cost structures, discounting, and product mix shifts.

### 3. Capitalize on Seasonality
> Plan inventory and campaigns around Q4 peaks and Jan lulls.

### 4. Focus on High-Margin Winners
> Invest in marketing, availability, and promotions for Labels, Copiers, and Phones.

### 5. Stabilize Weekly KPIs
> Identify and smooth causes of weekly profit volatility.

---

## ⚠️ Assumptions and Caveats

- **Data Completeness:** Assumes all records are accurate and complete across years.
- **Product Categorization:** Assumes consistency in subcategory definitions.
- **Profit Calculation:** Assumes cost attribution is accurate.
- **External Factors:** Analysis excludes macroeconomic influences (e.g., inflation, supply chain issues).

---

