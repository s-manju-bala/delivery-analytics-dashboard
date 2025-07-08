🚚 Delivery Analytics Dashboard (Power BI + Python EDA)

This project presents a comprehensive Delivery Analytics Dashboard built with Power BI, backed by thorough Python-based Exploratory Data Analysis (EDA). It empowers businesses to measure vendor delivery performance, spot inefficiencies, and streamline operations across the supply chain.

---

## 🧠 Project Scope
Analyze end-to-end delivery lifecycle using:
- Vendor performance
- Delivery timelines
- Invoicing and payment cycles
- Profitability & stock efficiency

---

## 🐍 Python: Exploratory Data Analysis (EDA)

Used **Pandas**, **Matplotlib**, and **Seaborn** for:
- Cleaning and merging:
  - `vendor_invoice.csv`
  - `purchases.csv`
  - `sales.csv`
  - `purchase_prices.csv`
- Feature engineering:
  - `DeliveryTimeInDays`
  - `InvoiceProcessingTimeInDays`
  - `PaymentProcessingTimeInDays`
  - `TotalCycleTimeInDays`
  - `GrossProfit`, `ProfitMargin`, and `SalesToPurchaseRatio`
  - `IsLate` (based on SLA of 3 days)
- Exported processed files:
  - `vendor_performance_summary.csv`
  - `delivery_timing_summary.csv`

---

## 💡 SQL Processing Highlights

Used **SQL CTEs** (Common Table Expressions) to:
- Aggregate delivery records across vendors and POs
- Join multiple tables with clean, readable queries
- Derive metrics for funnel analysis and stage tracking

---

---

## 📊 Key KPIs
| KPI                            | Value   |
|-------------------------------|---------|
| 📦 Total Orders               | 2M      |
| 💰 Total Purchase Price       | 3.29M   |
| 📈 Total Purchase Quantity    | 34M     |
| 💸 Gross Profit               | 22.32B  |
| 💯 Profit Margin (%)          | 99.44%  |
| 🔁 Stock Turnover             | 9.44    |
| ⏱️ Avg Delivery Time (Days)   | 7.62    |
| ✅ On-Time Delivery %         | 31%     |

---

## 📍 Filters
- **Year of Purchase** (2023, 2024)
- **Month of Purchase**

---

## 📈 Charts & Visuals

### 📌 On-Time vs Late Deliveries by Brand
> Compare delivery status for each brand to identify laggards and consistent performers.

### ⏳ Delivery Time Distribution
> Area chart showing delivery time (in days) across PONumbers for volume trends and outliers.

### 🛑 Bottom 5 Vendors by Delivery Time
> Vendors with the **longest average delivery times** that might cause operational bottlenecks.

### 🧾 Funnel View – Total Orders by Stage
> Visual breakdown of stages like:
- PO Raised
- Order Received
- Payment Completed
- Invoice Processed

### 💰 Top 5 Vendors by Profit
> High-value contributors ranked by **gross profit**.

### 🔄 Top 5 Brands by Stock Turnover
> Operational efficiency across fast-moving brands.

### 📆 Average Delivery Time Over Time
> Line chart of average delivery duration month-over-month to detect seasonal or operational trends.

---

## 📸 Screenshots

### Dashboard Overview
![Vendor's Delivery Analytics Dashboard](https://github.com/user-attachments/assets/7544985b-89f3-48f9-afac-8d5675dde084)

### Delivery Time Distribution
![Delivery Time Distribution](https://github.com/user-attachments/assets/3f85e50e-21bf-49ff-8302-6e9847aafd0a)

### On-Time vs Late Deliveries
![On-Time vs Late](https://github.com/user-attachments/assets/eee402de-1179-4b7d-8491-d267cc1c9c5e)

### Bottom 5 Vendors
![Bottom Vendors](https://github.com/user-attachments/assets/ec6cdd87-ea0f-4aff-9957-830d1403bfff)

📂 Download the full Power BI Dashboard (.pbix):  
https://drive.google.com/file/d/1NQCy8RvJGUFgaYSnLD35DcTizAGjM5Ux/view?usp=sharing

---

## 🧰 Tools Used
- 🐍 Python (Pandas, Matplotlib, Seaborn)
- 📊 Power BI
- 🧮 DAX for calculated measures
- 📁 CSV for clean data input

---

## 🙋‍♂️ Author
**MANJU BALA S**  
Aspiring Data Analyst  
📧 smanjubala@outlook.com
🌐 https://www.linkedin.com/in/manjubala-sundaramoorthy/

---


