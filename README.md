#  Delhi Metro Network Analysis with Python

Welcome to the **Delhi Metro Network Analysis** project! This project takes a deep dive into the structure and evolution of the Delhi Metro using Python. Whether you’re a data science enthusiast, urban planner, or just curious about how city transportation works, this project offers a clear, interactive way to understand a real-world metro system.

---

##  Why This Project?

Cities are growing rapidly, and public transportation is key to reducing traffic, pollution, and travel time. A metro system like **Delhi Metro** carries millions of passengers daily. But have you ever wondered:
- How has the metro network grown over the years?
- Are stations evenly spaced?
- Which lines are longest or most dense?
- How many stations are underground vs elevated?

This project answers these questions using **data analysis** and **visualizations** to make sense of the Delhi Metro's structure and development.

---

##  Project Objectives

1. **Understand the spatial distribution** of metro stations.
2. **Track the historical growth** of the network over the years.
3. **Compare metro lines** in terms of number of stations and distances.
4. **Analyze station layouts** – underground, elevated, or ground level.

---

##  The Dataset

The dataset used is a CSV file named `Delhi Metro Network.csv`, which includes:

| Column              | Description                                         |
|---------------------|-----------------------------------------------------|
| Station Name        | Name of the metro station                           |
| Line                | The metro line the station belongs to               |
| Latitude & Longitude| Geographical coordinates for mapping                |
| Opening Date        | The date when the station started operating         |
| Distance from Start | Distance from the starting station of the line (km)|
| Station Layout      | Whether the station is Elevated, Underground, etc. |

This dataset provides all the necessary information to perform spatial, temporal, and structural analysis.

---

## 🛠Tools & Libraries

We use the following Python libraries:

- `pandas` – to load and manipulate data
- `folium` – to create interactive maps showing station locations
- `plotly` – to make interactive charts and graphs
- `datetime` – to handle and convert date information

These tools allow us to turn raw data into meaningful visual insights.

---

##  What You'll See in This Project

### 1. **Geographical Map of Stations**
Using **Folium**, we plot each station on a live interactive map with color-coded lines. Hovering over a marker shows the station name and line. This helps visualize how well-distributed stations are across the city.

### 2.  **Time-Series Growth Analysis**
We analyze how many stations opened each year. A bar chart shows key expansion periods. For example:
- Some years have major spikes (network expansion).
- Other years have slowdowns (construction or planning delays).

### 3.  **Metro Line Analysis**
We calculate:
- The total number of stations per line.
- The average distance between two consecutive stations.

This helps us answer:
- Which line is the longest?
- Which line is the most densely packed?

### 4. **Station Layout Analysis**
Metro stations can be:
- **Elevated** (built on flyovers)
- **Underground** (below the surface)
- **At-grade** (at ground level)

A bar chart shows how many stations fall into each category. We observe:
- Most stations are elevated (cheaper and quicker to build).
- Underground stations are fewer (mostly in central areas).

---

## Sample Visualizations

- 🗺️ Interactive Metro Station Map
- 📊 Bar chart showing number of stations opened by year
- 📉 Comparison of metro lines (station count vs. spacing)
- 🏗️ Station layout type distribution

All visuals are **interactive** and provide deeper insights into how the Delhi Metro functions.

---

