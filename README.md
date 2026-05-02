# 🚗 Highway Traffic Data Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-yellow.svg)
![NumPy](https://img.shields.io/badge/NumPy-Computations-lightblue.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualizations-orange.svg)

## 📌 Project Overview
Traffic jams cost money, pollute the air, and damage roads. This project analyzes the **Metro Interstate Traffic Volume** dataset to determine how the time of day, adverse weather conditions, and the day of the week impact the number of vehicles on the I-94 highway. The primary goal is to uncover predictable traffic patterns and identify anomalies using a structured data analysis pipeline.

## 🎯 Research Questions
1. Exactly when is "Rush Hour," and how bad does it get?
2. Does extreme bad weather (like heavy snow or freezing cold) keep cars off the road?
3. How does traffic change between weekdays and weekends?
4. Can we use math (Z-scores) to find weird traffic jams, like a jam at midnight?

## 📊 Dataset Information
* **Dataset Name:** `Metro_Interstate_Traffic_Volume.csv`
* **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/492/metro+interstate+traffic+volume)
* **Size:** 48,204 rows & 9 columns (Expanded to 15 columns after feature engineering)
* **Target Variable:** `traffic_volume`

## 🛠️ Technologies Used
* **Python 3:** Core programming language.
* **Pandas:** Loading, cleaning, filtering, grouping, and aggregating data.
* **NumPy:** Advanced mathematical anomaly detection (Z-score) and variance calculation.
* **Matplotlib:** Rendering correlation heatmaps, line charts, scatter plots, and bar charts.

## 💡 Key Findings
* **Bimodal Rush Hour:** Traffic follows a strict bimodal trend dictated by working hours, peaking specifically at **7:00 AM** and **4:00 PM**, nearly doubling the baseline hourly average.
* **Weekday vs. Weekend Flow:** Weekdays carry significantly more traffic (averaging 3,407 vehicles) than weekends (averaging 2,370 vehicles). **Friday** is the busiest day of the week.
* **Weather Impact:** Extreme weather moderately suppresses traffic. Clearer conditions (Clouds/Haze) correlate with peak traffic, while adverse conditions (Squalls/Thunderstorms) align with lower traffic volumes.
* **Midnight Anomalies:** Using Z-score mathematical anomaly detection, **17 distinct anomalies** were discovered where midnight traffic spiked over 2,000 vehicles, indicating unusual late-night events or roadwork.

## 📂 Repository Contents
* `Python_Final_Term_project_23_50025_1.ipynb`: The main Jupyter Notebook containing all the Python code, data cleaning, feature engineering, and visualizations.
* `Final_Project_Report_Template.pdf`: The final compiled project report detailing the methodology, visual charts, and analytical insights.

## 👨‍💻 Author
**MD Mazharul Islam Nabil**  
* **Student ID:** 23-50025-1
* **Course:** Programming in Python (Section D)
* **Instructor:** MD. TANZEEM RAHAT
* **University:** American International University-Bangladesh (AIUB)
