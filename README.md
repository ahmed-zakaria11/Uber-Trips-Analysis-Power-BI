# 🚗 Uber Trips Analysis – Power BI Project  

## 📌 Project Overview  
This Power BI project analyzes Uber trip data to uncover travel behavior patterns. The dashboard provides insights into trip purposes, pickup and drop-off hotspots, trip duration trends, distance distributions, and rush-hour activity.  

By applying **Power Query transformations**, **DAX measures**, and **interactive visualizations**, the project delivers a complete end-to-end analysis of urban mobility.  

---

## 📑 Dataset  
- **Source:** Uber trips dataset  
- **Columns:** start date, end date, start location, end location, miles, trip purpose, category  
- **Rows:** 1,155  
---

## 🧹 Data Cleaning & Transformation  
Data was prepared in Power BI’s **Power Query Editor** to ensure accuracy and consistency:  
- Replaced all `null` values with **"Unknown"**  
- Removed an unnecessary **summary row**  
- Standardized **distance values** to one decimal place  
- Unified all **datetime columns** into `DD/MM/YYYY` format  
- Calculated **trip duration (minutes)** from start and end times  
- Created **duration bins** (15-minute intervals) for better analysis  
- Added a **Start Time column** to identify rush hours  

This process ensured the dataset was clean, reliable, and ready for analysis.  


---

## 📈 Dashboard Design  
- KPIs for **total trips, average distance, and average duration**  
- Bar charts of **pickup and drop-off locations**  
- Breakdown of **trip category (Business vs Personal)**  
- **Rush-hour analysis** with hourly distribution  
- Duration analysis using **15-minute bins**  
- Insights into top cities, distance ranges, and busiest travel times  

---

## 🔑 Key Insights  
- **Business trips** make up the majority of total trips compared to personal travel  
- Clear **rush-hour peaks** between 1:00 pm and 6:00 pm 
- Most trips last **under 15 minutes** or **15-30 minutes** and cover short to medium distances  
- **Cary** is the **top pickup/drop-off location**
- **Meeting** is the most commen purpose
- Average trip distance is **11 miles** while average duration is **23 minutes** 

---

## 🚀 Tools Used
- **Power BI Desktop**
- 
---
## 📖 Learning Outcome  
This project demonstrates the ability to:  
- Clean and transform raw trip data with Power Query  
- Design an **interactive Power BI dashboard** with advanced visuals  
- Build DAX measures for KPIs and calculated insights  
- Deliver actionable findings on **urban travel behavior**  

---

## 📂 Repository Structure  
📂 Dataset
📂 Screenshots
📄 README.md
📄 Uber.pbix
---

## 🖼️ Dashboard  
![Dashboard Overview](Screenshots/Overview.PNG)  
![Rush Hour Analysis](Screenshots/Rush%20hour.PNG)  

