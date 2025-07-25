# 🌍 Life Expectancy Analysis Dashboard | SQL + Power BI

An advanced data analytics project combining SQL and Power BI to uncover actionable health and economic insights from WHO’s Life Expectancy dataset (2000–2015), spanning 179 countries and 20+ indicators.

> 🎯 **Goal:** Identify key factors affecting life expectancy and visualize trends using a dynamic, interactive Power BI dashboard.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Tools Used](#tools-used)
- [Dashboard Highlights](#dashboard-highlights)
- [Insights & Recommendations](#insights--recommendations)
- [Getting Started](#getting-started)
- [Dataset Source](#dataset-source)
- [Contact](#contact)

---

## 📈 Project Overview

This project analyzes a rich dataset from the World Health Organization covering:

- **179 countries**
- **16 years** (2000–2015)
- **20+ health and economic variables** including:
  - GDP per capita
  - Immunization coverage (Polio, Hepatitis B, Diphtheria)
  - Mortality rates
  - Schooling
  - Alcohol consumption
  - HIV/AIDS
  - Health expenditure

The final Power BI dashboard enables stakeholders to **compare country performance**, **filter by year/status**, and **derive insights for global public health policy**.

---

## 🚀 Key Features

✅ Built fully interactive Power BI dashboard  
✅ Performed SQL-based preprocessing & cleansing  
✅ Hover-based dynamic tooltips with insights  
✅ Slicers for Year, Country, and Development Status  
✅ Comparative analysis across Developed vs Developing nations  
✅ Scatter plots, bar charts, KPI cards, and trend lines  

---

## 🛠 Tools Used

| Tool         | Purpose                        |
|--------------|--------------------------------|
| **SQL (MySQL)**     | Data cleaning, filtering, and querying |
| **Power BI**        | Dashboard development & visual analytics |
| **Excel**           | Initial exploration & data validation |
| **Git & GitHub**    | Version control & public portfolio |

---

## 📊 Dashboard Highlights

### 🔹 KPI Cards
- **Average Life Expectancy**
- **Global Average GDP per Capita**
- **Polio & Hepatitis B Immunization Averages**
- **Avg. Years of Schooling**

### 🔹 Visuals Included
- Life Expectancy vs GDP (Scatter Plot with Year animation)
- Immunization Rates by Country (Bar Chart)
- Mortality Rate vs Life Expectancy (Bubble Plot)
- Schooling & Alcohol vs Life Expectancy (Multi-axis visual)
- HIV/AIDS & Infant Mortality Trends
- Regional Comparisons (Developed vs Developing)

> ✅ Includes advanced tooltips & slicers for interactivity

---

## 📌 Insights & Recommendations

💡 **Key Insights:**
- Countries with higher **GDP and immunization rates** consistently show higher life expectancy.
- **Schooling years** positively correlate with healthcare awareness and outcomes.
- High **adult mortality and HIV/AIDS rates** drastically lower life expectancy, especially in developing nations.
- Public health expenditure has a visible impact on child mortality and vaccination rates.

📢 **Recommendations:**
- Boost investment in education and immunization in developing nations.
- Increase targeted HIV/AIDS interventions where mortality remains high.
- Track longitudinal impact of economic growth on life expectancy post-2015.

---

> 🔹 To view the dashboard:

1. Clone this repo  
2. Open `powerbi/life_expectancy_dashboard.pbix` in Power BI Desktop 
3. Import the Views into the Power BI directly or onto server (in my case localhost via phpmyadmin) and connect BI with the database.
3. Explore using slicers (Year, Country, Status) and hover over tooltips for insights  

---

## 📚 Dataset Source

- [WHO Life Expectancy Dataset (Kaggle)](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who)

---
