# 🚲 Cyclistic Bike Share Analysis
![Python](https://img.shields.io/badge/Python-Pandas-blue)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-orange)
![Google Data Analytics](https://img.shields.io/badge/Google-Data%20Analytics%20Capstone-green)

## Google Data Analytics Capstone Project

This project was completed as part of the Google Data Analytics Professional Certificate offered by Google through Coursera.

The objective of this case study was to analyze how annual members and casual riders use Cyclistic bike share services differently and provide data driven recommendations to increase membership conversions.

---

## Business Task

Cyclistic aims to maximize the number of annual memberships, which are considered more profitable than casual riders. To support this goal, this analysis explores behavioral differences between the two customer segments and identifies opportunities to convert casual riders into annual members.

---

## Tools Used

* Python (Pandas, NumPy)
* Google Colab
* Tableau
* GitHub

---

## Data Cleaning Process

The dataset required several preprocessing steps before analysis:
* Standardized column names between the 2019 and 2020 datasets
* Merged datasets into a unified structure
* Created trip duration and day of week features
* Removed 117 records with negative trip durations
* Removed records with missing end station information
* Removed 7,452 trips shorter than one minute where rides started and ended at the same station
* Checked for duplicates and missing values
* Excluded inconsistent columns caused by schema differences between datasets

---

## Key Insights

### 1. User Distribution
* Annual members accounted for 91.4% of users
* Casual riders represented 8.6% of users

### 2. User Growth
* Casual riders increased by 92.25% from 2019 to 2020
* Member growth was 9.62% during the same period

### 3. Ride Duration
* Members accumulated approximately 572 million ride minutes
* Despite representing only 8.6% of users, casual riders accumulated approximately 364 million ride minutes, highlighting significantly longer ride durations compared to members.
* Casual riders generally take longer trips than members

### 4. Peak Usage Hours
**Members**
* Peak hours: 8 AM, 4 PM, and 5 PM
* Most popular station: Canal St & Adams St

**Casual Riders**
* Peak hours: 2 PM, 3 PM, and 4 PM
* Most popular station: Streeter Dr & Grand Ave

### 5. Route Preferences
* The most popular round trip route was Lake Shore Dr & Monroe St
* Casual riders showed a strong preference for leisure oriented locations such as lakefront, aquarium, and park stations
---

## Business Recommendations
### Commuter Focused Membership Campaigns
Target office workers and students around high demand commuter stations such as Canal St & Adams St.
### Leisure Membership Programs
Develop recreational and tourism-focused promotions around popular casual rider locations.
### Conversion Incentives
Offer rewards and personalized promotions to encourage frequent casual riders to become annual members.
### Fleet Rebalancing
Optimize bike distribution by shifting inventory from commercial districts to leisure destinations based on demand patterns.
### Operational Improvements
Investigate short-duration invalid trips to identify potential operational issues and improve user experience.

---

## Dashboard Preview

### Customer Overview Dashboard

![Dashboard 1](Dashboard/Dashboard%201.png)

### Ride Behavior Dashboard

![Dashboard 2](Dashboard/Dashboard%202.png)

---
## Project Structure

```text
cyclistic-bike-share-analysis
│
├── Dashboard
│   ├── Dashboard 1.png
│   └── Dashboard 2.png
│
├── Notebook
│   └── cyclistic_analysis.ipynb
│
└── README.md
```

---

## Skills Demonstrated

* Data Cleaning
* Data Wrangling
* Exploratory Data Analysis (EDA)
* Data Visualization
* Business Insight Generation
* Dashboard Development
* Data Storytelling

---

**Author:** Jessica Agnesia Tataung
