# Traffic Enforcement & Revenue Overview

**Author:** Amirtha Ganesh R  
**Tool:** Microsoft Power BI  
**Data Period:** January 2015 - February 2026  
**Total Records:** 4,061 daily observations

---

##  Project Overview

This Power BI dashboard provides a comprehensive analysis of traffic enforcement (E-Challan) data spanning over 11 years. The project analyzes challan issuance, disposal rates, revenue collection, pending amounts, and court case processing to identify trends, bottlenecks, and system efficiency.


<img width="734" height="459" alt="image" src="https://github.com/user-attachments/assets/b823adab-9c87-4833-9809-1349455fa234" />

### Key Metrics Analyzed
- **417M** Total Challans Issued
- **159M** Disposed Challans
- **257M** Pending Challans
- **₹636bn** Total Revenue Generated
- **₹406bn** Pending Revenue

---

## Business Questions Answered

### Executive Overview (Page 1)
- What is the overall enforcement performance?
- Is disposal keeping up with challan issuance?
- What is the total revenue generated vs collected?

### Trend Analysis (Page 2)
- Are challans increasing over time?
- Did COVID-19 (2020-21) impact enforcement?
- Is pending backlog growing structurally?
- Is revenue growing year-over-year?

### Financial Performance (Page 3)
- How much money is generated vs collected?
- What is the collection efficiency rate?
- Is pending amount increasing over time?
- What is the average fine trend?
<img width="843" height="475" alt="image" src="https://github.com/user-attachments/assets/4f5eb7f5-e9b3-4f1b-b538-d52ec83a945a" />

### Court Analysis (Page 4)
- What percentage of challans go to court?
- Is court processing a bottleneck?
- What is the court disposal efficiency?
- Are years with high court cases correlating with high pending amounts?

---
<img width="842" height="478" alt="image" src="https://github.com/user-attachments/assets/60c51751-ce74-4a2d-a1eb-3fa64f20d8c4" />

##  Dataset Information

**Source:** E-Challan Daily Data (2015-2026)  
**File:** `echallan_daily_data.csv`  
**Size:** 286.66 KB  
**Records:** 4,061 daily entries

### Data Columns

| Column | Description | Data Type |
|--------|-------------|-----------|
| `date` | Date of record | DateTime |
| `totalChallan` | Total fines issued daily | Integer |
| `disposedChallan` | Fines paid/settled by citizens | Integer |
| `pendingChallan` | Fines unpaid/outstanding | Integer |
| `totalAmount` | Total fine value generated (₹) | Currency |
| `disposedAmount` | Collected fine value (₹) | Currency |
| `pendingAmount` | Outstanding fine value (₹) | Currency |
| `totalCourt` | Total cases sent to court | Integer |
| `pendingCourt` | Cases pending in court | Integer |
| `disposedCourt` | Cases resolved in court | Integer |

---

## 🔍 Key Insights & Findings

### 1. **Revenue Collection Efficiency**
- Only **36.13%** of total revenue has been collected
- **63.87%** (₹406bn) remains pending
- Indicates significant gaps in collection enforcement

### 2. **Court System Bottleneck**
- **85%** of court cases remain unresolved
- Only **15%** court disposal rate
- Court escalation significantly delays revenue realization
- Court processing is a major bottleneck in the system

### 3. **Pending Backlog Trend**
- Pending challans show structural growth until 2024
- Sharp decline in 2025-2026 (data may be incomplete or enforcement changed)
- Backlog accumulation indicates capacity constraints

### 4. **COVID-19 Impact (2020-2021)**
- Visible reduction in challan issuance during pandemic years
- Recovery pattern observed post-2021
- Enforcement activity returned to pre-pandemic levels by 2022

### 5. **Average Fine Trend**
- Average fine value: **₹103K**
- Shows increasing trend over years
- May indicate stricter penalties or inflation adjustment

---

##  Tools & Technologies

- **Microsoft Power BI Desktop**
- **Data Source:** CSV file import
- **Visualizations Used:**
  - Line Charts
  - Stacked Column Charts
  - Donut/Pie Charts
  - Area Charts
  - Scatter Plots
  - Combo Charts (Line + Column)

### Key Features Implemented
-  Dynamic filtering across pages
-  Custom color theme for consistency
-  Calculated measures for rates and percentages
-  Time-series trend analysis
-  Cross-page drill-through capabilities

---

##  Dashboard Pages Structure

### **Page 1: Executive Overview**
Clean, high-level summary with key performance indicators and trend visualization

### **Page 2: Trend Analysis**
Year-over-year growth patterns, COVID impact, and long-term enforcement trends

### **Page 3: Financial Performance**
Revenue generation, collection efficiency, and pending amount analysis

### **Page 4: Backlog & Efficiency**
Disposal capacity, pending trends, and system scalability assessment

### **Page 5: Court Analysis**
Court case burden, resolution rates, and judicial bottleneck identification

---

##  Recommendations Based on Analysis

1. **Improve Collection Mechanisms**
   - 64% pending revenue indicates need for stronger follow-up
   - Consider automated payment reminders
   - Implement penalty escalation for long-pending cases

2. **Address Court Bottleneck**
   - 85% court pending rate is critical
   - Explore alternative dispute resolution mechanisms
   - Increase judicial capacity for traffic cases

3. **Enhance Disposal Efficiency**
   - Scale disposal capacity with growing challan volume
   - Digitize more processes to reduce manual bottlenecks
   - Monitor disposal rate as a key performance indicator

4. **Revenue Realization Focus**
   - ₹406bn pending is significant financial exposure
   - Prioritize high-value pending cases
   - Implement collection incentives or settlement schemes

---

##  How to Use This Dashboard

### Opening the Dashboard
1. Install **Microsoft Power BI Desktop** (free version available)
2. Download the `.pbix` file from this repository
3. Open the file in Power BI Desktop
4. Data will refresh automatically if CSV is in the same directory

### Interacting with Visuals
- **Click** on any chart element to filter other visuals
- Use **slicers** (Year, Date) to focus on specific time periods
- **Hover** over data points for detailed tooltips
- **Right-click** on visuals for export and drill-down options

### Navigation
- Use page tabs at the bottom to move between analysis pages
- All pages are interconnected with consistent filtering
- Return to Page 1 for executive summary view


---

## Contact

**Amirtha Ganesh R**

For questions, feedback, or collaboration opportunities, please reach out through:
- Email: amirthaganeshramesh@gmail.com

---



##  Acknowledgments

- Dataset Source: E-Challan Daily Data (2015-2026)
- Tool: Microsoft Power BI
- Guidance: ChatGPT for analytical framework and dashboard structure

---

**Last Updated:** February 2026  
**Version:** 1.0

---

### 🌟 If you found this project useful, please consider giving it a star!
