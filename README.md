# ImprovadoExam-PowerBI
An executive-level dashboard featuring dynamic Half-over-Half (HoH) analysis, multi-scale KPI formatting, and automated performance tracking for multi-channel marketing campaigns.

Digital Marketing Performance Analytics Dashboard
Project Overview
This project features a high-level executive dashboard designed to track and analyze digital marketing performance across multiple channels (Amazon, Paid Search, Social, etc.). It focuses on identifying growth trends and efficiency shifts between semesters (H1 vs H2).

Key Features
Dynamic HoH Analysis: Custom DAX measures to compare Half-over-Half performance with automated trend indicators (↑/↓).

Smart Formatting: Implementation of dynamic scaling in labels (switching between Millions, Thousands, and Units) to maintain a clean UI regardless of data volume.

Advanced Visual Logic: Color-coded status indicators where "positive" isn't always green (e.g., an increase in CPC/CPM is automatically flagged as red).

Multi-Channel Granularity: Comparative analysis of Organic vs. Paid channels with interactive sparklines for trend visualization.

Tech Stack
Tool: Power BI Desktop

Data Modeling: Star schema approach with dedicated dim_date and fact_performance tables.

Metrics Tracked
Volume: Impressions, Video Views, Conversions.

Efficiency: CTR (Click-Through Rate), CVR (Conversion Rate).

Cost: Total Spend, CPC (Cost Per Click), CPM (Cost Per Mille).
