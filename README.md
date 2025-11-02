# 🌞 Analyzing Renewable Energy Production Logs ⚡  
*A Big Data Analytics Project using Hadoop & Hive on Cloudera VM*

---

## 📘 Project Overview
This project focuses on **analyzing renewable energy production logs** to extract insights about solar, wind, and hydro energy generation.  
Using **Hive** on the **Cloudera Quickstart VM**, the system processes CSV-based energy data stored in **HDFS** and performs analytical queries to compute total, average, and fault metrics.

---

## 🧩 Technologies Used
- **Hadoop HDFS** – Distributed storage for dataset  
- **Hive** – Data warehouse for analytical queries  
- **Cloudera Quickstart VM** – Local big data environment  
- **Linux (CentOS)** – OS running inside VirtualBox  
- **Hue (Port 8888)** – Web UI for running Hive queries  

---

## 🗂️ Dataset Information
**File:** `energy_logs.csv`  
**Sample Columns:**
| Column | Description |
|---------|--------------|
| timestamp | Time of data capture |
| plant_id | ID of renewable plant |
| source | Type of energy (solar/wind/hydro) |
| energy_kwh | Energy produced in kWh |
| temperature_c | Temperature in Celsius |
| wind_speed_mps | Wind speed (m/s) |
| status | Operational status (OK/FAULT) |


## 💡 Insights
```bash
Solar farms show consistent output but higher temperature variation.
Wind plants occasionally fail under high wind speeds.
Hydro plants produce steady energy with minimal variation.
```

🚀 How to Run via Hue
```bash
Start VM → Open browser → Go to http://localhost:8888
Login → Hue → Query Editors → Hive
Paste the queries above → Click Run
```

##  Project Directory Structure
```bash
renewable_project/
├── energy_logs.csv
├── README.md
└── hive_queries.sql
```
