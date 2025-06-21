# Tuberculosis-Visual-Analytics
A collection of interactive D3.js visualizations analyzing global tuberculosis (TB) trends by region, year, gender, and economic impact.

## 📊 Project Overview

This project transforms complex TB health data into intuitive, interactive dashboards and charts that allow users to explore insights through maps, timelines, and hierarchical breakdowns. Each visualization is designed to support analysis for researchers, public health officials, and policy-makers.

---

## 🔍 Visualizations Included

| Visualization | Description |
|---------------|-------------|
| **🌍 Map Dashboard** (`tb-map-dashboard.html`) | Displays TB cases per 100k by country with color-coded economic impact and hospital data. Includes year selector and search by country code. |
| **📈 Scatter Plot** (`tb-scatter-plot.html`) | Compares TB total incidence over time with detection rates and HIV-positive subsets. |
| **👥 Bar Chart** (`tb-age-gender-bar-chart.html`) | Grouped bar chart showing TB cases by male age groups over the years. |
| **🌈 Sunburst Chart** (`tb-region-gender-sunburst.html`) | Multi-level sunburst chart: Region → Country → Year → Gender (Male/Female) cases. |
| **🔘 Animated Bubble Timeline** (`tb-region-bubble-timeline.html`) | Animated bubble chart visualizing region-wise TB cases year-by-year. |
| **🧭 Dashboard Shell** (`tb-dashboard-shell.html`) | A responsive dashboard interface linking all visualizations using iframes and a sidebar menu. |
| **🧬 Force-Directed Graph** (`tb-force-directed-graph.html`) | A network-style visualization that highlights relationships between countries, shared characteristics (e.g., similar case trends or detection rates), and clusters based on TB patterns. |

## 🛠️ Technologies Used

- [D3.js v6 & v7](https://d3js.org/)
- [Leaflet.js](https://leafletjs.com/) – for interactive map visualizations
- HTML, CSS, JavaScript
- Basic CSV data handling

---

## 🧪 Sample Dataset

The dataset (`data.csv`) contains:
- Country & region codes
- Year-wise TB metrics (e.g., total_cases, total_population)
- Demographic breakdowns (age, gender)
- Economic impact indicators
