# 📊 Acadio.io BI Intern Dashboard Project

This repository contains the Power BI dashboard and supporting code I developed during my BI internship at **Acadio.io**. The goal was to analyze retail sales data, segment customers, and surface actionable insights for department managers and marketing teams.

---

## 🔍 Business Questions

1. **How are total sales and customer counts trending year-over-year?**  
2. **Which departments drive the most revenue and which lag behind?**  
3. **Which customer segments deliver the highest sales, volume, and average spend?**  
4. **What is the year-over-year growth in sales and customers, and which segments or departments contain high-value customers?**

---

## 🛠 Analysis Approach

- **Data Preparation & Feature Engineering**  
  - **Python (pandas, numpy)** for cleaning, aggregation, and new features:  
    - `Avg_Sales_Per_Customer`  
    - `High_Value_Segment` flag (top 25% by avg spend)  
- **Visualization & Dashboarding**  
  - **Power BI Desktop** for interactive reports  
  - **Power Query** for in-tool transformations  

---

## 📈 Dashboard Pages

### 1️⃣ Page 1: Sales & Customer Overview  
![Page 1](https://github.com/user-attachments/assets/1f3e040b-c22a-4350-ab75-e61dd897c870)  
- **KPIs:**  
  - Total Sales: **\$11.86 M**  
  - Total Customers: **971 K**  
  - Avg. Sales / Customer: **\$8.01**  
- **Department Highlights (2022 → 2023):**  
  - **Highest Sales:** Knick Knacks (\$6,520,808.64)  
  - **Lowest Sales:** Store Use (\$71,257.50)  
  - **Highest Customer Count:** Formal Wear (167,630)  
  - **Lowest Customer Count:** Shirts (29,965)  
- **Year-over-Year Sales Changes:**  
  - **↑** Boot Accessories, Boots, Cowboy Hats, Shirts, Store Use  
  - **↓** Beachwear, Knick Knacks, Formal Wear, Misc, Women’s Jeans  

---

### 2️⃣ Page 2: Segment & Profile Analysis  
![Page 2](https://github.com/user-attachments/assets/e378a647-32ab-42c4-9eef-acb050bd77d1)  
#### 2022  
- **Top Sales Segments:**  
  - Elite Customers: \$1,869,370.18  
  - Core Customers: \$1,666,697.62  
- **Top Customer Volumes:**  
  - Elite: 123,817  
  - Core: 101,420  
- **Avg Spend / Customer:**  
  - Elite: \$9.38  
  - Core: \$8.21  

#### 2023  
- **Top Sales Segments:**  
  - Elite Customers: \$1,150,360.97  
  - New Customers: \$1,097,916.82  
- **Top Customer Volumes:**  
  - Elite: 115,880  
  - New: 103,929  
- **Avg Spend / Customer:**  
  - Elite: \$11.03  
  - New: \$8.20  

---

### 3️⃣ Page 3: Growth & High-Value Focus  
![Page 3](https://github.com/user-attachments/assets/81e56c63-aa24-422f-ad64-fd4b896d8c93)  
- **Overall Growth (2022 → 2023):**  
  - Sales Growth: **–41 %**  
  - Customer Growth: **–34 %**  
- **High-Value Customer Share:**  
  - **Yes:** 19 % of profiles  
  - **No:** 81 % of profiles  
- **Departments with 0 High-Value Customers:**  
  Formal Wear, Boots, Boot Accessories, Store Use  
- **Visuals:**  
  - Line charts: Sales & Customers by Year & Segment  
  - Pie chart: Profiles by High_Value_Segment  
  - Bar charts:  
    - Total Sales by Profile Description & High_Value_Segment  
    - Total Sales by Department Description & High_Value_Segment  

---

## 🔗 Interactive & Download Links

- 📄 **PDF Export:** [`Power BI dash in pdf.pdf`](./Power%20BI%20dash%20in%20pdf.pdf)  
- 🌐 **Live Dashboard:**  
  https://app.powerbi.com/links/g2YEBD44vF?ctid=56c1d497-700b-49cf-8f8d-3dd6b20d522f&pbi_source=linkShare  

---

## ✅ Key Learnings & Takeaways

- **Python + pandas** enabled rapid feature creation and EDA.  
- **Power BI** visuals drive stakeholder engagement with interactive slicers (Segment, Year, Department).  
- Combining **aggregate KPIs** with **segment-level** and **growth** analyses surfaces targeted opportunities.

---

> 📣 **For more details**, open the PDF export or explore the interactive PBIX file in Power BI Service.  
