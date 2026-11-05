# San Diego Crime Trends & Spatial Hotspot Analysis (2022–2025)
**Applied Data Science & Statistical Analysis Project**

---

## Executive Summary
This project delivers an end-to-end empirical evaluation of municipal crime patterns across San Diego from 2022 through 2025 using 319,838 primary incident records from the San Diego Police Department (SDPD). Through exploratory data analysis, time-shift segmentation, spatial Pareto concentration modeling, and formal statistical hypothesis testing, this study identifies actionable trends across crime categories, neighborhood hotspots, and temporal convergence windows to inform data-driven public safety resource allocation.

---

## Core Findings & Key Deliverables
* **Volume Trajectory:** Analyzed 319,838 total incidents across 4 years (2022–2025), identifying key macro inflection points across municipal shifts.
* **Spatial Concentration:** Proven Pareto principle ($p < 0.05$)—the top 10% of neighborhoods account for **38.4% of all reported citywide crime**, led by East Village (5.9% total share).
* **Emerging Offense Shifts:** Shoplifting experienced a massive **+257.5% YoY surge**, representing the fastest-growing crime category.
* **Temporal Convergence:** Peak incident activity converges during the **Afternoon Shift (12:00 PM – 5:59 PM)**, with Friday afternoon recording the highest single density block.
* **Statistical Rigor:** All 5 formal hypothesis tests ($\chi^2$ test of independence, Kruskal-Wallis non-parametric seasonality test) confirmed statistically significant variations ($p < 0.05$).
* **Executive Summary Dashboard:** Built a consolidated 6-panel interactive Plotly dashboard for rapid executive decision-making.

---

## Data Source & Reproducibility
* **Primary Source:** Official **[City of San Diego Open Data Portal – Police NIBRS Offenses](https://data.sandiego.gov/datasets/police-nibrs/)**
* **Public Data Repository:** Due to GitHub repository size limits, raw datasets are maintained in a public Google Drive folder and auto-streamed into the notebook upon execution: **[Access Raw SDPD CSV Datasets (Google Drive)](https://drive.google.com/drive/folders/14b64u14ys9cvJ7HaKwFZUvVTApmRrROD?usp=sharing)**
> **Note on Plotly Visualizations:** GitHub's default web previewer disables interactive JavaScript rendering. To view all interactive charts and the Executive Dashboard, open the notebook directly in **[Google Colab](https://colab.research.google.com/drive/1VimIsin95ml-7U5Ea4UPJYQty90zLqel#scrollTo=62GpIlj1or3i)** or clone the repository locally.

---

## Project Structure
```text
├── San_Diego_Crime_Analysis.ipynb   # Main Notebook (Data Cleaning, EDA, Stats, Dashboard)
├── RESEARCH_BRIEF.md                # Applied Empirical Research Paper & Policy Recommendations
├── requirements.txt                 # Python dependencies for environment reproduction
└── README.md                        # Project documentation and key executive findings
```
