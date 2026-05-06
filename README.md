# 📊 LATAM Energy Dashboard – Growth & Energy Pressure

---

## 📷 Dashboard Preview

![Dashboard](LATAM_energy_dashboard_preview.png)

---

## 🧭 Overview

This project analyzes the relationship between economic growth and energy consumption across Latin American countries between 1980 and 2022.

The dashboard explores how energy demand evolves alongside economic expansion, highlighting differences in scale, efficiency, and structural dynamics across the region.

---

## 🎯 Objective

To evaluate how economic growth impacts energy consumption patterns in LATAM, identifying differences in energy intensity, development paths, and structural efficiency between countries.

---

## 📊 Key Insights

- **Brazil dominates in scale**, leading both in total GDP and total energy consumption.
- **Chile shows the highest energy consumption per capita**, suggesting higher energy intensity relative to its economic size.
- **Argentina presents moderate levels with higher volatility**, indicating sensitivity to macroeconomic cycles.
- **Peru and Colombia exhibit lower and more stable consumption patterns**, consistent with different development structures.
- The region shows **heterogeneous trajectories**, reflecting differences in industrial composition, economic stability, and energy efficiency.

---

## 📈 Dashboard Structure

### 1. Energy Consumption Over Time
- Line chart showing energy consumption per capita evolution.
- Highlights long-term trends and divergence across countries.

### 2. GDP vs Energy Consumption
- Scatter plot illustrating the relationship between economic size and energy use.
- Animated over time to show structural evolution.

### 3. KPI Snapshot (2022)
- Highest energy consumption per capita → Chile  
- Highest total energy consumption → Brazil  
- Highest GDP → Brazil  

---

## 🧠 Analytical Approach

- Data filtered for selected LATAM countries
- Time range adjusted to **1980–2022** to ensure data consistency
- Focus on **per capita vs total metrics** to avoid misleading comparisons
- Use of DAX measures to manage aggregation and context
- Validation of data quality and removal of unreliable variables (e.g., emissions due to missing data)

> Each observation represents a **country-year combination**, ensuring consistent granularity for analysis.

---

## 🛠 Tools & Technologies

- Power BI (data modeling & visualization)
- DAX (measures and context control)
- Excel (initial data exploration)
- Dataset: Our World in Data – Energy Dataset  
  https://github.com/owid/energy-data

---

## ⚠️ Data Considerations

- Missing values in GDP and energy efficiency metrics for recent years (2023–2024)
- Adjustments made to avoid distortions in KPIs
- Units standardized across all visuals (MWh per capita, TWh total, USD billions)

---

## 📌 Conclusion

Energy consumption in LATAM is strongly linked to economic activity but follows **non-uniform patterns** across countries.

The analysis suggests that:
- Growth alone does not determine energy demand
- Structural factors (industry mix, efficiency, stability) play a key role
- The region exhibits **divergent development paths in energy usage**

---

# 🏭 Dashboard 02 — Industrial Efficiency & Energy Intensity

---

## 📷 Dashboard Preview

![Dashboard 02](LATAM_industrial_efficiency_dashboard_preview.png)

---

## 🧭 Overview

This second dashboard expands the analysis by focusing on the relationship between industrial production and energy consumption across Latin America between 1990 and 2022.

Instead of analyzing growth alone, this dashboard explores how efficiently countries transform energy into industrial output, highlighting structural differences in industrial intensity, productivity, and energy dependence.

---

## 🎯 Objective

To evaluate whether higher industrial production in LATAM is associated with proportional increases in energy consumption, and to identify countries with relatively higher or lower industrial energy efficiency.

---

## 📊 Key Insights

- **Brazil dominates both industrial output and total energy consumption**, confirming its role as the largest industrial economy in the region. However, its scale also implies significantly higher structural energy pressure.

- **Chile and Bolivia exhibit higher energy intensity**, meaning they consume comparatively more energy per unit of industrial production. This may reflect differences in industrial structure, energy matrix composition, or efficiency levels.

- **Argentina and Uruguay show comparatively better relative efficiency**, maintaining industrial activity with lower energy intensity growth over time.

- **Peru demonstrates gradual efficiency improvements**, with energy intensity remaining more stable despite increases in industrial production.

- **Colombia and Brazil display stronger coupling between industrial growth and energy demand**, suggesting that industrial expansion still relies heavily on increased energy consumption rather than efficiency gains.

- The region overall presents **heterogeneous industrial development paths**, where economic expansion does not necessarily translate into equivalent energy efficiency improvements.

---

## 📈 Dashboard Structure

### 1. Total Energy Consumption (1990–2022)
- Line chart comparing total energy consumption evolution by country.
- Highlights scale differences and long-term growth trajectories.

### 2. Industrial Production Over Time
- Visualization of industrial output evolution using constant USD values.
- Allows comparison between industrial expansion and energy demand.

### 3. Industrial Output Ranking (2022)
- Horizontal ranking chart comparing industrial production levels across countries.

### 4. Industrial Production vs Energy Consumption
- Animated scatter plot relating industrial production and total energy consumption.
- Bubble size represents GDP scale.
- Designed to identify structural divergence and energy dependence patterns.

### 5. Energy Intensity Trend
- Measures energy consumed per unit of industrial production over time.
- Used to evaluate relative industrial efficiency dynamics.

---

## 🧠 Analytical Interpretation

The dashboard suggests that industrial growth in LATAM remains strongly associated with energy demand, although the degree of dependency differs substantially across countries.

Some economies appear to improve industrial productivity without proportional increases in energy consumption, while others maintain more energy-intensive growth patterns.

These differences may be associated with:
- industrial composition,
- technological adoption,
- energy infrastructure,
- macroeconomic stability,
- and long-term investment capacity.

---

## 📁 Repository Files

- `LATAM_energy_dashboard.pbix` → Dashboard focused on GDP growth and energy consumption
- `LATAM_industrial_efficiency_dashboard.pbix` → Dashboard focused on industrial production and energy intensity
- `LATAM_energy_dashboard_preview.png` → Preview image for Dashboard 01
- `LATAM_industrial_efficiency_dashboard_preview.png` → Preview image for Dashboard 02

---

## 📌 Project Conclusion

Together, both dashboards provide a broader view of how economic and industrial development interact with energy consumption across Latin America.

The analysis highlights that:
- Economic growth and industrial expansion do not affect energy demand uniformly
- Structural efficiency differs significantly between countries
- Some economies appear more capable of decoupling industrial growth from energy intensity
- Long-term development patterns are influenced by industrial composition, infrastructure, and energy efficiency dynamics

This project combines data modeling, analytical interpretation, and visual storytelling to explore regional energy and industrial trends through an interactive business intelligence approach.

---

## 👤 Author

Laura Agostina Spena  
Data Analyst | Power BI | SQL | Data Storytelling
