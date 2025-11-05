# Ahmad Rizal Bayhaqi — Data Analyst & Visualization Specialist

Welcome to my portfolio!  
Here you’ll find a curated selection of data projects, dashboards, and analyses demonstrating my experience in data analytics, automation, and visualization.

---

## Table of Contents

<details open>
<summary>Projects</summary>

1. [Finance Monitoring & Control Dashboard – PT Wira Cipta Perkasa (2025)](#finance-monitoring--control-dashboard--pt-wira-cipta-perkasa-2025)  
2. [Balance Sheet and Profit-Loss Dashboard – PT Wira Cipta Perkasa (2025)](#balance-sheet-and-profit-loss-dashboard--pt-wira-cipta-perkasa-2025)  
3. [PLS-SEM Model Simulator – Synthetic SEM Generator (2025)](#pls-sem-model-simulator--synthetic-sem-generator-2025)  
4. [Multimodal Deep Learning for Hoax Detection – Final Project (2024)](#multimodal-deep-learning-for-hoax-detection--final-project-2024)
5. [Integrated Web Scraping and Data Analysis Pipeline – Tokopedia & TurnBackHoax.id (2023)](#integrated-web-scraping-and-data-analysis-pipeline--tokopedia--turnbackhoaxid-2023)
7. [Rock–Paper–Scissors Image Classification – Dicoding (2022)](#rockpaperscissors-image-classification--dicoding-2022)  
8. [Coming Soon Projects](#coming-soon-projects)

</details>
---

## Finance Monitoring & Control Dashboard – PT Wira Cipta Perkasa (2025)

Created comprehensive finance dashboards (AR/AP/CF/Budget) to automate performance monitoring for the FAT department.  
Automated summary generation and streamlined weekly review.

[![View Dashboard](https://img.shields.io/badge/View-Dashboard-blue)](https://github.com/rizalarb/Finance-Monitoring-Control-Dashboard)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/rizalarb/Finance-Monitoring-Control-Dashboard/master/CF_SUMMARY.png" width="260"/><br><sub>Cash Flow Summary</sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/rizalarb/Finance-Monitoring-Control-Dashboard/master/CASH%20IN.png" width="260"/><br><sub>Cash In Dashboard</sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/rizalarb/Finance-Monitoring-Control-Dashboard/master/CASH-OUT.png" width="260"/><br><sub>Cash Out Dashboard</sub></td>
</tr>
</table>

**Role / Tools:** Automation & Reporting Analyst — `Excel`  
**Impact:** Simplified cross-department financial monitoring; improved visibility and accuracy.

<details open>
<summary>Read more</summary>

- Integrated AR, AP, TAX, and Budget datasets.  
- Implemented automated aggregation.  
- Designed layout for daily-to-monthly variance visualization.

</details>

[Back to Top](#ahmad-rizal-bayhaqi--data-analyst--visualization-specialist)

---

## Balance Sheet and Profit-Loss Dashboard – PT Wira Cipta Perkasa (2025)

Created an **Excel-based dashboard** to automate Balance Sheet and Profit & Loss reporting, aggregate COA, and surface five bank-aligned financial ratios for monthly monitoring.

[![View Dashboard](https://img.shields.io/badge/View-Dashboard-blue)](https://github.com/rizalarb/Balance-Sheet-and-Profit-Loss-Dashboard)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/rizalarb/Balance-Sheet-and-Profit-Loss-Dashboard/master/Balance.png" width="260"/><br><sub>Balance Sheet (COA aggregation)</sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/rizalarb/Balance-Sheet-and-Profit-Loss-Dashboard/master/Profit%20And%20Loss.png" width="260"/><br><sub>Profit & Loss (period comparatives)</sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/rizalarb/Balance-Sheet-and-Profit-Loss-Dashboard/master/Ratio%20And%20EBITDA.png" width="260"/><br><sub>Ratio Dashboard (EBITDA & key ratios)</sub></td>
</tr>
</table>

**Role / Tools:** Automation & Reporting Analyst — `Excel`, `Power Query`  
**Impact:** Simplified reporting and monitoring; improved visibility of financial position and key ratios.

<details>
<summary>Read more</summary>

- Automates ETL of GL exports and sub-ledgers via Power Query.  
- Maps and normalizes COA for multi-level aggregation (GL → subgroup → report line).  
- Produces monthly/YTD Balance Sheet, P&L, and five bank-aligned ratios (performance, solvency, liquidity, profitability, efficiency).  
- Includes validation checks, reconciliation rows, and a short user guide for handover.  
- Workbook (raw .xlsx) available for download in the repository.

</details>

[Back to Top](#ahmad-rizal-bayhaqi--data-analyst--visualization-specialist)


---

## PLS-SEM (Partial Least Squares Structural Equation Modeling) – Synthetic SEM Generator (2025)

Developed a **dynamic PLS-SEM model simulator** for automating the generation, visualization, and validation of structural equation models — designed to support **researchers and analysts** in testing causal relationships through **controlled parameter experiments**.

[![View Repository](https://img.shields.io/badge/View-Project-blue)](https://github.com/rizalarb/PLS-SEM-Model-Simulator)

<table>
<tr>
<td align="center"><img src="https://github.com/rizalarb/PLS-SEM-Model-Simulator-Customizable-Inner-and-Outer-Model-with-Synthetic-Data-Visualization/blob/master/Ilustration.jpg" width="260"/><br><sub>Model Overview & Simulation Workflow</sub></td>
<td align="center"><img src="https://github.com/rizalarb/PLS-SEM-Model-Simulator-Customizable-Inner-and-Outer-Model-with-Synthetic-Data-Visualization/blob/master/Inner%20Model%20Auto-Diagram.png" width="260"/><br><sub>Inner Model Path Coefficients (β)</sub></td>
<td align="center"><img src="https://github.com/rizalarb/PLS-SEM-Model-Simulator-Customizable-Inner-and-Outer-Model-with-Synthetic-Data-Visualization/blob/master/Heatmap.png" width="260"/><br><sub>Correlation Heatmap (Descriptive Analysis)</sub></td>
</tr>
</table>

**Highlights:**
- Designed a **Colab-based system** to generate **synthetic SEM data** with full parameter control (constructs, noise, and Likert scaling).  
- Implemented **automated computation of outer model validity** (Outer Loadings, AVE, Reliability, HTMT, Fornell-Larcker).  
- Developed **inner model testing** using regression-based path coefficients and **bootstrapping t-value analysis**.  
- Enabled **dynamic PlantUML diagram generation** for both measurement and structural models.  
- Integrated **visual descriptive analytics**, including **correlation heatmaps** and **construct summary statistics**.  
- Supported **experimental manipulation** of data relationships to observe model robustness and sensitivity.  

**Tools:** `Python`, `Pandas`, `NumPy`, `Scikit-learn`, `Matplotlib`, `Seaborn`, `PlantUML`, `Google Colab`

[Back to Top](#ahmad-rizal-bayhaqi--data-analyst--visualization-specialist)

---
## Multimodal Deep Learning for Hoax Detection – Final Project (2024)

Developed a **deep learning system** to automatically detect **hoax news** by combining text and image data, supporting **Mafindo’s (Indonesian Anti-Slander Society)** anti-disinformation initiative.

[![View Repository](https://img.shields.io/badge/View-Project-blue)](https://github.com/rizalarb/Application-Multimodel-Deep-Learning-Detecting-Hoax-News-Turnbackhoax.id-CNN)

<img src="https://github.com/rizalarb/Application-Multimodel-Deep-Learning-Detecting-Hoax-News-Turnbackhoax.id-CNN/blob/master/Cover%20PA%20English.jpg" width="30%"> 
<img src="https://github.com/rizalarb/Application-Multimodel-Deep-Learning-Detecting-Hoax-News-Turnbackhoax.id-CNN/blob/master/Model%20Architecture.jpg" width="30%"> 
<img src="https://github.com/rizalarb/Application-Multimodel-Deep-Learning-Detecting-Hoax-News-Turnbackhoax.id-CNN/blob/master/Result%20Visualization.jpg" width="30%">

**Highlights:**
- Built a **multimodal CNN** combining text-based (1D) and image-based (2D) architectures.  
- Processed **text with Word2Vec** and **images with CNN feature extraction**.  
- Trained on the **Turnbackhoax.id dataset** (3,103 train / 775 test samples).  
- Achieved **99.35% accuracy** and **99.81% AUC**, outperforming unimodal baselines.  
- Provided a scalable solution for **AI-assisted hoax verification** to improve public information trust.

**Tools:** `Python`, `TensorFlow`, `scikit-learn`, `Pandas`, `Matplotlib`

[Back to Top](#ahmad-rizal-bayhaqi--data-analyst--visualization-specialist)

---
## Integrated Web Scraping and Data Analysis Pipeline – Tokopedia & TurnBackHoax.id (2023)

Developed an automated **dual-source web scraping and data integration pipeline** combining **GraphQL API extraction** (Tokopedia) and **pseudo REST API HTML parsing** (TurnBackHoax.id).  
The unified dataset supports **text mining, misinformation detection (NLP)**, and **e-commerce trend analysis**.

[![View Repository](https://img.shields.io/badge/View-Project-blue)](https://github.com/rizalarb/Integrated-Web-Scraping-and-Data-Analysis-Pipeline-Tokopedia-TurnBackHoax.id-2023)

<table>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/rizalarb/Dual-Source-WebScraping-FactCheck-Builder/main/assets/tokopedia-dashboard.png" width="260"/><br><sub><b>Tokopedia Product Data</b><br>Automated product collection via GraphQL API</sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/rizalarb/Dual-Source-WebScraping-FactCheck-Builder/main/assets/turnbackhoax-scraper.png" width="260"/><br><sub><b>TurnBackHoax Dataset</b><br>Structured text extraction via pseudo REST scraping</sub></td>
<td align="center"><img src="https://raw.githubusercontent.com/rizalarb/Dual-Source-WebScraping-FactCheck-Builder/main/assets/eda-insights.png" width="260"/><br><sub><b>Exploratory Data Insights</b><br>Trends, topics, and correlation overview</sub></td>
</tr>
</table>


### 🔍 Highlights

- **GraphQL API Integration (Tokopedia)**  
  Built a dynamic scraper that sends GraphQL payloads to Tokopedia’s `https://gql.tokopedia.com/graphql/SearchProductQueryV4`.  
  Extracted detailed product attributes such as **name, price, rating, shop, and city** through a single GraphQL endpoint.

- **Pseudo REST API Scraping (TurnBackHoax.id)**  
  Implemented an **HTML parser using BeautifulSoup** to simulate REST-style HTTP GET requests,  
  extracting structured data fields — **title, date, category, and fact-check results** — from TurnBackHoax.id articles.

- **Data Integration**  
  Unified both sources into a structured **Pandas DataFrame**, enabling direct use for **NLP preprocessing**, **EDA**, or **BI dashboards**.

- **Automated Export & Visualization**  
  Implemented an automated `.xlsx` export pipeline for live storage and used **Matplotlib** to visualize price clustering and misinformation trends.

### 🧠 Tools & Technologies
`Python`, `Requests`, `BeautifulSoup`, `Pandas`, `JSON`, `LXML`, `GraphQL`, `Excel`, `Matplotlib`


[Back to Top](#ahmad-rizal-bayhaqi--data-analyst--visualization-specialist)

---
## Rock–Paper–Scissors Image Classification – Dicoding (2022)

Developed a **Convolutional Neural Network (CNN)** to automatically classify hand gestures (rock, paper, scissors) from image input — part of **Dicoding’s Machine Learning for Beginners** program, focusing on **computer vision fundamentals** and reproducible model testing in the cloud.

[![View Repository](https://img.shields.io/badge/View-Project-blue)](https://github.com/rizalarb/Rock-Paper-Scissors-Image-Classification)

<table>
<tr>
<td align="center"><img src="https://github.com/rizalarb/Rock-Paper-Scissors-Image-Classification/blob/master/CNN%20Layers.png" width="260"/><br><sub>CNN Layer Architecture (feature extraction)</sub></td>
<td align="center"><img src="https://github.com/rizalarb/Rock-Paper-Scissors-Image-Classification/blob/master/Training%20Model%20Output.png" width="260"/><br><sub>Training Process & Validation Metrics</sub></td>
<td align="center"><img src="https://github.com/rizalarb/Rock-Paper-Scissors-Image-Classification/blob/master/Output%20Prediction%20Tes.png" width="260"/><br><sub>Prediction Example (real-time test)</sub></td>
</tr>
</table>

**Highlights:**
- Implemented a **multi-layer CNN (5 convolutional blocks)** optimized for the RPS dataset.  
- Applied **image augmentation** to improve generalization and robustness.  
- Trained and evaluated in **Google Colab**, achieving **~95% validation accuracy** within 12 epochs.  
- Added a simple **real-time inference flow** for user-uploaded images to demonstrate practical use.  
- Clean, reproducible Colab notebook with end-to-end pipeline: data download → augmentation → training → prediction.

**Tools:** `Python`, `TensorFlow / Keras`, `NumPy`, `Matplotlib`, `Google Colab`

[Back to Top](#ahmad-rizal-bayhaqi--data-analyst--visualization-specialist)

---

## Coming Soon Projects

- Data Pipeline Automation using `Airflow` & `PostgreSQL`  
- Power BI Dashboard for SME Business Insights  
- Interactive Data Storytelling Portfolio Website  

[Back to Top](#ahmad-rizal-bayhaqi--data-analyst--visualization-specialist)

---

## Technical Skills

**Languages & Libraries:** Python, R, Pandas, NumPy, scikit-learn, TensorFlow, Keras  
**Databases & Query:** SQL (MySQL / PostgreSQL / T-SQL), ETL, Data Warehousing Concepts  
**Dashboard & Reporting:** Tableau, Excel (Pivot Table, VBA), Dashboarding  
**Statistics & Tools:** Hypothesis Testing, A/B Testing, Time Series, Econometrics, SPSS, Minitab  
**Dev & Productivity:** Jupyter, Git, Basic Docker  

**Soft Skills:** Attention to Detail, Problem Solving, Teamwork, Documentation, Communication  

**Keywords for ATS:** Data Analyst, Data Scientist, SQL, Python, Power BI, Dashboard, ETL, Machine Learning, TensorFlow, VBA, Financial Reporting, Forecasting, Data Visualization, KPI

[Back to Top](#ahmad-rizal-bayhaqi--data-analyst--visualization-specialist)

---

## Interests

Data Engineering · Automation · Visualization · Digital Product Design · Financial Monitoring  

[Back to Top](#ahmad-rizal-bayhaqi--data-analyst--visualization-specialist)
