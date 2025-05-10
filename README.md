# 🚖 Travel Insights Power BI Dashboard

This project provides detailed travel-related insights using Power BI based on a dataset containing trip records, location mapping, and time dimensions. It enables data-driven decision-making by analyzing revenue, passenger trends, trip timings, and route efficiency.

---

## 🧾 Project Summary

- **Tool Used:** Microsoft Power BI
- **Data Sources:**
  - `TripData`: Contains details of each trip (pickup time, drop time, distance, fare, payment mode, etc.)
  - `Location`: Maps location IDs to real city names.

---

## 📂 Project Structure

| Table        | Description                                                  |
|--------------|--------------------------------------------------------------|
| TripData     | Core table with trip ID, pickup/drop times, distance, fare.  |
| Location     | Mapping of `LocationID` to readable `LocationName`.          |
| Date         | Date dimension with Year, Month, and Day breakdown.          |

---

## 📌 Key Insights

- **Total Revenue:** ₹7K+
- **Total Passengers:** 746
- **Revenue by Operation Period:** Day, Night, Evening, Dawn
- **Trips by Day of Week**
- **Most Frequent Locations (Pickup/Drop)**
- **Trip Distance by Location**
- **Passenger Distribution by Time Period**
- **Mode of Payment Analysis** – Cash vs UPI
- **Total Minutes by Location**


---

## 📈 KPIs Used

- **Total Revenue**  
- **Total Distance**  
- **Total Minutes**  
- **Total Passengers**  
- **Trips by Operation Period (Day/Night/Evening/Dawn)**  
- **Average Fare per Distance**  
- **Surge Fee Analysis**  

---

## 🔗 Relationships in Data Model

- `TripData[Pickup Date]` → `Date[Pickup Date]`  
- `TripData[PULocationID]` & `DOLocationID` → `Location[LocationID]`  

---


## 📁 Files Included

- `TravelInsights.pbix` – Main Power BI dashboard file
- `README.md` – Project documentation
- Sample screenshots of dashboard (for GitHub preview)
- Raw Data Excel File of Tables (Trip Data and Location).

---

## 📌 Future Improvements

- Add real-time API integration (e.g., live trip data)
- Include geospatial visuals (Map of trips)
- Predictive analytics for fare estimation or peak hours

---

## 🙌 Credits

Created by Nishi Vijayvargiy – Aspiring Data Analyst  
Connect with me on [LinkedIn]([your-linkedin-url](https://www.linkedin.com/in/nishi-vijayvargiya-849577192/)) | [GitHub]([your-github-url](https://github.com/Nishivv))

---

## 🏷️ Tags

`#PowerBI` `#DataAnalytics` `#TravelDashboard` `#DataVisualization` `#ETL` `#DAX` `#BusinessIntelligence`


