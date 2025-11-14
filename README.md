### rapido-trip-analysis
### 🚀 Rapido Trip Analysis (EDA Project)

A complete Exploratory Data Analysis (EDA) of Rapido trip data to understand customer behavior, trip patterns, demand trends, and operational performance. This project includes data cleaning, feature engineering, visualizations, and actionable insights to help optimize ride operations and improve user experience.

### 🔍 Project Overview

This project analyzes Rapido trip-level data to uncover:

Trip demand patterns

Customer usage behavior

Peak hours & peak locations

Trip duration & distance distribution

Revenue trends

Driver performance metrics

Cancellations and delays (if included)

The goal is to find insights that can help improve operational efficiency, reduce cancellations, and increase customer satisfaction.

### 🔄 Workflow / Project Pipeline
1️⃣ Data Collection

Dataset collected from Rapido trip records (CSV/Excel).

2️⃣ Data Understanding

Inspecting structure, columns, data types

Identifying missing values & duplicates

Understanding key variables:

Trip ID

Start & end time

Pickup & drop location

Trip distance

Fare amount

Cancellation status

3️⃣ Data Cleaning

Removed duplicates

Fixed incorrect date/time formats

Handled null values

Corrected inconsistent labels

Converted timestamps to datetime

4️⃣ Feature Engineering

Trip duration calculation (end_time – start_time)

Time-based features:

Hour

Day of week

Month

Distance buckets

Revenue per trip

Driver performance metrics


5️⃣ Visualizations

Used Donut Charts for Revenue Split.

Line charts (Pickup Time/ Week days)

Bar charts (Distance, Total Revenue, Most Preferred vehicle)

Filter (Customer Cancellation Insights)

Stacked Area Chart (Frequent Pickup Location, Frequent Drop Location)

### 📁 Folder Structure
```
├── data/
│   ├── Rapidoo_csv.csv
│
├── visuals/
│   ├── Overview Analysis
│   ├── Timeseries Analysis
│   ├── Details
│
├── README.md
├──requirements.txt

```
### Tools

Power BI

Excel

Power Query

DAX

📈 Key Insights (Sample)


  - Evening hours (3:30 PM - 7:30 PM) show the highest trip demand.

  - Weekends have 20–30% more bookings compared to weekdays.

  - Short-distance trips (< 3 km) contribute to the maximum trip volume.

  - Peak pickup hotspots are around bus stations & commercial areas.

  - Average trip duration is 8–12 minutes, depending on traffic.

### 🗺️ Visual Highlights

Click the link for Visualization https://github.com/HarishDomala/rapido-trip-analysis/tree/main


### 🧪 How to Run This Project
git clone https://github.com/HarishDomala/rapido-trip-analysis
cd Rapido-Trip-Analysis


### 👨‍💻 Author

Harish Domala

🔗 GitHub: https://github.com/HarishDomala

🔗 LinkedIn: https://linkedin.com/in/harishdomala
