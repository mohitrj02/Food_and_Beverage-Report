# 🧾 Green Beverages Report: Power BI Dashboard

<div align="center">
<img src=https://github.com/mohitrj02/Food_and_Beverage-Report/blob/main/imgs/1%20Home_page.png alt="Full Dashboard Screenshot" width="100%">
<table>
  <tr>
    <td align="center">
      <img src="https://github.com/mohitrj02/Food_and_Beverage-Report/blob/main/imgs/2%20Detail_page.png" width="500"/><br>
    </td>
    <td align="center">
      <img src="https://github.com/mohitrj02/Food_and_Beverage-Report/blob/main/imgs/3%20More_info_page.png" width="500"/><br>
    </td>
  </tr>
</table>

</div>

## ✅ Objective

To create a comprehensive Power BI dashboard that provides clear, visual insights into revenue trends, product category performance, customer segmentation, and sales behavior in the Green Beverages F&B (Food & Beverages) industry. The report empowers decision-makers to act on data-backed insights quickly and effectively.

---

## 📌 1. Purpose of the Dashboard

This dashboard offers a consolidated view of the Green Beverages F&B business performance, focusing on:

- Revenue performance over time  
- Sales trends by year and month  
- Product category contributions  
- Customer segmentation and behavior  
- Sales team experience and its influence  
- Product-level volume and distribution  

It is designed for business stakeholders to understand overall revenue movement, category performance, and operational metrics such as billing and discount distribution.

---

## 📦 2. What This Project Involves

This Power BI project includes the following key components:

- **Data Cleaning & Shaping** using Power Query  
- **Data Modeling** with relationships between tables (e.g., Customers, Products, Orders)  
- **DAX Measures** to calculate key KPIs such as Net Revenue, YoY Growth, Discount %, and G2N  
- **Interactive Dashboard Design**, featuring:
  - Card visuals for high-level KPIs  
  - Bar and line charts for revenue trends  
  - Slicers and filters for deep-dive analysis  
- **PDF Export Capability** for stakeholder sharing and offline reporting

---

## 📚 3. Dataset Description & Data Model

The dashboard is built on a structured dataset composed of **multiple related tables** that represent key business entities. Here's a breakdown:

### 🗃️ Key Tables Used

| Table Name        | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `Customer`        | Contains customer-level information such as name, type, region, and grade  |
| `Sales`           | Transactional data including bill number, product code, order date, volume |
| `Product`         | Product details such as category, color, price/kg, and unit conversion      |
| `CalendarTable`   | A date dimension table for managing time-based analysis                     |
| `Area`            | Links customers with geographical data via city and beat codes             |
| `Beat`            | Maps beat code to sales regions and associated salespersons                |
| `Sales Person`    | Contains salesperson details including name, experience, and region        |
| `Customer Grade`  | Details on discount types, trade type, and grade associated with customers |

### 🧭 Data Modeling & Relationships

The model uses **star schema logic**:
- **Sales** is the central fact table
- Dimension tables (Customer, Product, CalendarTable, etc.) are connected via keys such as:
  - `Customer ID`
  - `Product Code`
  - `Order Date`

The relationships are managed in **Power BI’s Data Model View**, as visualized below:
<br><br><img src=https://github.com/mohitrj02/Food_and_Beverage-Report/blob/main/imgs/5%20Tables.png width="100%">

---

## 📊 5. Key Metrics and Visuals

### 🧮 Key Performance Indicators (KPIs):
- **Net Revenue (NR):** $15.5 Billion (2018–2020)  
- **Year-over-Year Growth:**  
  - +34.79% compared to previous years  
  - +8.22% from 2019 to 2020  
- **G2N (Gross to Net per Kg):** $15.4  
- **Total Bills Generated:** 81.43K  
- **Leaves Needed:** (Data present but not fully visible)  
- **Discount %:** 5.00%

### 📅 Time-Based Views:
- Yearly Net Revenue (2018–2020)  
- Monthly breakdown with YoY delta and percentage growth  
- Quarterly revenue summaries

### 📦 Product Category Breakdown (by Volume in Thousand Tons):
- **Tea:** Dust Tea, Green Tea, Flavor Tea, Tea Bag  
- **Coffee:** Coffee Sachet, Coffee Box  
- **Condiments:** Mustard Sauce, Tomato Ketchup  
- **Snacks:** Choco Bread, Frozen Pizza, Almonds

### 🗂️ Customer Segmentation:
- **Customer Types:** General, Online, Institutional, Retail Chain  
- **Salesman Experience:** Ranges from 5 to 37 years  
- **Customer Count:** 55 customers observed

---

## 🌍 6. Data Story & Insights

- **Revenue Recovery & Growth:**  
  A strong recovery is observed from 2019 to 2020, with a revenue increase of 8.22%, continuing a positive trend after a dip in 2019.

- **Quarterly Peaks in Revenue:**  
  Q2 and Q3 (April–September) show revenue spikes, indicating seasonal strength or successful campaigns.

- **Best Performing Months:**  
  - **June** recorded the highest revenue: $705.84K  
  - **April** showed the highest YoY growth: 19.11%

- **Diverse Product Range:**  
  Broad product offering with beverages and condiments performing strongly.

- **Customer Type Impact:**  
  Online and Institutional customers consistently outperform General and Retail Chain types in revenue contribution.

---

## 🧠 7. Recommendations

1. **Optimize Campaigns Around Q2/Q3 Peaks:**  
   Leverage historical data to time promotional efforts and product launches.

2. **Re-evaluate Discount Strategy:**  
   Assess if the 5% flat discount is equally effective across all categories and customer segments.

3. **Focus on High-Margin Categories:**  
   Prioritize growth in high G2N and volume categories, such as premium teas or condiments.

---

## 💼 8. Business Use Case

In the competitive F&B industry, understanding sales performance is crucial for strategic decision-making. This dashboard supports:

- 📈 **Sales Monitoring** – Analyze performance by time period and product category  
- 🛒 **Customer Segmentation** – Evaluate which customer types generate the most revenue  
- 🤝 **Sales Team Performance** – Examine the impact of experience on results  
- 💰 **Discount Strategy Evaluation** – Understand if flat discounts align with profitability  
- 🔍 **Product-Level Insights** – Identify high and low-performing product categories

  It empowers sales managers, marketing teams, and finance analysts to make informed decisions about pricing, campaigns, and inventory strategy.
---

## 📁 Folder Structure

```plaintext
├── Data/
│   └── All Data.xlxs
├── Dashboard/
│   └──  F&B Report.pbix
├── Screenshots/
│   └── img file
├── README.md
```
---

## 📸 Dashboard Previews

<div align="center">
<img src=https://github.com/mohitrj02/Food_and_Beverage-Report/blob/main/imgs/1%20Home_page.png width="90%">
<img src="https://github.com/mohitrj02/Food_and_Beverage-Report/blob/main/imgs/2%20Detail_page.png" width="90%"/><br>  
<img src="https://github.com/mohitrj02/Food_and_Beverage-Report/blob/main/imgs/3%20More_info_page.png" width="90%"/><br>
</div>


