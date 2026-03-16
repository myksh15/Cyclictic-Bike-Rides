# Cyclistic Bike-Share Analysis: Annual Membership Conversion
### [cite_start]Google Data Analytics Capstone Project [cite: 175, 176]

## 🚲 Project Overview
[cite_start]This case study analyzes **5,601,662 rides** from Cyclistic, a bike-share program in Chicago, to identify how annual members and casual riders use the service differently[cite: 177, 179]. [cite_start]The ultimate goal is to provide data-driven recommendations to convert casual riders into long-term annual members[cite: 180].

## 🛠️ Data Cleaning & Tools
* [cite_start]**Tools:** Microsoft Excel (Power Query for ETL, Pivot Tables for analysis)[cite: 199].
* [cite_start]**Dataset:** 12 months of historical trip data (March 2024 - February 2025) sourced from Motivate International Inc[cite: 183, 184].
* **Cleaning Process:**
    * [cite_start]Merged 12 monthly CSV files into a single dataset using Power Query[cite: 201].
    * [cite_start]Created derived columns for Month, Day, Hour, and Ride Time[cite: 203].
    * [cite_start]Categorized trip lengths into four brackets: Under 10, 30, 60 mins, and Over 60 mins[cite: 204].
    * [cite_start]Verified data integrity by confirming 5,601,662 unique records with no duplicate Ride IDs[cite: 207, 210].

## 📊 Key Insights
[cite_start]Through exploratory data analysis, I identified distinct behavioral profiles for both groups[cite: 310, 311]:

| Dimension | Casual Riders | Member Riders |
| :--- | :--- | :--- |
| **Usage Type** | Recreational | Commute |
| **Peak Days** | Fri - Sun | Mon - Fri |
| **Peak Hours** | 4-6 PM (gradual) | 8 AM & 5 PM (sharp spikes) |
| **Ride Duration** | 10–30 mins | Under 10 mins |

* [cite_start]**Seasonality:** Both groups peak in summer, with **81% of casual rides** occurring between May and October[cite: 235, 236].
* [cite_start]**Bike Preference:** Both groups prefer **Electric Bikes** over Classic Bikes[cite: 290].

## 💡 Top Recommendations
* [cite_start]**Seasonal Membership Tiers:** Launch "Weekend" and "Summer" passes to capture high-volume recreational users[cite: 314, 315].
* [cite_start]**"Try Commuting" Campaign:** Use social media and employer partnerships to show casual riders how a membership pays for itself through daily commuting[cite: 323, 327].
* [cite_start]**Long-Ride Incentives:** Implement a loyalty program that rewards rides over 30 minutes, specifically targeting the casual rider habit[cite: 330, 331].

## 📂 How to use this repository
* **Analysis Report:** View the full [Google - Case Study 1.pdf] for detailed visualizations.
* **Scripts:** The `cleaning_logic.txt` file contains the M-code used for data transformation.
