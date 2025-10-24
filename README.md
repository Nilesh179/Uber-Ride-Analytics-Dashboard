# Uber-Ride-Analytics-Dashboard
The Uber Ride Analytics Dashboard is an end-to-end data analytics project that transforms raw ride data into meaningful business insights. The project includes data cleaning, transformation, and exploratory data analysis (EDA) using Microsoft Excel, followed by dynamic data visualization and reporting through Power BI.

This dashboard helps analyze ride performance, revenue distribution, customer trends, and vehicle-wise operations, empowering business stakeholders to make data-driven decisions.

# 🎯 Objective
To perform comprehensive data analysis on Uber ride data, uncover key insights about ride trends, cancellations, customer behavior, and revenue generation, and visualize them through an interactive Power BI dashboard.

# 💻 Tech Stack
The following tools and technologies were used throughout the project:
• 📊 Microsoft Excel – Initial dataset exploration, data cleaning, and preprocessing.
• 🗑️ Data Cleaning & Transformation – Handling missing values, formatting inconsistencies, and creating structured datasets.
• 🧠 Exploratory Data Analysis (EDA) – Performed in Excel to detect trends, outliers, and key metrics.
• 📈 Power BI Desktop – For building dynamic dashboards, creating relationships, DAX measures, and generating insights.
• 📁 File Format: .csv for data preparation and .pbix for dashboard visualization.

# 🗂️ Dataset Details
The dataset includes comprehensive ride-level information with the following key attributes:
• Vehicle Type – Auto, Bike, Go Mini, Go Sedan, Premier Sedan, Uber XL
• Customer Count – Total number of customers per category
• Completed Bookings – Successfully completed rides
• Revenue – Total revenue generated per vehicle type
• Total Distance – Distance covered in all rides
• Average Distance – Mean distance traveled per ride
• Cancellations & Incomplete Rides – Trips that were not completed

# ❯❯❯❯ Steps Performed

1. Data Collection & Import
  • Imported the raw Uber dataset into Microsoft Excel.
  • Conducted an initial scan for missing or inconsistent data entries.

2. Data Cleaning & Preprocessing
  • Removed duplicates and invalid entries.
  • Standardized data formats (dates, vehicle types, and numeric columns).
  • Created calculated columns for metrics like total revenue, completion rate, and average ride distance.

3. Exploratory Data Analysis (EDA)
   • Analyzed patterns in completed vs. cancelled rides.
   • Studied ride trends across months and vehicle categories.
   • Derived performance KPIs such as:
     • Total Completed Rides
     • Total Revenue Generated
     • Total Distance Covered
     • Average Distance per Ride
   
4. Data Visualization in Power BI
   • Built an interactive dashboard with multiple pages:
      • Vehicle Analysis View – Performance comparison between Auto, Bike, Go Mini, Sedan, etc.
      • Revenue Insights – Month-wise and vehicle-wise revenue breakdown.
      • Operational Metrics – Completed, cancelled, and incomplete rides with dynamic filters.
      • Customer Insights – Ratings for customers and drivers, top pickup and drop locations.
   • Added DAX measures for calculating KPIs dynamically.
   • Integrated filters and slicers for real-time data interaction.

# 📊 Key Insights
• Autos and Bikes contributed the highest number of completed rides, making up a major portion of total revenue.
• Premier Sedan and Uber XL generated lower ride counts but higher average revenue per trip.
• Yearly Trend: Ride cancellations were significantly reduced post-Q2, indicating better operational efficiency.
• Customer Ratings: Average customer satisfaction remained above 4.3/5, with consistent driver performance.
• Top Locations: Jahangirpuri and Yamuna Bank emerged as key pickup and drop hubs.

# 💡 Business Impact
• Helped operations teams identify top-performing vehicle types and regions.
• Supported marketing and planning teams in optimizing route performance and customer satisfaction.
• Enabled data-driven decision-making through clear visualization of ride, distance, and revenue KPIs.

# 📸 Dashboard Snapshots

🚗 Homepage & Navigation
Vehicle Overview 2
Revenue Insights

# 📈 Key Metrics Summary

| Metric             | Value          | Description                             |
| :----------------- | :------------- | :-------------------------------------- |
| Completed Bookings | **92.5K**      | Successfully completed rides            |
| Lost Bookings      | **14K**        | Cancelled rides                         |
| Revenue            | **₹5.18 Cr**   | Total revenue generated                 |
| Total Distance     | **625.62K km** | Distance covered in all completed rides |
| Average Distance   | **24.6 km**    | Mean distance per ride                  |

# 🏁 Conclusion

This project demonstrates an end-to-end data analytics workflow — from data extraction and preprocessing in Excel to developing an insightful Power BI dashboard.
It highlights analytical thinking, technical proficiency, and storytelling through data visualization, making it ideal for business decision-makers and analysts.

# 📌 Future Enhancements

•  Automate data refresh using Power BI Service and scheduled gateway connections.
•  Integrate external APIs (e.g., weather or traffic) to explore correlation with ride demand.
•  Add predictive insights for revenue forecasting and cancellation reduction.
