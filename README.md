# 📊 SIES Benchmark Dashboard — Chilean Higher Education

## Description

Interactive dashboard built with Python, Jupyter and Voilà for analyzing and comparing higher education enrollment in Chile using official SIES data. The project is designed to support **institutional benchmarking** within the Chilean higher education industry, providing dynamic visualizations and exportable executive reports.

---

## 🎯 Objective

To provide a comparative analysis tool that enables higher education institutions to **understand their relative position in the market**, identify enrollment trends by field of study, region and institution, and support strategic decision-making based on public data.

---

## 📂 Data Source

**SIES — Servicio de Información de Educación Superior**
Ministry of Education, Government of Chile.

The dataset used corresponds to the **Enrollment 2007–2025** file, publicly available at [https://www.mifuturo.cl/bases-de-datos-de-matricula/](https://www.mifuturo.cl/bases-de-datos-de-matricula/). It contains enrollment data disaggregated by institution, program, region, modality, schedule and academic level, covering the entire Chilean higher education system.

---

## 📈 Charts and Objectives

### Chart 1 — Enrollment Trend by Generic Program Area
Displays the historical evolution (2007–2025) of total enrollment grouped by generic program area. Allows identification of growth or decline trends by field of knowledge over time, with filters for year, academic level, modality, institutional classification and knowledge area.

### Chart 2 — Enrollment by Region and Year
Visualizes the geographic distribution of enrollment by region and year, with the option to filter by a specific institution. Enables analysis of regional behavior across the system and comparison of an institution's market share in each region over time.

### Chart 3 — Institutional Positioning by Program Area
Compares enrollment volumes across multiple institutions by generic program area for a selected year. The first institution selected is visually highlighted, making it easier to assess competitive positioning against the broader system or specific competitors.

---

## 📄 Deliverables

Each chart includes an **executive PDF report export button**, containing:

- **Report G1 — Enrollment Trend:** applied filters summary, exported chart, top 10 programs with highest growth, top 10 with greatest decline, most stable programs, distribution by knowledge area and automated executive summary.

- **Report G2 — Enrollment by Region:** filters summary, exported chart, year-over-year growth percentage by region, distribution by academic level and modality, and executive summary.

- **Report G3 — Institutional Comparison:** filters summary, enrollment comparison table by program and institution, market share by program area, top 5 most and least demanded programs per institution, and executive summary.

---

## 🛠️ Technologies

- Python 3
- Jupyter Notebook 6.5.7
- Voilà
- Plotly
- ipywidgets
- Pandas / NumPy
- FPDF2

---

## 🖼️ Dashboard Screenshots

Preview images of the generated charts are available in the repository as PNG files. These screenshots show real outputs produced by the dashboard using SIES enrollment data.

---

## 🌐 Dashboard Mockup

You can view the dashboard interface mockup at:
👉 [https://diegoevans2-arch.github.io/Dashboard-Benchmark-SIES/Dashboard_Benchmark_SIES.html](https://diegoevans2-arch.github.io/Dashboard-Benchmark-SIES/Dashboard_Benchmark_SIES.html)

> *Note: this is a static mockup showing the dashboard layout and filters only. It does not include interactive charts, as these require an active Jupyter kernel to run. For chart previews, see the PNG screenshots available in this repository.*
