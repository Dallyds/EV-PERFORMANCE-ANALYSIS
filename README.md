# ⚡ EV Performance Analysis — Power BI Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Dataset](https://img.shields.io/badge/Dataset-EV%20Data-brightgreen?style=for-the-badge)
![Dashboards](https://img.shields.io/badge/Dashboards-3-green?style=for-the-badge)

---

## 📌 Project Overview

This Power BI project provides a comprehensive analysis of Electric Vehicles (EVs) across multiple dimensions — performance, pricing, and sales insights. The dashboard is designed to help users explore EV trends by manufacturer, battery type, range, charging time, and more.

---

## 📂 Dataset — `ev_dataset`

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

## 🎨 Design Theme

- **Primary Color:** 🟢 Pleasing Green (`#6BBF4E`, `#4CAF50`, `#A8D5A2`)
- **Background:** Soft green gradient
- **Text:** White & Dark Green for contrast
- **Card Icons:** EV-relevant emoji/icons placed on each KPI card
- **Font:** Segoe UI / Calibri for clean readability

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

---

## 🚀 How to Use

1. **Clone this repository:**
   ```bash
   git clone https://github.com/yourusername/EV-Performance-Analysis-PowerBI.git
   ```

2. **Open the `.pbix` file** in Power BI Desktop.

3. **Connect the dataset** if prompted — point to `Dataset/ev_dataset.csv`.

4. **Explore the dashboards** using slicers for Manufacturer, Battery Type, Country, Year, and Model.

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
- 📧 [Your Email]
- 🔗 [Your LinkedIn]
- 🐙 [Your GitHub]

---

## 📃 License

This project is open-source and available under the [MIT License](LICENSE).

---

> ⚡ *Driving the future, one data point at a time.*
