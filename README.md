

# 🏷️ Adidas Interactive Sales Dashboard

## 📌 Project Overview

This project is an **interactive sales analytics dashboard** built using **Python, Streamlit, Pandas, and Plotly**. It analyzes Adidas retail sales data to uncover insights across **retailers, time, geography, and sales performance metrics**.

The dashboard is designed to support **data-driven decision making** by enabling users to:

* Explore sales trends over time
* Compare retailer and state-level performance
* Analyze units sold vs revenue
* Visualize regional sales distribution

This project demonstrates **end-to-end data analysis skills**, from data ingestion and transformation to interactive visualization and deployment — aligning closely with **Data Scientist / Analytics Engineer responsibilities**.

---

## 🎯 Objectives

* Transform raw Excel sales data into meaningful insights
* Build an interactive, business-friendly dashboard
* Enable stakeholders to download aggregated datasets
* Showcase data storytelling and visualization best practices

---

## 🧰 Tech Stack

| Category        | Tools                            |
| --------------- | -------------------------------- |
| Language        | Python                           |
| Data Processing | Pandas                           |
| Visualization   | Plotly (Express & Graph Objects) |
| App Framework   | Streamlit                        |
| Data Source     | Excel (`Adidas.xlsx`)            |
| Image Handling  | Pillow (PIL)                     |

---

## 📂 Project Structure

```bash
├── Adidas.xlsx                # Raw sales dataset
├── adidas-logo.jpg            # Branding image
├── app.py                     # Streamlit dashboard application
├── README.md                  # Project documentation
```

---

## 📊 Dataset Description

The dataset represents **Adidas retail sales transactions** across different regions, states, cities, and product categories.

### Key Columns

| Column          | Description                       |
| --------------- | --------------------------------- |
| Retailer        | Retail partner name               |
| RetailerID      | Unique retailer identifier        |
| InvoiceDate     | Transaction date                  |
| Region          | Sales region                      |
| State           | State of sale                     |
| City            | City of sale                      |
| Product         | Product category                  |
| PriceperUnit    | Unit price                        |
| UnitsSold       | Quantity sold                     |
| TotalSales      | Revenue generated                 |
| OperatingProfit | Profit earned                     |
| OperatingMargin | Profit margin                     |
| SalesMethod     | Sales channel (In-store / Outlet) |

---

## ⚙️ Features & Analytics

### 🔹 1. Retailer Sales Analysis

* Bar chart of **Total Sales by Retailer**
* Expandable data table with CSV export

### 🔹 2. Time Series Sales Trends

* Monthly aggregation using `InvoiceDate`
* Line chart showing **Total Sales Over Time**
* Enables trend detection and seasonality analysis

### 🔹 3. State-Level Performance

* Dual-axis chart:

  * **Bar:** Total Sales
  * **Line:** Units Sold
* Highlights revenue vs volume dynamics

### 🔹 4. Regional & City Sales Distribution

* Interactive **Treemap** visualization
* Drill-down from Region → City
* Sales values formatted in millions for readability

### 🔹 5. Data Transparency

* Expandable views for:

  * Aggregated datasets
  * Raw transaction data
* One-click CSV downloads for further analysis

---

## 🖥️ Dashboard Preview (Conceptual)

* Wide-layout responsive UI
* Brand-aligned header with Adidas logo
* Clean visual hierarchy
* Business-focused metrics

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/adidas-sales-dashboard.git
cd adidas-sales-dashboard
```

### 2️⃣ Install Dependencies

```bash
pip install streamlit pandas plotly pillow openpyxl
```

### 3️⃣ Run the App

```bash
streamlit run app.py
```

---

## 🧠 Data Science Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Time-series aggregation
* KPI calculation and comparison
* Data visualization & storytelling
* Dashboard development
* Data export & reproducibility
* Business-oriented insight delivery

---

## 📈 Potential Enhancements

* Add filters (Region, Product, Sales Method)
* Profit & margin trend analysis
* Forecasting using time-series models
* Deployment on Streamlit Cloud
* Integration with SQL or cloud data sources

---

## 👤 Author

**Amanuel Birri**
Data & Analytics Engineer | Data Scientist
🔗 [LinkedIn](https://www.linkedin.com/in/amanuel-birri)
💻 [GitHub](https://github.com/AmanuelKBr)

---

## 📄 License

This project is for **educational and portfolio purposes**. Dataset used for analysis demonstration only.

