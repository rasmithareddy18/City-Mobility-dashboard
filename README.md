# City-Mobility-dashboard
A Python-based spatial dashboard analyzing Hyderabad’s mobility. It maps bus stops, calculates road lengths per GHMC ward, and visualizes infrastructure gaps using OpenStreetMap and KML data. Built with GeoPandas, OSMnx, and Folium for urban planning insights.
# 🚦 City Mobility Dashboard: Hyderabad

A spatial data dashboard that explores public transport access and road infrastructure across Hyderabad using open data.

## 📍 Features

This dashboard visualizes:

- 🚌 **Bus Stop Distribution** (from OpenStreetMap)
- 🛣️ **Road Network Coverage**
- 📏 **Total Road Length per Ward** (GHMC)

## 📊 Data Sources

- 🗺️ **OpenStreetMap** (via OSMnx for roads & bus stops)
- 🧭 **GHMC Ward Boundaries** (KML file manually downloaded)

## 🛠️ Tools & Libraries

- Python
- GeoPandas
- Folium (for interactive mapping)
- OSMnx (for spatial data download and analysis)
- Pandas

## 🧠 Key Insights

- 🟢 **Bus Stop Density**: Sparse in peripheral zones, dense in city core.
- ⚫ **Road Density**: Wards in central Hyderabad have more connected roads.
- 🚧 **Ward Disparities**: Some wards have far more infrastructure than others.

## 📈 Possible Extensions

- 🚇 Add metro station data from OSM
- 🚶 Buffer zones to analyze walkability to transit
- 🚦 Add traffic congestion layers using external data (if available)
- 🧭 Create mobility inequality scores across wards

---

## 📂 Folder Structure

City_mobility_dashboard_hyderabad/
│
├── data/
│ ├── ghmc-wards.kml
│ ├── bus_stops.geojson
│ └── road_network.graphml
│
├── City_Mobility_Dashboard.ipynb
├── README.md
└── requirements.txt # Optional, can list osmnx, geopandas, folium etc.
