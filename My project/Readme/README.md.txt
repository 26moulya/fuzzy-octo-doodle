# 🚦 Smart Traffic Flow Analysis – A Bengaluru Case Study

This project uses real-world traffic data from Bengaluru to analyze congestion patterns, identify traffic hotspots, and recommend smarter mobility strategies. Built using Python and Jupyter Notebook, it demonstrates how data analytics can improve urban transportation planning.



## 📄 Abstract

Urban traffic congestion is one of the major issues faced by fast-growing cities like Bengaluru. Using traffic data that includes volume, speed, congestion levels, environmental impact, and transport usage, this project provides insights into where, when, and why congestion occurs — and how it might be reduced.


## 🎯 Objective

- Analyze and understand traffic flow patterns across Bengaluru city.
- Detect peak hours, bottlenecks, and high-congestion intersections.
- Explore relationships between public transport usage, environmental impact, and traffic conditions.
- Suggest data-driven recommendations for city planners and commuters.



## 📂 Dataset Overview

- 📌 Source: Kaggle – Bengaluru Traffic Volume Dataset  
- 🗂️ Features:
  - Date, Hour, Weekday
  - Traffic Volume, Average Speed, Congestion Level
  - `Public Transport Usage, Environmental Impact
  - `Road/Intersection Name, Area Name, Incident Reports, etc.


## ⚙️ Working Process

### 1. 🧹 Data Cleaning
- Converted `Date` to datetime, extracted `Hour`, `Weekday`, `Month`
- Removed duplicates
- Converted and cleaned categorical and numerical columns
- Handled missing values

### 2. 📊 Exploratory Data Analysis (EDA)
- Traffic volume by hour, area, weekday
- Top congested roads and areas
- Relationship between volume and speed
- Correlation between congestion and public transport usage

### 3. 🔗 Correlation Analysis
- Strong negative correlation between traffic volume and average speed
- Higher public transport usage linked to lower congestion
- Congestion levels higher during weekday evenings


## 📈 Visual Insights

| Visualization | Description |
|---------------|-------------|
| 📍 Bar chart – Top 10 Congested Roads | Shows which roads face the highest traffic volume |
| 🕐 Line chart – Traffic by Hour | Reveals peak congestion hours (5 PM–8 PM) |
| 🚌 Boxplot – Public Transport Usage | Shows trends across weekdays |
| 🔗 Heatmap – Correlation Matrix | Identifies relationships between traffic variables |


## 💡 Key Insights

- BTM Layout, Whitefield, and MG Road face the highest congestion.
- Evening hours see a steep rise in congestion and drop in average speed.
- Better public transport usage correlates with lower congestion.
- Environmental impact worsens in zones with high traffic volume and poor transport access.



## 🚀 Tools Used

- Python 🐍
- Pandas & NumPy for data manipulation
- Seaborn & Matplotlib for visualization
- Jupyter Notebook for step-by-step analysis



## 🧪 Future Scope

- Connect to **Google Maps or HERE API** for real-time traffic monitoring.
- Build a **dashboard using Streamlit or Power BI**.
- Recommend **signal timing optimization** based on congestion level predictions.





