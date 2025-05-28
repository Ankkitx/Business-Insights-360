# AtliQ Business Insights 360

# ➡️ Live Dashboard: https://shorturl.at/sD595
## 📊 Project Overview

**AtliQ Hardware**, a fast-growing company specializing in computers and accessories, is expanding globally through **retailers**, **direct sales**, and **distributors**.

Despite rapid growth, the company faced **unexpected losses** after opening a store in America. Initial analysis using **surveys**, **intuition**, and **basic Excel** revealed the issue, but lacked the depth needed to compete with rivals who use advanced analytics.

To stay competitive and make **data-driven decisions**, AtliQ Hardware decided to implement **Power BI** dashboards to provide valuable insights into **finance**, **sales**, **marketing**, and **supply chain** operations.

---

## 📁 Datasets

The datasets were sourced from two different databases and categorized as:

### `gdb041`
- `dim_customer`: Customer information
- `dim_market`: Market region details
- `dim_product`: Product catalog
- `fact_forecast_monthly`: Forecasted quantities to anticipate customer needs and reduce warehouse costs
- `fact_sales_monthly`: Actual sales data with quantities sold

### `gdb056`
- `freight_cost`: Shipment cost details
- `gross_price`: Product pricing before deductions
- `manufacturing_cost`: Product production costs
- `pre_invoice_deductions`: Discounts applied before invoicing
- `post_invoice_deductions`: Discounts applied after invoicing

---

## 🔄 Importing Data & Data Modeling

Data was imported from **MySQL** into **Power BI**. After cleaning and transforming the data, a **Snowflake schema** was used for data modeling.

### Why is data modelling important?

A Data Analyst’s workflow generally includes:

✅ Data Extraction → ✅ Data Cleaning → ✅ Data Modeling → ✅ Data Analysis

Data modeling acts as the **foundation for analytics**—poor modeling can result in incorrect or slow reports. In this project, we adopted a **Snowflake Schema** to ensure optimized performance and accurate visualizations.

![Snowflake Schema](https://github.com/Ankkitx/Business-Insights-360/blob/main/snowflake%20schema.png?raw=true)


---

## 📊 Power BI Dashboard Overview

The dashboard includes **six pages**, each designed for specific business functions:

### 🏠 Home Page
A navigation hub to access other views.
[<!-- Screenshot of Home Page -->](https://github.com/Ankkitx/Business-Insights-360/blob/main/Info.png?raw=true)

### 💰 Finance View
Helps improve **financial planning**, **budgeting**, and **cost control**.
- Profit and Loss statements
- Top/Bottom Products & Customers by Net Sales
![Finance View](https://github.com/Ankkitx/Business-Insights-360/blob/main/Finance%20view.png?raw=true)


### 📈 Sales View
Aim to increase **sales revenue** and **market share**.
- Customer performance by Net Sales
- Gross Margin & Gross Margin %
![Sales View](https://github.com/Ankkitx/Business-Insights-360/blob/main/Sales%20view.png?raw=true)

### 📣 Marketing View
Focuses on **brand visibility** and **customer engagement**.
- Segment performance by Gross Margin % and Net Profit %
![Marketing View](https://github.com/Ankkitx/Business-Insights-360/blob/main/Marketing%20view.png?raw=true)

### 🚚 Supply Chain View
Optimizes **inventory management** and **supplier performance**.
- Forecast Accuracy, Net Error, and other logistics KPIs
![Supply Chain View](https://github.com/Ankkitx/Business-Insights-360/blob/main/Supply%20chain%20view.png?raw=true)


### 🧑‍💼 Executive View
Offers a **high-level summary** for top management.
- Net Sales, Gross Margin %, Net Profit
- Top 5 Customers & Products, Regional Performance
![Executive View](https://github.com/Ankkitx/Business-Insights-360/blob/main/Executive%20View.png?raw=true)


---

## 🧠 Skills Learned

During this project (via Codebasics Bootcamp), I gained hands-on experience in:

- Power BI fundamentals
- Data Cleaning & Modeling
- Creating DAX Measures and Calculated Columns
- Using Bookmarks and Conditional Formatting
- Custom Tooltips & Dynamic Titles
- Performance optimization with **DAX Studio**

---

## 🛠️ Tools & Technologies

- **SQL**
- **Power BI Desktop**
- **DAX Language**
- **DAX Studio**
- **Project Charter Documentation**

---

## 💼 Business Concepts/ Domain Knowledge

- Gross Margin / Gross Margin %
- Gross Sales / Gross Sales %
- Net Sales, Net Profit, COGS
- Pre- and Post-invoice deductions
- YTG (Year to Go), YTD (Year to Date)
- Sales Channels: Direct, Retailers, Distributors

---

## ✅ Conclusion

This project enabled AtliQ Hardware to **move from intuition to insight**, empowering leadership with **clear, actionable data** across departments. The dashboards help answer critical business questions, ultimately contributing to **greater profitability and smarter strategies**.
