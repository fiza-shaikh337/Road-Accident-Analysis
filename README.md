# 🚦 Road Accident Analysis - Code + Power BI Dashboard
 
End-to-end project: Data Cleaning with Code + Interactive Dashboard in Power BI.
Analyzed **12,315 road accidents** and **19K casualties** to find when, where & why accidents happen.
 
<img width="607" height="333" alt="image" src="https://github.com/user-attachments/assets/55f81ef8-e48b-4fe6-b678-31064c143ce8" />

 
## 📊 Key KPIs
- **Total Accidents:** 12.315K
- **Total Casualties:** 19K
- **Fatality Rate (DAX):** 1.3%
 
## 🔍 Key Insights
- **Most Dangerous Time:** Afternoon (5.1K accidents) > Morning (3.2K) > Evening Peak (2.7K) > Night (1.3K)
- **Most At-Risk Age Group:** 18-30 years (4.3K) followed by 31-50 years (4.1K)
- **Top Cause:** No Distancing (2.26K) followed by Lane Change (R) (1.81K)
- **Light Conditions:** 72% accidents in Daylight, 27% in Dark (Lit)
- **Top Area Type:** Other (3.59K) and Office areas (3.28K)
 
## 💻 Part 1 - Data Cleaning & Analysis (Code)
- Cleaned raw dataset - handled nulls, duplicates, date/time formatting
- Created new columns: Time Slot (Morning, Afternoon, Evening Peak, Night), Age Band
- Explored patterns in Accidents by Time, Age, Cause, Area & Light Conditions
- Exported clean dataset for Power BI
 
## 📊 Part 2 - Power BI Dashboard
- Built KPIs using DAX (Fatality Rate, Total Accidents, Total Casualties)
- Visuals: Bar Chart, Donut Chart, Treemap, Funnel Chart
- Slicers for Weather Status & Week Days
- Sorted Top 4 / Top 5 visuals by value
 
## 🛠️ Tools Used
- Python (Jupyter Notebook) - Data Cleaning
- Power BI Desktop - Dashboard
- DAX - KPIs
 
## 📁 Files in this Repo
- `Road_Accident_Analysis.ipynb` 
- `Road Accident Analysis.pbix`
- `clean_road_accident.csv`
- `dashboard image.png`
 
## 🚀 How to Use
1. Run the code file `Road_Accident_Analysis.ipynb` in Jupyter Notebook to clean the data
2. Open `Road Accident Analysis.pbix` in Power BI Desktop
3. Use slicers to filter by Weather & Week Day
 
