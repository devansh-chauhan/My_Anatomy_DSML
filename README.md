# My_Anatomy_DSML
# COVID-19 India Data Analysis & Visualization

This repository contains data science and machine learning exploratory workflows for analyzing the COVID-19 situation across Indian States and Union Territories. The analysis leverages dataset automation with KaggleHub, data cleaning using Pandas, and visual analytics via Seaborn and Matplotlib.

##  Features & Highlights

- **Automated Dataset Download**: Programmatically fetches the latest `covid19-in-india` dataset directly using `kagglehub`.
- **Data Cleaning & Preprocessing**:
  - Null value detection and duplicate checks.
  - Conversion of date fields into datetime objects.
  - Feature engineering to derive active case counts (`Active = Confirmed - (Deaths + Recovered)`).
- **State-Level Aggregations**:
  - Grouping cumulative metrics by State/Union Territory.
  - Computing statistical metrics such as **Recovery Rate (%)** and **Death Rate (%)**.
- **Data Visualizations**:
  - Horizontal bar charts displaying Top 10 States/UTs by confirmed COVID-19 cases.
  - Recovery rate comparisons across states.
  - Time-series line plot tracking overall daily confirmed cases over time.

---

##  Requirements & Installation

Make sure you have Python 3.x installed along with the following libraries:

```bash
pip install pandas matplotlib seaborn kagglehub
