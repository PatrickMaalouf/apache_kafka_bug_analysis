# Apache Kafka Bug Analysis Project

### 🎯 **Project Goal**

To analyze the bug-reporting trends and resolution performance of the Apache Kafka open-source project to provide actionable insights for its development team. This project demonstrates skills in data acquisition, cleaning, analysis, and professional reporting.

### 💡 **Key Findings**

* **Bug Volume Trends**: The number of bug reports has fluctuated significantly over time, with major spikes in mid-2016 and 2019, indicating potential correlations with major releases or project changes.
* **Component Instability**: The `streams`, `core`, and `connect` components have the highest number of bug reports, highlighting them as key areas for targeted development and testing efforts.
* **Resolution Efficiency**: While bugs in high-volume components are resolved relatively quickly, a small number of bugs in components like `log` and `producer` take an exceptionally long time to fix, suggesting they are complex or low-priority issues.

### 📈 **Dashboard & Visualization**

View the full interactive dashboard https://public.tableau.com/views/ApacheKafkaBugAnalysis/ApacheKafkaBugAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link.

### 🔧 **Methodology**

1.  **Data Acquisition**: Used Python with the JIRA REST API to collect over 8,500 public bug reports.
2.  **Data Cleaning**: Normalized the data by handling missing values and splitting multi-component tags into individual categories.
3.  **Analysis**: Performed descriptive analysis on bug trends, component distribution, and resolution times.
4.  **Reporting**: Created this summary and an in-depth report detailing actionable recommendations.

### 📂 **Repository Contents**

* `data/`: Contains the raw and cleaned CSV files.
* `notebooks/`: Contains the Jupyter notebooks used for data processing and analysis.
* `report/`: Contains the final project report in PDF format.
