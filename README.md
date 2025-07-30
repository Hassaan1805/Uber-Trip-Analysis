# 🚕 Uber Trips Data Analysis (Jan–Feb 2015) 📊

Welcome! Dive into a quick data exploration 🚦of NYC Uber trips from January and February 2015. This project uncovers *when, where, and how* riders moved, using powerful Python tools for insightful visualizations. 

## 🗂️ Project Overview

Explore urban mobility patterns and find the answers to:
- ⏰ **When** do most trips happen?
- 📍 **Where** are hotspots for Uber pickups?
- 🗓️ **How** do weekends compare to weekdays?

## 📑 Dataset

- **File:** `Uber-Jan-Feb-FOIL.csv`
- **Details:** Contains trip timestamp, latitude, longitude, base, active vehicles, and total trips per day.

## 📈 Key Analyses & Visualizations

- 📅 **Trips per Hour, Day, Month:** Understand trip timing.
- 📆 **Weekday vs Weekend:** Spot weekly patterns.
- 🌡️ **Heatmap:** Visualize peak hours and busy days.
- 🗺️ **Scatter/Heatmap:** Find popular pickup locations.
- 🏢 **Base Distribution:** Which dispatch bases are the busiest?
- 🧭 **Mean Pickup Location by Hour:** How does the city move through the day?
- 🥇 **Top Busiest Hours:** See when Uber is in highest demand.
- 🧩 **Correlation Matrix:** Numeric relationships at a glance.
- 🛣️ **Trip Distance Distribution:** How far do riders go?

## 💻 Technologies & Libraries

- Python 3 🐍
- Pandas 🐼
- NumPy 🔢
- Matplotlib 📊
- Seaborn 🌈

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone 
   ```
2. **Place the dataset** `Uber-Jan-Feb-FOIL.csv` in your working directory.
3. **Install requirements:**
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
4. **Run the script:**
   ```bash
   python uber.py
   ```

## 📂 File Structure

| File                      | Description                                |
|---------------------------|--------------------------------------------|
| `Uber-Jan-Feb-FOIL.csv`   | 📥 Raw Uber trips data                     |
| `uber.py`                 | ⚙️ Pandas data wrangling & all plots       |

## ✨ Insights & Observations

- 📉 **Rush hours revealed:** See how demand spikes are tied to the city’s rhythm.
- 📆 **Weekday/weekend differences:** Find out when New Yorkers Uber most.
- 📍 **Pickup hotspots:** Map the action with location-based visuals.
- 🏢 **Base impacts:** Top-performing Uber bases at a glance.
- 📏 **Trip length trends:** Most trips fall within certain ranges.
