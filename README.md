<b>🤸 Gymnastic Performance & Club Analytics Power BI Dashboard</b>

<b>📌 Project Overview</b>

This Power BI dashboard was developed to help Gymnastic Federations, Training Academies, and Clubs track and analyze athlete performance, training effectiveness, and competition outcomes. The project integrates Excel-based datasets and utilizes AI-generated visuals for posture and form analysis. It is built using optimized data modeling with **star and snowflake schema** to ensure scalability and high-performance reporting.

---

<b>📂 Data Sources</b>

- <b>Format:</b> Microsoft Excel (multiple structured sheets)  
- <b>Data Tables:</b>  
  - 🧍 Athlete Master  
  - 🏫 Club Details  
  - 🏋️‍♀️ Training Logs  
  - 🏆 Competition Scores  
  - 📅 Calendar Table  
  - 🤖 AI Visual Feedback (Posture, Flexibility, Form Accuracy)  

---

<b>🧩 Data Modeling</b>

- Utilized **Star Schema** for core reporting metrics (Athlete Fact table linked to dimension tables like Club, Date, and Performance Type).  
- **Snowflake Schema** implemented in cases like hierarchical Club structure (State > City > Club).  
- Relationship design optimized with **one-to-many (1:*), many-to-one (*:1)** cardinality.  
- **Calendar Table** connected to date fields across all tables to support dynamic time intelligence (YTD, MTD, Daily).  
- Measures and KPIs calculated using **DAX** and optimized with summarization logic, variable declarations, and time intelligence functions.  

---

<b>📈 Key KPIs & Metrics</b>

- 🧠 AI-Based Posture & Form Score  
- 🧍 Athlete Skill Progress (Monthly/Quarterly)  
- 🏆 Competition Average Scores & Win Rate  
- 🏫 Club Retention Ratio and Athlete Turnover  
- ⏱️ Training Consistency and Load Distribution  
- 🕵️ Dropout and Injury Incidence Rate  
- 🎯 Training Target vs Achievement  
- 📆 YTD, MTD, MoM Trends for Training and Scores  
- 📉 Performance Deviation and Top Performers  

---

<b>📊 Visuals Created</b>

- 📊 Clustered Bar & Column Charts – Performance by Club, Event, Gender  
- 📈 Line Charts – Athlete Skill Growth Over Time  
- 📦 Treemaps – Club-wise Contribution to Total Medals  
- 🧠 AI Comparison Panels – Before vs After Form Correction  
- 🔍 Heatmaps – Posture Accuracy and Flexibility Score  
- 🗺️ Geo Charts – Club Distribution by Region/State  
- 📅 KPI Cards – Weekly Hours, Win Rate, Dropouts, Skill Index  
- 🎛️ Slicers – Club, Event Type, Gender, Age Group, Date Range  
- 🔁 Drill-Through Reports – Athlete-Level and Club-Level Details  

---

<b>🛠️ Tools & Technologies Used</b>

- Power BI Desktop – Dashboard development  
- Power Query – Data transformation and table normalization  
- DAX – KPI logic, dynamic calculations, and time intelligence  
- Excel – Primary structured data source (training logs, scores, AI feedback)  
- Calendar Table – Custom-built for managing dynamic date filters and trends  

---

<b>🖼️ Dashboard Previews</b>

<b>🏠 Home Dashboard</b>  
<img src="https://github.com/someshsn/Gymnastic-Pro/blob/main/Home.png" width="800" />

<b>📊 Analytics Dashboard</b>  
<img src="https://github.com/someshsn/Gymnastic-Pro/blob/main/Dashboard.png" width="800" />

<b>🏋️‍♀️ Club Performance Dashboard</b>  
<img src="https://github.com/someshsn/Gymnastic-Pro/blob/main/Clube%20Dashboards.png" width="800" />

<b>🤖 AI Visual Analysis</b>  
<img src="https://github.com/someshsn/Gymnastic-Pro/blob/main/AI%20Visuals.png" width="800" />

---

<b>🎯 Achievements & Benefits</b>

- Enabled real-time performance tracking across 100+ athletes  
- Improved form correction using visual AI scoring  
- Identified at-risk athletes through training load trends  
- Supported data-driven coaching strategies and medal forecasting  
- Reduced dropout rate by visualizing training imbalances and improvement zones  

---
