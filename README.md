# 🚇 NYC Public Transit Ridership — Data Visualization & Analysis

An exploratory data analysis and visualization project examining New York City's public transit ridership patterns using real-world MTA datasets. The project uncovers temporal trends, spatial distributions, commuter behavior, payment adoption, and post-COVID recovery across NYC's transit network.

---

## 📌 About the Project

This project analyzes ridership data from New York City's Metropolitan Transportation Authority (MTA), covering multiple transit modes including Subway, Bus, LIRR, Metro-North Railroad (MNR), and Staten Island Railway (SIR). The analysis spans from March 2020 to May 2026, with a focused look at 2026 trends and the long-term impact of the COVID-19 pandemic on public transit usage.

---

## 📊 Datasets

Three publicly available datasets from the [MTA Open Data Portal](https://data.ny.gov/) were used:

| Dataset | Description | Size |
|---------|-------------|------|
| **Daily Ridership Data** | Daily aggregate ridership across 9 transit modes (Mar 2020 – May 2026) | ~16,781 rows |
| **Hourly Station-Level Data** | Hourly entry/exit counts for 400+ subway stations | ~1,000,000 rows |
| **Subway Station Geolocation** | Latitude/longitude coordinates for 496 subway stations | 496 rows |

All datasets are published under an open data license by the MTA and are freely available for academic and non-commercial use.

---

## 📈 Visualizations

The project produces the following visualizations:

1. **Daily Ridership by Transit Mode** — Stacked area chart showing Subway, Bus, LIRR, MNR, and SIR usage over time
2. **Weekday vs Weekend Comparison** — Grouped bar chart comparing average ridership across transit modes
3. **Ridership Heatmap** — Hour × Day-of-Week heatmap revealing peak commute patterns
4. **Hourly Ridership Curve** — Weekday vs weekend hourly ridership profile (dual-peak M-shape vs single hump)
5. **Top 20 Busiest Stations** — Horizontal bar chart of highest-traffic subway stations
6. **Borough-Level Analysis** — Pie charts showing ridership distribution and per-station averages by borough
7. **Interactive Subway Map** — Folium-based geographic heatmap of station-level ridership across NYC
8. **Payment Method Breakdown** — Pie chart showing OMNY vs MetroCard adoption
9. **COVID-19 Recovery Timeline** — Monthly average subway ridership from 2020 to 2026
10. **Day-of-Week Ridership** — Bar chart of average subway ridership by day of the week

---

## 🔍 Key Insights

- **Subway dominance**: The subway carries over 60% of all NYC transit ridership, peaking at ~4.3M riders on Wednesdays
- **Commuter dual-peak**: Weekday ridership shows a classic M-shaped curve — morning peak at 8 AM, stronger evening peak at 5 PM
- **Station concentration**: Times Square–42 St leads with 2M+ total riders; the top 20 stations are concentrated in Midtown Manhattan
- **Borough disparity**: Manhattan accounts for 55.7% of ridership; Staten Island and the Bronx record the lowest per-station averages
- **OMNY adoption**: Contactless OMNY payments now handle 97.2% of all fare transactions, with MetroCard at just 2.8%
- **Post-COVID recovery**: Ridership plummeted from ~2.4M to ~400K in April 2020, gradually recovering to ~3.9M by early 2026

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas** & **NumPy** — Data wrangling and aggregation
- **Matplotlib** & **Seaborn** — Static visualizations (charts, heatmaps)
- **Plotly** — Interactive charts
- **Folium** — Interactive geographic maps

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/nyc-transit-data-visualization.git
   cd nyc-transit-data-visualization
   ```

2. Install the required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly folium
   ```

3. Place the dataset CSV files in the `data/` folder

4. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook Data_Visualization.ipynb
   ```

---

## 📂 Project Structure

```
nyc-transit-data-visualization/
├── README.md
├── Data_Visualization.ipynb      # Main analysis notebook
├── data/
│   ├── daily_rides.csv           # Daily aggregate ridership
│   ├── hourly_rides.csv          # Hourly station-level data
│   └── subway_stations.csv       # Station geolocation data
└── images/
    └── *.png                     # Exported visualization images
```

---

## 📝 License

This project is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).

You are free to share and adapt this work, as long as you give appropriate credit and distribute any derivative work under the same license.

The MTA datasets are published under an open data license by the Metropolitan Transportation Authority of New York City.

---

## 👤 Author

**Khurram Shahzad**
Matricola: 950051
MS Data Science — University of Milano-Bicocca, Milan, Italy
📧 k.shahzad8@campus.unimib.it

**Course:** Data Visualization (2526-1-FDS02Q001-FDS02Q00102) — Academic Year 2025–2026
**Professor:** Prof. Andrea Nelson Mauro (andrea.mauro@unimib.it)

---
