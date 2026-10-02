# Blinkit Business Analytics & Dashboard

An end-to-end Excel Business Analytics project built using Blinkit-style operational, customer, product, delivery, feedback, inventory, and marketing data.

The project focuses on transforming raw business datasets into an interactive analytics dashboard using Excel, PivotTables, relationships, calculated metrics, and visualizations.

---

## 📊 Project Overview

This project analyzes Blinkit's business performance across multiple dimensions including:

- Sales & Revenue
- Orders & Customers
- Product Performance
- Delivery Performance
- Customer Feedback & Ratings
- Inventory & Product Damage
- Marketing Performance
- Customer Segmentation
- Regional Order Analysis

The final output is an interactive **Blinkit Business Analytics Dashboard** designed to provide a quick overview of important business KPIs and operational trends.

---

## 🎯 Objectives

- Analyze overall business revenue and order performance
- Understand customer segments and purchasing behavior
- Identify product-level sales and quantity trends
- Analyze delivery performance and delays
- Evaluate customer ratings and feedback
- Monitor product damage and inventory-related metrics
- Analyze marketing revenue and ROAS by channel
- Create an interactive business dashboard for decision-making

---

## 🗂️ Dataset Structure

The project uses 8 CSV datasets:

| Dataset | Description |
|---|---|
| Customers | Customer information, segments and order statistics |
| Orders | Order details, revenue, payment and delivery status |
| Order Items | Product-level order quantities and prices |
| Products | Product, category, brand and pricing information |
| Inventory New | Stock received and damaged stock |
| Delivery Performance | Delivery time, distance and delay information |
| Customer Feedback | Ratings, feedback categories and sentiment |
| Marketing Performance | Campaign impressions, clicks, conversions, spend, revenue and ROAS |

---

## 🔗 Data Relationships

The datasets were connected using common business keys:

- Customers → Orders using `customer_id`
- Orders → Order Items using `order_id`
- Products → Order Items using `product_id`
- Orders → Delivery Performance using `order_id`
- Orders → Customer Feedback using `order_id`
- Products → Inventory New using `product_id`

These relationships allow related business data to be analyzed together through PivotTables and dashboard components.

---

## 📈 Dashboard Analysis

The dashboard includes analysis such as:

### Sales & Revenue
- Monthly Revenue Trend
- Payment Method Revenue
- Order Performance

### Product Analytics
- Category Average Price
- Product Quantity Analysis
- Product Damage Analysis

### Delivery Analytics
- Delivery Status Analysis
- Average Delivery Time

### Customer Analytics
- Customer Segment Order Analysis
- Customer Rating Analysis
- Area-wise Order Analysis

### Marketing Analytics
- Marketing Revenue by Channel
- Marketing ROAS by Channel

---

## 📊 Key Dashboard Components

The dashboard contains:

- KPI / Business Summary Cards
- Interactive Slicers
- PivotTable-based Charts
- Revenue Analysis
- Order Analysis
- Customer Analysis
- Product Analysis
- Delivery Analysis
- Marketing Analysis

---

## 🛠️ Tools & Technologies

- Microsoft Excel
- Power Query
- PivotTables
- PivotCharts
- Excel Data Model
- Slicers
- Data Cleaning & Transformation
- Business Analytics
- Data Visualization

---

## 🔄 Project Workflow

```text
Raw CSV Datasets
       ↓
Data Import
       ↓
Data Cleaning & Transformation
       ↓
Data Relationships
       ↓
PivotTables
       ↓
PivotCharts
       ↓
KPI / Business Summary
       ↓
Interactive Dashboard

📁 Project Structure

Blinkit-Business-Analytics/
│
├── README.md
│
├── Blinkit Business Analytics & Dashboard.xlsx
│
├── datasets/
│   ├── blinkit_customers.csv
│   ├── blinkit_orders.csv
│   ├── blinkit_order_items.csv
│   ├── blinkit_products.csv
│   ├── blinkit_inventoryNew.csv
│   ├── blinkit_delivery_performance.csv
│   ├── blinkit_customer_feedback.csv
│   └── blinkit_marketing_performance.csv
│
└── screenshots/
    └── dashboard.png

💡 Business Insights

The project helps analyze:
- Revenue trends over time
- Customer ordering patterns
- High-volume products
- Product category pricing
- Delivery delays and performance
- Customer satisfaction
- Product damage trends
- Marketing channel revenue
- Marketing return on ad spend
- Regional order distribution

🚀 How to Use

1. Download the Excel workbook.
2. Open Blinkit Business Analytics & Dashboard.xlsx.
3. Navigate to the Blinkit Analytics Dashboard sheet.
4. Use the available slicers to filter the analysis.
5. Explore the PivotTables sheet for detailed calculations and supporting analysis.

👨‍💻 Author

Thariq Arsath J
B.Sc. Artificial Intelligence & Machine Learning

Skills Demonstrated:

Excel Power Query PivotTables Data Analysis Data Visualization Business Analytics Dashboard Development

⭐ Project Highlights

- 8 interconnected business datasets
- Multiple business-domain analyses
- Relational data modeling
- Interactive Excel dashboard
- PivotTable & PivotChart analysis
- Customer, product, delivery and marketing analytics
- End-to-end business analytics workflow
📌 Project Type
Business Analytics | Data Analysis | Excel Dashboard 
