# Cyclistic Bike-Share Analysis: Annual Membership Conversion
### Google Data Analytics Capstone Project

## 🚲 Project Overview
This case study analyzes **5,601,662 rides** from Cyclistic, a bike-share program in Chicago, to identify how annual members and casual riders use the service differently. The ultimate goal is to provide data-driven recommendations to convert casual riders into long-term annual members.

## 🛠️ Data Cleaning & Tools
* **Tools:** Microsoft Excel (Power Query for ETL, Pivot Tables for analysis).
* **Dataset:** 12 months of historical trip data (March 2024 - February 2025) sourced from Motivate International Inc.
* **Cleaning Process:**
    * Merged 12 monthly CSV files into a single dataset using Power Query.
    * Created derived columns for Month, Day, Hour, and Ride Time.
    * Categorized trip lengths into four brackets: Under 10, 30, 60 mins, and Over 60 mins.
    * Verified data integrity by confirming 5,601,662 unique records with no duplicate Ride IDs.

## 📊 Key Insights
Through exploratory data analysis, I identified distinct behavioral profiles for both groups:

| Dimension | Casual Riders | Member Riders |
| :--- | :--- | :--- |
| **Usage Type** | Recreational | Commute |
| **Peak Days** | Fri - Sun | Mon - Fri |
| **Peak Hours** | 4-6 PM (gradual) | 8 AM & 5 PM (sharp spikes) |
| **Ride Duration** | 10–30 mins | Under 10 mins |

* **Seasonality:** Both groups peak in summer, with **81% of casual rides** occurring between May and October.
* **Bike Preference:** Both groups prefer **Electric Bikes** over Classic Bikes.

## 💡 Top Recommendations
* **Seasonal Membership Tiers:** Launch "Weekend" and "Summer" passes to capture high-volume recreational users.
* **"Try Commuting" Campaign:** Use social media and employer partnerships to show casual riders how a membership pays for itself through daily commuting.
* [cite_start]**Long-Ride Incentives:** Implement a loyalty program that rewards rides over 30 minutes, specifically targeting the casual rider habit[cite: 330, 331].

## 📂 How to use this repository
* **Analysis Report:** View the full [Google - Case Study 1.pdf] for detailed visualizations.
* **Scripts:** The `cleaning_logic.txt` file contains the M-code used for data transformation.
