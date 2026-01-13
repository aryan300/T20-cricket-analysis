# 🏏 T20 Cricket Analysis

A data analytics project that extracts, transforms, and visualizes T20 cricket data to derive performance insights and select the optimal **Playing XI** using a data-driven approach.

This repository demonstrates end-to-end analytics — from **web scraping T20 match data** from ESPN Cricinfo, to **cleaning and shaping the data with Python and Pandas**, transforming it with **Power Query**, building analytical models with **DAX**, and finally **visualizing insights in Power BI Dashboards** to identify the best 11 players.

---

## 📌 Table of Contents

- 🔍 [Project Overview](#-project-overview)  
- 🚀 [Workflow](#-workflow)  
  - 📥 Data Collection  
  - 🧹 Data Cleaning & Transformation  
  - 📊 Data Modeling & DAX  
  - 📈 Dashboard Development    
- 📁 [Repository Structure](#-repository-structure)
- 🏆 Dashboard Highlights
- 🛠️ [Tech Stack](#️-tech-stack)  
- 🧪 [How to Run](#️-how-to-run)  
- 📊 [Key Deliverables](#-key-deliverables)  
- 📜 [License](#-license)

---

## 🔍 Project Overview

This project focuses on analyzing Twenty20 cricket match data to derive meaningful performance insights at both player and team levels. The end goal is to build an interactive dashboard in **Power BI** that supports cricket analysts/coaches in selecting the **best possible playing XI** — based on data metrics such as batting averages, strike rates, bowling performance, and specialist roles.

---

## 🚀 Workflow

### 📥 1. Data Collection

- Web scraping of T20 cricket data from the **ESPN Cricinfo** website.
- Scraped data includes match details, players’ batting & bowling stats, and team info. :contentReference[oaicite:1]{index=1}

✔️ Save raw JSON and CSV versions for reproducibility.

---

### 🧹 2. Data Cleaning & Transformation

- Use **Python (Pandas)** to parse JSON/HTML data and remove noise.
- Handle missing values, normalize player names, and create clean, enriched tables.
- Export clean datasets ready for Power BI ingestion.

---

### 🔁 3. Data Transformation in Power BI

- Load CSV data into **Power Query** for additional transformations:
  - Data type corrections
  - Merging related tables
  - Date, categorical, and numerical feature formatting

---

### 📊 4. Data Modeling & DAX

- Build data relationships and model logic inside Power BI.
- Create calculated columns, measures, and performance metrics using **Data Analysis Expressions (DAX)**.
- Define role-based filters (openers, middle order, finishers, all-rounders, specialist bowlers).

---

### 📈 5. Dashboard Development

- Design Power BI visualizations to present:
  - Top performers by batting/bowling metrics
  - Player comparisons
  - Role-based dashboards
  - Final 11 selection indicators

---

## 📁 Repository Structure

```text
T20-cricket-analysis/
├── t20_csv_files/              # Cleaned datasets
├── t20_json_files/             # Raw/Intermediate JSON from scraper
├── t20_data_preprocessing.ipynb# Python notebook (cleaning & ETL)
├── README.md                  # Project overview & docs
└── … (other assets, visuals, pbix)

```
---
## 📊 Dashboard Highlights

The Power BI dashboard enables:

- Player performance comparisons across multiple metrics  
- Role-based insights (openers, middle order, finishers, bowlers)  
- Interactive filtering by team, role, and performance indicators
- Include explanations for why each player makes the cut (e.g., strike rate, average, economy).  
- Visual and data-backed **Best Playing XI selection*

---

## 🛠️ Tech Stack

- **Python** – Pandas, BeautifulSoup  
- **Jupyter Notebook**  
- **Power BI Desktop**  
- **Power Query**  
- **DAX (Data Analysis Expressions)**  
- **Git & GitHub**

---

## ⚙️ How to Run the Project

### Prerequisites

- Python 3.x  
- Jupyter Notebook  
- Power BI Desktop  

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/aryan300/T20-cricket-analysis.git

2. Install required Python dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the data preprocessing notebook:
   ```bash
   t20_data_preprocessing.ipynb
   
4. Open t20_cricket_analysis.pbix in Power BI Desktop to explore insights.   

---

## 🤝 Contributing

Contributions are welcome! If you’d like to improve the analytics, add features, or fix issues:

1. Fork the repository
2. Create your feature branch: `git checkout -b my-feature`
3. Commit your changes: `git commit -m "Add feature"`
4. Push to branch: `git push origin my-feature`
5. Open a Pull Request

---

## 📜 License

This project is open-source and available under the **MIT License**.  

---

## 📫 Contact

Aryan Batra – *Project Owner*  
GitHub: [aryan300](https://github.com/aryan300)

---
