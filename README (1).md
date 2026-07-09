# 🏥 Hospital Patient Analysis – Power BI Dashboard

## Project Overview
An interactive Power BI dashboard analyzing hospital patient data to uncover insights on readmission rates, patient demographics, encounter patterns, and payer coverage. Built to support data-driven decision-making in healthcare operations.

---

## 📊 Dashboard Highlights

| Metric | Description |
|--------|-------------|
| **Total Patients** | Count of unique patients in the dataset |
| **Readmission Rate** | Percentage of patients readmitted after discharge |
| **Average Encounter Duration** | Average time spent per hospital visit |
| **Gender Distribution** | Percentage breakdown of male vs female patients |

---

## 📈 Visuals Included

- **KPI Cards** – Readmission rate, total patients, gender distribution %, average encounter
- **Line & Column Combo Chart** – Yearly encounter count and duration trends by age category
- **Donut Charts** – Gender distribution and marital status breakdown
- **Table** – Encounter class, patient ID, average encounter, and payer coverage
- **Slicers** – Filter by Gender and County

---

## 🔍 Key Insights

- Identified readmission patterns across different encounter classes
- Analyzed encounter duration trends over multiple years
- Compared payer coverage across patient segments
- Broke down patient demographics by gender, age category, and marital status

---

## 🛠️ Tools Used

- **Power BI Desktop** – Dashboard design and data visualization
- **DAX** – Custom measures (Readmission Rate, Age Category, Total Patients, Encounter Duration)
- **Data Modeling** – Relationships between `patient` and `encounters` tables

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `HOSPITAL_ANALYSIS.pbix` | Power BI dashboard file (open with Power BI Desktop) |
| `dashboard_screenshot.png` | Preview of the dashboard |
| `sample_data.csv` | Sample dataset structure used in the analysis |

---

## 🚀 How to Open

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Download `HOSPITAL_ANALYSIS.pbix` from this repository
3. Open the file in Power BI Desktop
4. Explore the dashboard using the Gender and County slicers

---

## 👤 Author

**Jeolin Sibi S**  
Aspiring Data Analyst | SQL • Power BI • Python • Excel  
📧 jeolinsibi@gmail.com

---

## 📄 Related Publication

Sibi, J. (2026). *Business Intelligence-Driven Analysis of Hospital Encounter Patterns and 30-Day Readmission Using Power BI: A Case Study on Synthetic Patient Data.* Zenodo. https://doi.org/10.5281/zenodo.21273022

This paper builds on the dashboard in this repository, applying the full underlying dataset (974 patients, 27,891 encounters) to analyze encounter class distribution, payer coverage, and a derived 30-day hospital readmission rate.
