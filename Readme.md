# 🏠 Airbnb Analysis Dashboard

> An interactive Power BI dashboard exploring Airbnb listings, pricing, room types, neighbourhoods, hosts, reviews, and geographic patterns.

<p align="center">

  <img src="AIRBNB 01.PNG" width="900">

</p>

---

## 📊 Dashboard Overview

This project analyzes Airbnb listing data using **Power BI** to understand:

- 🏘️ Popular neighbourhoods and listing distribution
- 💰 Pricing patterns across locations and room types
- 🏠 Room-type distribution
- 👤 Host activity and review engagement
- ⭐ Relationship between price and reviews
- 🌎 Geographic distribution of listings
- 📍 Neighbourhood and city-level patterns

The dashboard is designed with interactive filters and multiple analytical views to make exploration easier.

---

## 🚀 Dashboard Pages

| Page | Focus |
|------|-------|
| 🏠 **Overview** | Overall Airbnb market snapshot |
| 💰 **Price Analysis** | Pricing by room type, neighbourhood and city |
| 👤 **Host Analysis** | Hosts, reviews and room-type distribution |
| 🏘️ **Property Analysis** | Property and room-type patterns |
| 💡 **Problems & Insights** | Key findings from the analysis |

---

## 📌 Key Metrics

| Metric | Value |
|--------|------:|
| 👤 Total Hosts | **226K** |
| 🏠 Total Listings | **4M** |
| ⭐ Total Reviews | **8M** |
| 💰 Average Price | **219.72** |

---

## 🔍 Key Insights

### 🏘️ Listing & Neighbourhood Insights

- **Unknown** is the largest neighbourhood-group category in the dataset, with approximately **116K listings**.
- **Manhattan** and **Brooklyn** follow with approximately **20K** and **18K listings** respectively.
- The dashboard shows a strong concentration of listings across major neighbourhood groups and cities.

### 🏠 Property & Room-Type Insights

- **Entire home/apartment** represents approximately **68.21%** of listings.
- **Private rooms** account for approximately **29.15%**.
- **Shared rooms** represent approximately **1.78%** of listings.
- **Hotel rooms** make up the remaining small share.
- Entire homes/apartments dominate the listing mix across the dashboard.

### 💰 Pricing Insights

- The overall average listing price shown in the dashboard is **219.72**.
- **Hotel rooms** show the highest average price among the room types displayed.
- The dashboard shows substantial price variation across neighbourhood groups and room types.
- Price and review analysis shows that many listings with lower prices receive higher review counts, while very high-priced listings generally appear less frequently among highly reviewed properties.

### 👤 Host Insights

- **Michael** has the highest number of reviews among the top hosts shown, followed by **David** and **John**.
- The top 10 hosts visualization highlights a significant difference in review volume between the leading hosts and the remaining hosts.
- Manhattan and Brooklyn account for a substantial share of the distinct host distribution shown in the dashboard.

---

## 📈 Visual Analysis

### 🏠 Overview Dashboard

<p align="center">
  <img src="AIRBNB 02.PNG" width="900">
</p>

**Includes:**

- Total Hosts
- Total Listings
- Total Reviews
- Average Price
- Popular Neighbourhoods
- Listings by City
- Room-Type Distribution
- Listings by Room Type & Neighbourhood Group

---

### 💰 Price Analysis Dashboard

<p align="center">
  <img src="AIRBNB 02.PNG" width="900">
</p>

**Includes:**

- Average Price by Neighbourhood Group & Room Type
- Average Price by Room Type
- Price vs Number of Reviews
- Sum of Price by City
- Interactive Neighbourhood Group filtering

---

### 👤 Host Analysis Dashboard

<p align="center">
  <img src="AIRBNB 03.PNG" width="900">
</p>

**Includes:**

- Top 10 Hosts by Number of Reviews
- Host Distribution by Room Type
- Average Price vs Number of Reviews
- Host Distribution by Room Type

---

### 🏘️ Property Analysis Dashboard

<p align="center">
  <img src="AIRBNB 04.PNG" width="900">
</p>

**Includes:**

- Room-Type Share
- Room-Type Distribution Across Neighbourhood Groups
- Interactive property analysis

---

### 💡 Problems & Insights

<p align="center">
  <img src="INSIGHTS%20.png" width="900">
</p>

This page summarizes the major findings obtained from the dashboard analysis.

---

## 🎛️ Interactive Features

The dashboard allows users to explore the dataset dynamically through:

- 🔘 Room-Type filters
- 📍 Neighbourhood Group filters
- 🗺️ Geographic visualizations
- 📊 Cross-filtering between charts
- 🔎 Interactive Power BI visuals
- 📈 Comparative price and review analysis

Select a category in one visual to dynamically explore related information across the dashboard.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI** | Dashboard development & visualization |
| **Power Query** | Data cleaning & transformation |
| **DAX** | Measures & calculations |
| **Excel / CSV** | Dataset |
| **Microsoft Bing Maps** | Geographic visualization |

---

## 📂 Project Structure

```text
Airbnb-Analysis-Dashboard/
│
├── 📊 Airbnb-Analysis-Dashboard.pbix
├── 📁 Dataset/
│   └── airbnb.csv
│
├── 🖼️ Dashboard/
│   ├── AIRBNB 01.PNG
│   ├── AIRBNB 02.PNG
│   ├── AIRBNB 03.PNG
│   ├── AIRBNB 04.PNG
│   └── INSIGHTS.png
│
└── 📄 README.md