README.md

# Divvy Bikes Data Analysis Project
## Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on the Divvy Bikes trip dataset using Python in Jupyter Notebook through Anaconda Navigator.
The analysis helps understand:
- User behavior
- Ride patterns
- Peak usage times
- Station popularity
- Differences between casual riders and members
The project includes:
- Data Cleaning
- Data Preprocessing
- Visualization
- Insights Generation
- Business Recommendations
---
# Team Members
| Sl No | Name | Role |
|------|------|------|
| 1 | Member 1 | Data Collection |
| 2 | Member 2 | Data Cleaning |
| 3 | Member 3 | Data Visualization |
| 4 | Member 4 | EDA & Insights |
| 5 | Member 5 | Documentation |
| 6 | Member 6 | Presentation & GitHub |
> Replace the above names with your actual group member names.
---
# Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Anaconda Navigator
---
# Dataset Used
Dataset: Divvy Bike Share Dataset
File Used:
- `202604-divvy-tripdata.csv`
Dataset contains:
- Ride ID
- Rideable Type
- Start & End Time
- Station Names
- Latitude & Longitude
- User Type (Member/Casual)
---
# Project Structure
```bash
Divvy-Bikes-EDA/
│
├── data/
│   └── 202604-divvy-tripdata.csv
│
├── notebook/
│   └── Divvy_Bikes_EDA.ipynb
│
├── images/
│   └── charts_and_graphs
│
├── README.md
│
└── requirements.txt

⸻

Steps Performed

1. Data Loading

* Imported CSV dataset using Pandas.

2. Data Cleaning

* Removed duplicates
* Converted date columns
* Removed invalid trip durations
* Handled missing values

3. Feature Engineering

Created:

* Trip Duration
* Day of Week
* Hour
* Month

4. Exploratory Data Analysis

Analyzed:

* Casual vs Member users
* Trip durations
* Popular stations
* Rideable type usage
* Peak hours and days
* Monthly trends

5. Visualization

Used:

* Count plots
* Histograms
* Boxplots
* Line charts
* Heatmaps
* Bar charts

⸻

Key Insights

* Members use bikes more frequently than casual riders.
* Casual riders usually take longer trips.
* Electric bikes are highly preferred.
* Peak hours occur during commuting times.
* Weekend usage is higher among casual riders.

⸻

Business Recommendations

* Increase bike availability during peak hours.
* Promote memberships to casual riders.
* Add more electric bikes.
* Improve service around highly used stations.
* Provide weekend offers and promotions.

⸻

How to Run the Project

Step 1

Install Anaconda Navigator.

Step 2

Open Jupyter Notebook.

Step 3

Install required libraries:

pip install pandas numpy matplotlib seaborn

Step 4

Open the notebook file:

Divvy_Bikes_EDA.ipynb

Step 5

Run all cells.

⸻

Output

The project generates:

* Cleaned dataset
* Graphs & visualizations
* Insights
* Business recommendations

⸻

Future Improvements

* Predictive analysis using Machine Learning
* Interactive dashboard using Power BI/Tableau
* Real-time ride analysis

⸻

Conclusion

This project successfully analyzes Divvy Bike usage patterns and provides useful insights into customer behavior, operational trends, and business opportunities.

⸻

License

This project is for educational purposes only.

⸻

Acknowledgement

Thanks to Divvy Bikes and the dataset providers for making the data available for analysis.
