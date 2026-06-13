# 🍽️ Zomato Restaurant Analysis Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-FF4500?style=for-the-badge&logo=databricks&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

An interactive Power BI dashboard analyzing Zomato restaurant data across India, providing insights into restaurant ratings, cuisines, delivery options, pricing, and city-wise distribution.

---

## 📸 Dashboard Preview

![Zomato Dashboard](./Zomato%20Restaurant%20Dashboard%20Screenshoot.jpeg)

---

## 📌 Project Overview

This project explores the Zomato restaurant dataset to uncover trends and patterns in the Indian food delivery and dining industry. The dashboard enables users to filter data by country, city, and food style to gain actionable insights.

---

## 🎯 Key Features

- **KPI Cards** — At-a-glance metrics: Total Restaurants, Average Rating, Total Votes, and Average Cost for Two
- **Online Delivery Analysis** — Pie chart showing the percentage of restaurants offering online delivery
- **Table Booking Analysis** — Pie chart showing availability of table booking options
- **Top 5 Cuisines** — Horizontal bar chart ranked by total votes
- **City-wise Distribution** — Bar chart showing restaurant count per city
- **Interactive Filters** — Slicers for Country, City, and Style of Food Item
- **Price Range Gauge** — Visual indicator of average price range

---

## 📊 Dashboard Insights

| Metric | Value |
|---|---|
| Total Restaurants | 20 |
| Average Aggregate Rating | 4.1 / 5 |
| Total Votes | 29,697 |
| Avg Cost for Two | ₹1,445 |
| Online Delivery | 35% Yes |
| Table Booking | 45% Yes |

> *Values reflect filtered view: India → Mumbai*

---

## 🗂️ Dataset

**Source:** [Zomato Restaurants Dataset — Kaggle](https://www.kaggle.com/datasets/shrutimehta/zomato-restaurants-data)

**Key Columns Used:**

| Column | Description |
|---|---|
| `Restaurant Name` | Name of the restaurant |
| `City` | City where restaurant is located |
| `Cuisines` | Type of food served |
| `Aggregate Rating` | Average customer rating (0–5) |
| `Votes` | Total number of customer votes |
| `Average Cost for Two` | Estimated dining cost for two people |
| `Has Online Delivery` | Whether online delivery is available (Yes/No) |
| `Has Table Booking` | Whether table booking is available (Yes/No) |
| `Price Range` | Restaurant price tier (1–4) |
| `Country Code` | Numeric country identifier |

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Dashboard creation and visualization
- **Power Query** — Data cleaning and transformation
- **DAX (Data Analysis Expressions)** — Custom measures and KPIs
- **Microsoft Excel / CSV** — Raw data source

---

## ⚙️ DAX Measures Used

```dax
-- Average Rating
Avg Rating = AVERAGE('zomato'[Aggregate rating])

-- Average Cost for Two
Avg Cost = AVERAGE('zomato'[Average Cost for two])

-- Total Votes
Total Votes = SUM('zomato'[Votes])

-- Total Restaurants
Total Restaurants = COUNTROWS('zomato')
```

---

## 📁 Project Structure

```
📦 Zomato-Dashboard
 ┣ 📂 Zomato_Dataset              # Dataset folder
 ┣ 📝 README.md                   # Project documentation
 ┣ 📊 Zomato_Dashboard.pbix       # Power BI file
 ┗ 🖼️ dashboard_preview.jpeg      # Dashboard screenshot
```


---

## 🚀 How to Run

1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/zomato-dashboard.git
   ```

2. **Open Power BI Desktop**
   - Download from [Microsoft Power BI](https://powerbi.microsoft.com/)

3. **Open the `.pbix` file**
   - File → Open → `Zomato_Dashboard.pbix`

4. **Refresh Data** *(if needed)*
   - Home → Refresh

5. **Explore the Dashboard**
   - Use slicers on the left to filter by Country, City, or Food Style

---

## 📈 Key Findings

- **Pizza** is the most voted cuisine in Mumbai with 7.8K votes
- Only **35%** of restaurants offer online delivery, showing growth opportunity
- **New Delhi** has the highest restaurant concentration among all cities
- Average cost for two in Mumbai restaurants is approximately **₹1,445**
- Only **45%** of restaurants offer table booking, indicating a gap in premium dining services

---

## 🙋 About Me

**[Shravan Pandirkar]**
Aspiring Data Analyst | Power BI | SQL | Python | Excel

- 🔗 [LinkedIn](https://www.linkedin.com/in/shravan-pandirkar-4a9552321)
- 💻 [GitHub](https://github.com/Shravan-pandirkar)
- 📧 shravanpandirkar39@gmail.com

---


⭐ **If you found this project helpful, please give it a star!** ⭐