# ⚡ EV Performance Analysis — By CLAUDE

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Dataset](https://img.shields.io/badge/Dataset-EV%20Data-brightgreen?style=for-the-badge)
![Dashboards](https://img.shields.io/badge/Dashboards-3-green?style=for-the-badge)

---

## 📌 Project Overview

This Power BI project provides a comprehensive analysis of Electric Vehicles (EVs) across multiple dimensions — performance, pricing, and sales insights. The dashboard is designed to help users explore EV trends by manufacturer, battery type, range, charging time, and more.

---

## 📂 Dataset — `ev_dataset`
Dataset link:
    https://www.kaggle.com/datasets/pratyushpuri/ev-electrical-vehicles-dataset-3k-records-2025?resource=download

### 📋 Columns

| Column | Type | Description |
|---|---|---|
| Vehicle_ID | Numeric | Unique identifier for each EV |
| Manufacturer | Text | EV manufacturer name |
| Model | Text | EV model name |
| Year | Numeric | Manufacturing year (2015–2025) |
| Battery_Type | Text | Type of battery used |
| Battery_Capacity_kWh | Numeric | Battery capacity in kWh |
| Charging_Type | Text | Type of charging supported |
| Charge_Time_hr | Numeric | Time to charge (hours) |
| Range_km | Numeric | Driving range in kilometers |
| Price_USD | Numeric | Vehicle price in USD |
| CO2_Emissions_g_per_km | Numeric | CO2 emissions per km |
| Units_Sold_2024 | Numeric | Units sold in 2024 |
| Safety_Rating | Numeric | Safety rating score |
| Warranty_Years | Numeric | Warranty period in years |
| Autonomous_Level | Numeric | Level of vehicle autonomy |
| Color | Text | Vehicle color |
| Country_of_Manufacture | Text | Country where EV is manufactured |

### 📐 Measures

| Measure | Description |
|---|---|
| Average_charging_time | Average charge time across filtered vehicles |
| Average_EV_price | Average price of EVs |
| Average_range_KM | Average driving range in km |
| Total sales | Total sales revenue |
| Total_manufacturer | Total number of manufacturers |
| total_units_sold | Total units sold |
| total_vehicles | Total number of EV models |

---

## 📊 Dashboards

### 1. ⚡ EV Performance Analysis
> Explore performance metrics by manufacturer and battery type.
<img width="906" height="670" alt="image" src="https://github.com/user-attachments/assets/8b27a5a7-db24-4330-8472-150c14f5c1f4" />

**Visuals Included:**
- 🔘 Manufacturer Slicer (button style)
- 🔘 Battery Type Slicer (button style)
- 📊 Bar Chart — Sum of Range_km by Model & Manufacturer
- 🔢 KPI Card — Average KM Range
- 🔢 KPI Card — Average Charging Time
- 🔵 Scatter Plot — EV Range vs Price Analysis
- 📊 Bar Chart — AVG Driving Range by Battery Type
- 📊 Bar Chart — AVG Charging Time by Charging Type

---

### 2. 💰 EV Pricing Analysis
> Deep-dive into EV pricing by manufacturer, model, battery type, and country.
<img width="907" height="602" alt="image" src="https://github.com/user-attachments/assets/58c61df7-2b8f-4997-ad5e-07bc3350544f" />
**Visuals Included:**
- 🔘 Manufacturer Slicer (tile style)
- 🔢 KPI Card — Battery Capacity
- 🔢 KPI Card — Total Vehicles
- 🔢 KPI Card — Total Units Sold
- 🔢 KPI Card — Charge Time
- 🔢 KPI Card — Warranty Years
- 🔢 KPI Card — Range-KM
- 🔢 KPI Card — Safety Rating
- 🖼️ EV Image Visual
- 📝 Color, Country, Battery Type, Price display

---

### 3. 📈 Sales Insights
> Understand sales trends across countries, models, and manufacturers.
<img width="911" height="743" alt="image" src="https://github.com/user-attachments/assets/96653036-3e4e-44cb-ac4b-4c51d530a5f3" />
**Visuals Included:**
- 🔘 Model Slicer
- 🔘 Country of Manufacture Slicer
- 🔘 Year Slicer (2015–2025)
- 🗺️ Map Visual — Sales by Country
- 📊 Bar Chart — Top 5 Manufacturers by Sales
- 📊 Bar Chart — Top 10 Models by Units Sold
- 📊 Bar Chart — Top EV Manufacturers by Sales (2024)
- 🔢 KPI Card — Total EV Models
- 🔢 KPI Card — Total Units Sold (2024)
- 🔢 KPI Card — Average Vehicle Price
- 🔢 KPI Card — Total Manufacturers

---
## 🗂️ File Structure

```
📁 EV-Performance-Analysis-PowerBI/
│
├── 📄 README.md
├── 📊 EV_Performance_Analysis.pbix
├── 📁 Dataset/
│   └── ev_dataset.csv
└── 📁 Screenshots/
    ├── dashboard1_performance.png
    ├── dashboard2_pricing.png
    └── dashboard3_sales.png
```
## 🚀 How to Use

1. **Open the `.pbix` file** in Power BI Desktop.

2. **Connect the dataset** if prompted — point to `Dataset/ev_dataset.csv`.

3. **Explore the dashboards** using slicers for Manufacturer, Battery Type, Country, Year, and Model.

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Power BI Desktop | Dashboard creation |
| DAX | Calculated measures |
| Power Query | Data transformation |
| Bing Maps | Geographic visualizations |

---

## 👩‍💻 Author

**Dally DS**


