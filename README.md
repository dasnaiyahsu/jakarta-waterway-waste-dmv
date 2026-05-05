# 🌊 Jakarta Waterway Waste Analysis
### Data Mining & Visualization — SDG 12: Responsible Consumption and Production

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![SDG12](https://img.shields.io/badge/SDG%2012-Responsible%20Consumption-BF8B2E?style=for-the-badge)

**Analyzing daily waste volume across Jakarta's rivers and waterways using real government data — visualized to drive awareness on urban waste management.**

</div>

---

## 📌 Overview

Jakarta's rivers accumulate thousands of cubic meters of waste every single day — yet this data is rarely communicated in a way the public can understand. This project mines and visualizes real waste volume data from Jakarta's waterways to uncover patterns across districts, locations, and time periods.

This is a **Group Project** (3 members) for the **Data Mining and Visualization** course at Binus University, Semester 2. Aligned with **UN SDG 12: Responsible Consumption and Production**.

**My Role: Data Visualization & Infographic/Poster Design**

---

## 📊 Dataset

| Info | Detail |
|------|--------|
| Source | Jakarta Government Open Data |
| Raw Records | 30,256 rows |
| Coverage | 5 regions, 42 sub-districts |
| Time Period | Monthly daily waste records |
| Target Column | `volume_sampah_perhari (m³)` — Daily waste volume |

### Regions Covered
- 🏙️ Jakarta Pusat
- 🌆 Jakarta Utara
- 🌇 Jakarta Selatan
- 🌃 Jakarta Barat
- 🌉 Jakarta Timur

### Dataset Features
| Column | Description |
|--------|-------------|
| `bulan` | Month |
| `titik_lokasi` | River/waterway location name |
| `kecamatan` | Sub-district |
| `wilayah` | Region (5 areas of Jakarta) |
| `panjang/luas` | Length/area of waterway |
| `satuan_panjang/luas` | Unit (meter/m²) |
| `tanggal` | Date |
| `volume_sampah_perhari (m³)` | Daily waste volume in cubic meters |

---

## Process

### 1. Data Cleaning (Dirty → Clean Dataset)
- Removed duplicate entries
- Handled missing values
- Standardized column formats
- Fixed inconsistent location naming

### 2. Preprocessing
- Parsed date & month columns
- Filtered outliers in waste volume
- Grouped by region and time period
- Prepared aggregated summaries for visualization

### 3. Data Visualization
- Bar charts: waste volume per region
- Line charts: monthly waste trends
- Comparison: districts with highest waste load
- Heatmap-style breakdown by location

### 4. Infographic & Poster Design
- Created E-Poster summarizing key findings
- Designed for public communication and awareness
- Aligned with SDG 12 messaging

---

##  Project Structure

```
Group_6_Responsible_Consumption_And_Production/
│
├── Datasets kotor.csv              # Raw / dirty dataset
├── Datasets bersih.csv             # Cleaned dataset (30,256 rows)
├── Proses Pre-processing.html      # Preprocessing notebook (Python)
├── E-Poster (png).png              # Final infographic poster

```

---

##  Key Findings

- Waste volume varies significantly across Jakarta's 5 regions
- Certain sub-districts consistently show higher waste concentration
- Monthly trends reveal seasonal patterns in waste accumulation
- Data visualization makes patterns invisible in raw data immediately clear

---

## 🌍 SDG Alignment

This project directly supports **SDG Goal 12: Responsible Consumption and Production** by:
- Making waste data accessible and understandable to the public
- Identifying high-priority areas for waste management intervention
- Using data-driven insights to support sustainable city planning

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Python | Data processing & analysis |
| Pandas | Data cleaning & manipulation |
| Matplotlib / Seaborn | Data visualization & charts |
| Canva / Design tool | E-Poster & infographic design |
| Jupyter Notebook | Preprocessing pipeline |

---

## Team

**Group 6 — Data Mining and Visualization**
Binus University · Semester 2 · 2025

| Member | Role |
|--------|------|
| Cheryl Eugene Saari| Data Cleaning|
| Ernestine Danella Ong | Data Cleaning |
| Dasnaiya Hsu | Data Visualization & Poster Design |

---

<div align="center">
Made with 💚 for Data Mining & Visualization Course — Binus University 2025<br>
Supporting UN SDG 12: Responsible Consumption and Production
</div>
