# 🚖 Travel Insights Power BI Dashboard

This project provides detailed travel-related insights using Power BI based on a dataset containing trip records, location mapping, and time dimensions. It enables data-driven decision-making by analyzing revenue, passenger trends, trip timings, and route efficiency.

---

## 📊 Dashboard Preview

![Dashboard Screenshot](your_dashboard_image_link_here)

---

## 🧾 Project Summary

- **Tool Used:** Microsoft Power BI
- **Data Sources:**
  - `TripData`: Contains details of each trip (pickup time, drop time, distance, fare, payment mode, etc.)
  - `Location`: Maps location IDs to real city names.
  - `Date`: Provides time intelligence including day, month, and year breakdowns.

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

## 💡 Additional Insights Built

1. **Most Frequent Routes**  
2. **Average Fare per KM by Location**  
3. **Rush Hour vs Non-Rush Hour Distribution**  
4. **Trip Efficiency Score (Distance / Time)**  
5. **Payment Method Trends by Location**  
6. **Revenue by Passenger Group Size**  
7. **Surge Fee Trends by Hour of Day**  
8. **Trip Duration by Day of Week**

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

## 🚀 How to Use

1. Open `Power BI Desktop`.
2. Load the provided `.pbix` file or connect to your source tables.
3. Use filters (slicers) to explore by day, location, time period, or payment mode.
4. Customize or expand visualizations using DAX or Power BI visuals.

---

## 📁 Files Included

- `TravelInsights.pbix` – Main Power BI dashboard file
- `README.md` – Project documentation
- Sample screenshots of dashboard (for GitHub preview)

---

## 📌 Future Improvements

- Add real-time API integration (e.g., live trip data)
- Include geospatial visuals (Map of trips)
- Predictive analytics for fare estimation or peak hours

---

## 🙌 Credits

Created by [Your Name] – Aspiring Data Analyst  
Connect with me on [LinkedIn](your-linkedin-url) | [GitHub](your-github-url)

---

## 🏷️ Tags

`#PowerBI` `#DataAnalytics` `#TravelDashboard` `#DataVisualization` `#ETL` `#DAX` `#BusinessIntelligence`


