🏥 Healthcare Operations & Financial Performance Dashboard
Project Overview
This end-to-end data transformation project focuses on hospital efficiency and financial health. By processing raw healthcare records, I developed an interactive Power BI suite that enables hospital administrators to monitor patient flow, clinical outcomes, and revenue streams in real-time.
Data Pipeline
Data Cleaning (Excel): Performed extensive data wrangling, including handling null values, standardizing medical condition naming conventions, and creating date tables for time-series analysis.
Data Modeling (Power BI): Established a star schema to connect patient demographics, medical records, and billing data.
Visualization: Designed a 3-page interactive report focused on UX/UI best practices for executive decision-making.
Dashboard Breakdown
1. Hospital Operations
<img width="590" height="332" alt="Hospital operations" src="https://github.com/user-attachments/assets/da182a8c-b4b2-4b9f-924c-1e1aa97730bf" />

Focus: Patient volume and facility throughput.
Key Metrics: Total Patients (1,000), Revenue ($25.1M), and Emergency Admissions.
Insight: Identified a significant decline in patient volume and revenue starting in 2020, with a sharp drop-off through 2024, signaling a need for operational review.

2. Medical Insights
<img width="588" height="329" alt="medical insights" src="https://github.com/user-attachments/assets/5dd6b930-d480-499d-8ab7-bb2105c6e807" />

Focus: Clinical trends and patient demographics.
Key Metrics: Average Length of Stay (16 days), Severe/Critical case counts.
Insight: Analyzed treatment costs by condition, showing that Asthma and Hypertension are among the highest contributors to billing per patient.

3. Financial & Cost Analysis
<img width="588" height="334" alt="financial analysis" src="https://github.com/user-attachments/assets/dd98d272-6cec-4972-9fd0-b85c5092f02e" />

Focus: Revenue drivers and billing correlation.
Visuals: Scatter plot analyzing the correlation between Length of Stay and Billing Amount across different severity levels.
Insight: Breakdown of revenue by medication, identifying Metformin and Montelukast as top-performing pharmaceutical revenue drivers.

Technical Snippets
Power BI / DAX
I utilized custom DAX measures to calculate dynamic KPIs, such as:
Avg Billing per Patient: DIVIDE([Total Revenue], [Total Patients])
Severe Case Tracking: Filtered measures to isolate "Severe" and "Critical" patient counts for high-priority alerts.
Excel Cleaning Steps
Used Power Query to remove duplicates and fix inconsistent "Blood Type" formatting.
Applied conditional columns to categorize "Severity" based on medical diagnosis codes.

Key Skills Demonstrated
ETL: Extract, Transform, Load via Excel & Power BI.
DAX: Creating complex measures for financial reporting.
Data Storytelling: Translating 1,000+ rows of raw data into actionable insights.


ETL: Extract, Transform, Load via Excel & Power BI.
DAX: Creating complex measures for financial reporting.
Data Storytelling: Translating 1,000+ rows of raw data into actionable insights.
