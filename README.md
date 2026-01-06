# 🌍 Urban Sustainability Dashboard
**Power BI | Data Analytics | Urban Development**

---

## 📌 Project Overview
This repository contains an **Urban Sustainability Dashboard** developed in **Power BI** to assess and compare sustainability performance across cities using a **composite index methodology**.

Inspired by international development frameworks (e.g. UN-Habitat), the project integrates **social, economic, infrastructural, and environmental indicators** into a single analytical framework while preserving transparency and interpretability.

The dashboard is designed as a **decision-support tool** for policymakers, development agencies, NGOs, consultants, and researchers.

---

## 🎯 Project Objectives
- Assess urban sustainability in a **comparable and standardized way**
- Highlight **inequalities and disparities** across cities and regions
- Provide **actionable insights** for urban development and sustainability planning
- Demonstrate strong skills in **Power BI, data modeling, and data storytelling**

---

## 📊 Data Sources
All datasets used in this project are **publicly available** and aggregated from international sources.

### Included datasets:
- **City-level indicators (68 cities)**
  - Population
  - Socio-economic indicators (poverty, inequality, education, employment)
  - Infrastructure & services (water, shelter, transport, internet)
  - Environment & quality of life (PM10, CO₂, green spaces, renewable energy)

- **Country metadata**
  - Region
  - Income group

- **Urban population time series**
  - World Bank indicators (1960–2024)

> ⚠️ No confidential, proprietary, or sensitive data are used in this project.

---

## 🧮 Methodology

### 1. Data Cleaning & Preparation
- Harmonization of city and country identifiers
- Validation of indicator ranges and units
- Treatment of missing values:
  - Exclusion where critical
  - Neutral handling where appropriate
- Removal of duplicates and extreme outliers

---

### 2. Indicator Normalization
To ensure comparability across heterogeneous indicators, all variables were normalized using **min-max scaling**:
Normalized value = (Value − Min) / (Max − Min) × 100
Indicators with negative implications (e.g. pollution, poverty, mortality) were **direction-adjusted** so that higher values always represent better outcomes.

---

### 3. Thematic Indices
Indicators were grouped into four thematic dimensions:

#### Social Index
- Life expectancy
- Literacy rate
- Mean years of schooling
- Under-five mortality rate (inverted)

#### Economic Index
- Poverty rate (inverted)
- Gini coefficient (inverted)
- Youth unemployment (inverted)
- City product per capita

#### Infrastructure Index
- Access to improved water
- Improved shelter
- Internet access
- Access to public transport

#### Environmental Index
- PM10 concentration (inverted)
- CO₂ emissions (inverted)
- Renewable energy share
- Access to open public spaces

Each index is calculated as the **average of its normalized indicators**, using **equal weighting**.

---

### 4. Urban Sustainability Index (USI)
The **Urban Sustainability Index** is computed as: 
USI = Average(Social, Economic, Infrastructure, Environmental Indices)

Equal weighting across dimensions was chosen to:
- Ensure transparency
- Avoid subjective prioritization
- Align with international development best practices

---

## 📈 Dashboard Structure

### Page 1 — Overview
- Global city map
- Key performance indicators
- Top and bottom performing cities
- Filters by region, income group, and city

### Page 2 — Social & Economic Development
- Poverty, inequality, and education analysis
- Life expectancy vs poverty relationships
- Youth unemployment by region

### Page 3 — Urban Infrastructure & Services
- Access to essential services
- Transport and connectivity indicators
- Infrastructure performance comparison

### Page 4 — Environment & Quality of Life
- Air pollution and emissions
- Green and public space access
- Environmental sustainability patterns

### Page 5 — Methodology & Insights
- Explanation of index construction
- Sustainability breakdown by city
- Data limitations and interpretation guidance

---

## ⚠️ Data Limitations & Disclaimer
- Data availability varies across cities and indicators
- Some indicators may be aggregated or estimated
- Results should be interpreted as **comparative insights**, not absolute rankings

This dashboard is intended as an **analytical and exploratory tool**, not as a definitive performance assessment.

---

## 🛠️ Tools & Technologies
- **Power BI** (data modeling, DAX, visualization)
- **Excel / CSV** (data preprocessing)
- **GitHub** (version control & documentation)

---

## 👤 Author
**TARDY Emile**  
Data Analyst | Urban Analytics | Sustainability  

📍 Paris-based — Remote  
🔗 Portfolio available on Malt

---

## 📬 Contact
For questions, collaborations, or freelance opportunities, feel free to reach out via Malt or LinkedIn.
