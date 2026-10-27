# 📊 E-Commerce Sales & Customer Analytics (Advanced Excel)

## 🎯 Project Overview
This project was developed during a professional **Data Analytics Course** to demonstrate practical data engineering, database structuring, and descriptive analytics within Microsoft Excel. Running online store transaction logs generates high-volume multi-dimensional datasets. This project transforms **raw e-commerce logs into clear, organized analytical modules** covering sales performance, product categories, geographic distribution, and individual customer purchase frequencies from January to September 2026.

* **Developer:** Dilshadh J B
* **Core Focus:** Data Sanitization, Advanced Formulas, and Interactive Dashboards

## 🛠️ Advanced Excel Functions Implemented
* **Data Sanitization:** Converted raw unstructured text blocks into a formal Excel Table schema, ran structural duplication reviews, verified field integrity, and adjusted formatting attributes.
* **Nested Logical Formulas:** Developed automated data segmentation flags:
  * `Delivery Status = IF(DeliveryDays<=3,"Fast", IF(DeliveryDays<=6,"Normal","Delayed"))`
  * `Sales Category = IF(NetSales>=50000,"High", IF(NetSales>=20000,"Medium", "Low"))`
* **Dynamic Indexing & Custom Arrays:** Integrated advanced `XLOOKUP` matrices to dynamically match indices without manual input, paired with conditional statistical functions (`SUMIF`, `COUNTIF`, `AVERAGEIF`, `COUNTA`).

## 📷 Spreadsheet Analytical Dashboard
<!-- DROP YOUR SCREENSHOT RIGHT BELOW THIS LINE -->
<img width="704" height="530" alt="image" src="https://github.com/user-attachments/assets/bb22ad7e-b3c0-4ab0-ae1b-46c73cc54e4e" />


## 📈 Operational Summary Performance (45 Main Orders / 10 Unique Customers)

| Performance Indicator | Consolidated Outcome Metric |
| :--- | :--- |
| **Total Net Sales Portfolio** | ₹15,14,120 |
| **Average Order Value (AOV)** | ₹33,647.11 |
| **Highest Order Invoice Value** | ₹1,23,500 |
| **Total Product Units Distributed** | 162 Units Sold |
| **Average Delivery Turnaround Time** | 4.47 Days |

## 🔍 Multi-Dimensional Data Summaries (PivotTables)
* **Regional Performance:** Geographic evaluations isolate **Tamil Nadu as the peak market sector**, yielding ₹9,98,710 of total revenue.
* **Product Segment Leadership:** Electronics stands as the primary structural earner, capturing ₹11,04,870 in sales volume.
* **Customer Lifetime Activity:** Identified top buyer metrics; client **Suresh P leads structural database volume with 9 distinct invoices totaling ₹2,54,020**.
* **Payment Velocity:** Digital transaction channels dominate; **UPI ranks as the most frequent payment method**, accounting for 21 total orders and ₹8,68,020 in revenue.
