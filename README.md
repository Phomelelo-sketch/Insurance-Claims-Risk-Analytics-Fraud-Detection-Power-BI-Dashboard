# Insurance-Claims-Risk-Analytics-Fraud-Detection-Power-BI-Dashboard

## Project Overview
This Business Intelligence project applies Power BI and data storytelling principles to an insurance industry use case. Acting as an Insurance Data Analyst, the core objective was to investigate three critical corporate challenges: escalating claim liabilities, distinct regional risk variations across South Africa, and financial exposure tied to fraudulent activities. 

By transforming a flat transactional dataset (`insurance_claims.csv`) into an interactive executive dashboard, this solution bridges the gap between raw data and strategic, data-driven underwriting modifications.

## Key Insights Uncovered
* **Primary Cost Driver:** **Gauteng** represents the highest-exposure territory in the entire portfolio, with total claim amounts surpassing **R2 million**.
* **Risk Profile & Distribution:** **Accident claims** constitute the most frequent operational hazard, making up **52.34%** of all total claims.
* **Financial Leakage (Fraud):** Claims flagged as fraudulent account for a staggering **R1.34 million** in losses. Crucially, the average cost of a fraudulent claim is **R35.32K**—significantly outpacing the portfolio baseline average of **R31.70K**, proving that fraudulent activities skew toward high-value exposures.
* **Seasonal Volatility:** A major time-series trend was identified in **June**, where overall portfolio costs spiked sharply to an all-time high of **R1.5 million**, trailing a brief contraction in May (~R1 million).
* **High-Risk Segments:** **Third-Party Policies** show severe volume peaks over time, **Theft claims** act as a major vector for fraud flags, and the **KwaZulu-Natal (KZN)** region exhibits a high density of fraudulent entries despite an otherwise downward trend in standard claims volume.

## Dashboard Architecture & Visual Elements
The dashboard layout is designed with strict data hierarchy and interactivity in mind, consisting of the following key visual layers:

1. **Executive KPI Cards:** Auto-calculating high-level benchmarks showing *Total Claims Count*, *Total Claim Amount*, and *Average Claim Amount*.
2. **Time-Series Analysis (Line Chart):** Captures seasonal fluctuations and specific monthly anomalies over time (such as the June surge).
3. **Geographical Performance (Bar Chart):** Cross-tabulates aggregated total claim costs mapped by South African regions to immediately isolate high-cost territories.
4. **Segmentation Profiling (Donut Chart):** Breaks down the structural volume distribution of distinct claim types (Accidents vs. Theft, etc.).
5. **Loss Mitigation (Fraud Analysis Chart):** Visualizes financial exposure directly attributed to fraudulent vs. legitimate flags to track revenue leakage.
6. **Dynamic Canvas Slicers:** Interactive multi-select filters for `Region` and `Claim Type`, enabling deep-dive regional auditing.

## Tech Stack & Data Engineering
* **Power BI Desktop:** Power Query for automated data ingestion, cleaning, and schema normalization.
* **DAX (Data Analysis Expressions):** Formulated custom relational measures and calculated metrics to evaluate portfolio baselines, including average cost parameters and advanced premium-to-claims financial ratios.
* **Data Storytelling Framework:** Styled using an actionable narrative structure built around the **Insight ➔ Reasoning ➔ Action** framework to ensure deliverables drive immediate corporate strategy.

## Project Visual Preview

*Below is a visual representation of the completed interactive dashboard layer:*

![Insurance Risk Dashboard](images/# Insurance Claims Risk Analytics & Fraud Detection (Power BI)

## Project Overview
This Business Intelligence project applies Power BI and data storytelling principles to an insurance industry use case. Acting as an Insurance Data Analyst, the core objective was to investigate three critical corporate challenges: escalating claim liabilities, distinct regional risk variations across South Africa, and financial exposure tied to fraudulent activities. 

By transforming a flat transactional dataset (`insurance_claims.csv`) into an interactive executive dashboard, this solution bridges the gap between raw data and strategic, data-driven underwriting modifications.

## Key Insights Uncovered
* **Primary Cost Driver:** **Gauteng** represents the highest-exposure territory in the entire portfolio, with total claim amounts surpassing **R2 million**.
* **Risk Profile & Distribution:** **Accident claims** constitute the most frequent operational hazard, making up **52.34%** of all total claims.
* **Financial Leakage (Fraud):** Claims flagged as fraudulent account for a staggering **R1.34 million** in losses. Crucially, the average cost of a fraudulent claim is **R35.32K**—significantly outpacing the portfolio baseline average of **R31.70K**, proving that fraudulent activities skew toward high-value exposures.
* **Seasonal Volatility:** A major time-series trend was identified in **June**, where overall portfolio costs spiked sharply to an all-time high of **R1.5 million**, trailing a brief contraction in May (~R1 million).
* **High-Risk Segments:** **Third-Party Policies** show severe volume peaks over time, **Theft claims** act as a major vector for fraud flags, and the **KwaZulu-Natal (KZN)** region exhibits a high density of fraudulent entries despite an otherwise downward trend in standard claims volume.

## Dashboard Architecture & Visual Elements
The dashboard layout is designed with strict data hierarchy and interactivity in mind, consisting of the following key visual layers:

1. **Executive KPI Cards:** Auto-calculating high-level benchmarks showing *Total Claims Count*, *Total Claim Amount*, and *Average Claim Amount*.
2. **Time-Series Analysis (Line Chart):** Captures seasonal fluctuations and specific monthly anomalies over time (such as the June surge).
3. **Geographical Performance (Bar Chart):** Cross-tabulates aggregated total claim costs mapped by South African regions to immediately isolate high-cost territories.
4. **Segmentation Profiling (Donut Chart):** Breaks down the structural volume distribution of distinct claim types (Accidents vs. Theft, etc.).
5. **Loss Mitigation (Fraud Analysis Chart):** Visualizes financial exposure directly attributed to fraudulent vs. legitimate flags to track revenue leakage.
6. **Dynamic Canvas Slicers:** Interactive multi-select filters for `Region` and `Claim Type`, enabling deep-dive regional auditing.

## Tech Stack & Data Engineering
* **Power BI Desktop:** Power Query for automated data ingestion, cleaning, and schema normalization.
* **DAX (Data Analysis Expressions):** Formulated custom relational measures and calculated metrics to evaluate portfolio baselines, including average cost parameters and advanced premium-to-claims financial ratios.
* **Data Storytelling Framework:** Styled using an actionable narrative structure built around the **Insight ➔ Reasoning ➔ Action** framework to ensure deliverables drive immediate corporate strategy.

## Project Visual Preview

*Below is a visual representation of the completed interactive dashboard layer:*
nsurance Claims Risk Analytics & Fraud Detection Power BI Dashboard.png


## Repository Deliverables
* `DFA_Assignment 4_Phomelelo.pbix`: The source Power BI dashboard workbook (downloadable for interactive testing).
* `images/`: Folder holding UI screenshots and design elements..png)
*(Note: To display your dashboard image, upload a high-quality screenshot of your Power BI canvas into your repository's "images" folder and ensure it is named exactly "insurance_dashboard_preview.png")*

## Repository Deliverables
* `DFA_Insurance-Claims-Risk-Analytics-Fraud-Detection.pbix`: The source Power BI dashboard workbook (downloadable for interactive testing).
* `images/`: Folder holding UI screenshots and design elements.
