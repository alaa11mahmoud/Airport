# ✈️ Airport Delay Analysis Dashboard - Power BI

This project is an interactive **Power BI dashboard** that analyzes flight delay data across various U.S. airports. It provides clear insights into the reasons behind delays, their distribution over time, and airline-level performance.

---

## 📊 Dashboard Overview

The report consists of multiple visual components:

- **Delay Reasons Breakdown**  
  Shows the percentage contribution of each delay cause:
  - Carrier Delay: 7.15%
  - NAS Delay: 12.10%
  - Late Aircraft Delay: 28.83%
  - Weather & Security Delay: <1%
  - Others: 51.32%

- **Total Delay by Airport**  
  Highlights top airports with the most total delay minutes.  
  Example: Hartsfield–Jackson Atlanta International Airport: **33.6K minutes**

- **Delays by Day of the Week**  
  Sunday shows the highest total delay (~18.5K minutes), followed by Friday.

- **Monthly Flight Volume vs Delay Time**  
  December has the highest number of flights and total delays.

- **Carrier-wise Filtering**  
  Dynamic filter to analyze delay patterns by airline.

---
## Project Steps
### Here’s a breakdown of how the project was built:

### 1 Data Source Preparation
Imported raw flight delay data from Excel into Power BI.

### 2 Data Modeling
Created the following dimensional tables:

Airport Dim: Contains airport names and details.
Carriers Dim: Contains airline/carrier names and codes.
Date Dim: Created using DAX to enable time-based analysis.
Built a Fact Table for flight delay records with relationships to all dimensions.

### 3 Data Transformation & DAX Calculations
Cleaned and structured the data using Power Query.

### 4 Created calculated columns and measures, including:
TotalMinutes_Late
Delay categories (Carrier, NAS, Weather, etc.)
Delay % by reason
On-time vs late flight percentage

### 5 Dashboard Design & Visualization
Designed a user-friendly dashboard using slicers, KPIs, and charts.
Added filters by carrier, airport, and date to enhance interactivity.

### 5 Insights Extraction
Identified top airports, peak delay days, and high-delay carriers.
Analyzed seasonal and weekly delay trends.

---
## 🛠 Tools & Technologies

- **Power BI**
- DAX (Data Analysis Expressions)
- Data Modeling
- Interactive Slicers & Filters
- Custom Visuals

---


## 🚀 How to Use

1. Open the `.pbix` file using Power BI Desktop.
2. Explore the visuals and interact with slicers.
3. Filter by carrier, date, or delay reason to derive specific insights.

---

## 📌 Use Cases

- Aviation performance monitoring
- Airline operations optimization
- Delay pattern forecasting
- Executive reporting and KPIs

---

## files
**https://drive.google.com/drive/folders/1G5225ysqJ9vFFuFSMh_cpjJ1ZIBsyv4s?usp=sharing**

## 📬 Contact

Feel free to connect with me on [LinkedIn](#) or reach out if you'd like to collaborate or provide feedback!

---



