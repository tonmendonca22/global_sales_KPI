# 📊 E-commerce Sales Analysis with SQL and Power BI

Welcome to my data exploration project where I dive into real-world e-commerce data using **SQL** and bring the insights to life with **Power BI** dashboards. This project aims to extract business intelligence from raw data, answer strategic questions, and support data-driven decision-making.

---

## 🔍 Project Objective

The goal of this project is to perform an **Exploratory Data Analysis (EDA)** using SQL on an e-commerce dataset, followed by creating **interactive dashboards in Power BI** to visualize key business insights.

I focused on answering the following business questions:

1. **Which shipping modes generate the most revenue?**
2. **Which markets have the highest average shipping costs?**
3. **Which product categories generate the highest average profit?**
4. **How has the profit margin evolved over time?**

---

## 🛠️ Tools & Technologies

* **PostgreSQL / DataWorld** – SQL queries for data exploration
* **Power BI** – Interactive dashboard and data visualization
* **GitHub** – Project versioning and documentation
* **CSV Files** – Raw data loaded into the SQL environment

---

## 🧾 Datasets

The following tables were used:

* `global_sales`: Sales transactions with sales value, shipping cost, and product/customer info
* `global_orders`: Order details with dates, priority, and shipping mode
* `global_products`: Product category and details
* `global_customers`: Customer profile, including region and market

---

## 📈 Key Insights

* **Standard Class** shipping mode generated the highest total sales, suggesting customer preference for cost-effective delivery.
* **APAC** and **US** markets showed higher average shipping costs, pointing to potential supply chain optimizations.
* **Technology** was the most profitable category on average, making it a key driver of business margin.
* **Profit margins** fluctuated throughout the year, likely influenced by promotions and operational costs.

These insights were transformed into a **dynamic Power BI dashboard** with filters, KPIs, and visual breakdowns by market, shipping mode, and time.

---

## 📊 Power BI Dashboard Preview

![Dashboard Screenshot](link-to-your-screenshot-or-gif)

> *(Replace with an image link or upload a screenshot in your repo)*

The dashboard includes:

* KPI panel: Total Revenue, Avg. Shipping Cost, Profit Margin
* Visuals for revenue by shipping mode, profit by category, and margin trend by month
* Slicers by market, region, and category for easy exploration

---

## 📁 Repository Structure

```
📦 e-commerce-sql-powerbi
├── data/
│   ├── global_sales.csv
│   ├── global_orders.csv
│   ├── global_products.csv
│   └── global_customers.csv
├── sql/
│   └── analysis_queries.sql
├── dashboard/
│   └── powerbi_dashboard.pbix
├── images/
│   └── dashboard_preview.png
├── README.md
```

---

## 🚀 How to Use

1. Clone the repository
2. Import the CSV files into a PostgreSQL database or DataWorld
3. Run the SQL queries from `sql/analysis_queries.sql`
4. Open the `.pbix` file in Power BI to explore the dashboard
5. Use filters to generate insights for specific segments or time periods

---

## 🧠 Learnings & Takeaways

* Practicing real-world SQL for analytical queries
* Structuring EDA to answer business-critical questions
* Building compelling dashboards with business storytelling
* Strengthening the connection between data and decisions

---

## 🙌 Let's Connect

If this project sparked your interest or helped you in any way, feel free to:

* ⭐ Star this repository
* 📝 Leave feedback or open an issue
* 🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/seu-perfil)

Let’s keep transforming data into meaningful action—one query and one dashboard at a time.
