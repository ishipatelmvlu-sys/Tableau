Hotel Booking Revenue & Guest Segmentation Dashboard
📊 Project Overview

This project focuses on creating an interactive Hotel Booking Revenue & Guest Segmentation Dashboard using Tableau. The dashboard analyzes hotel booking data to understand revenue, profit, guest trends, room-type performance, regional performance, and customer segments.

🎯 Objective

The main objective of this project is to create an interactive Tableau dashboard that provides meaningful insights into hotel booking performance and customer behavior using different charts, KPIs, maps, and filters.

📂 Dataset
Dataset Name: Hotel Booking Revenue & Guest Segmentation Dataset
Format: CSV
Records: 800
Hotels: 6
Cities: 12
Regions: 4
Room Types: 4
Booking Categories: 4
Booking Channels: 4
Important Fields

Booking ID, Customer ID, Booking Date, Check-in Date, Hotel, City, Region, Room Type, Booking Category, Booking Channel, Guests, Nights, Room Rate, Discount (%), Revenue, Cost, Profit, Customer Age, Customer Gender, Payment Method, Customer Rating, and Booking Status.

🛠️ Tools & Technologies
Tableau Public
CSV Dataset
Tableau Calculated Fields
Data Visualization
Tableau Dashboard
📈 Dashboard Visualizations

The dashboard includes:

KPI Cards – Total Revenue, Total Profit and Total Guests
Monthly Revenue – Line Chart
Revenue by Room Type – Bar Chart
Revenue by City – Map
Discount vs Profit – Scatter Plot
Customer Segmentation – Bar Chart
Interactive Filters for Year, Room Type, Region and Hotel
🧮 Calculated Fields

Total Revenue: SUM([Revenue])

Total Profit: SUM([Profit])

Profit Ratio: SUM([Profit]) / SUM([Revenue])

Average Revenue: AVG([Revenue])

Customer Segment:

IF [Customer Age] <= 25 THEN "Young"
ELSEIF [Customer Age] <= 35 THEN "Adult"
ELSEIF [Customer Age] <= 50 THEN "Middle Age"
ELSE "Senior"
END
🔍 Key Insights
The dataset contains 800 hotel booking records, generating approximately ₹10.85 million in revenue and ₹3.79 million in profit.
The South Region generated the highest revenue of approximately ₹2.93 million.
BlueHarbor was the highest-performing hotel with approximately ₹2.04 million revenue.
Deluxe Rooms generated the highest profit of approximately ₹1.10 million.
The Senior customer segment generated the highest revenue of approximately ₹4.57 million.
📁 Project Files
Hotel_Booking_Revenue_Guest_Segmentation_800_Rows.csv
Tableau Workbook (.twbx)
Dashboard Screenshot
README.md
✅ Conclusion

The Hotel Booking Revenue & Guest Segmentation Dashboard provides an interactive way to analyze hotel performance, revenue, profit, room types, regional performance, and customer segments. Tableau visualizations and filters make it easier to identify important business trends and support data-driven decision-making.
