# Healthcare-Infrastructure-Analysis-Dashboard

This project is an end-to-end data informatics pipeline designed to monitor pandemic trends across **Pakistan, China, Iran, and Afghanistan**. By bridging raw data engineering in Python with interactive visualization in Power BI, this tool provides actionable insights into regional healthcare stress.

![Final Dashboard Overview](<img width="1312" height="745" alt="image" src="https://github.com/user-attachments/assets/68be7a37-7cde-428e-bea8-27c913fe7615" />
)

## 🛠️ Technical Workflow
1. **Data Engineering (Python):** - Processed **400,000+ rows** of global health data.
   - Implemented a **7-Day Rolling Average** to remove weekend reporting noise.
   - Engineered features for **Case Fatality Rate (CFR)** and **Vaccination Coverage**.
2. **Business Intelligence (Power BI):** - Created a "Situation Room" dashboard with dynamic regional filters.
   - Built a **Healthcare Infrastructure Gauge** compared against the WHO benchmark (3.0 beds per 1,000)

     
## 💡 Key Insights
* **Infrastructure Analysis:** Regional hospital capacity remains significantly below global benchmarks, impacting surge response capabilities.
* **Epidemiological Waves:** Smoothed curves reveal the true velocity of infection spikes, providing a clearer picture than raw daily reporting.
