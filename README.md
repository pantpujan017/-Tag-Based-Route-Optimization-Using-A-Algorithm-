
# 🏔️ Nepal Travel Path Finder

An intelligent travel planning system that finds optimal routes across Nepal using A* pathfinding and recommends places based on your interests.

## Features

- **Multi-route options** — Get top 3 alternative paths between any two cities
- **Tag-based recommendations** — Filter places by interests (temples, trekking, wildlife, etc.)
- **Interactive maps** — Visualize routes with Folium + OSRM real-road distances
- **Detour planning** — Select places to visit and see updated route distances

## Tech Stack

| Component | Technology |
|-----------|------------|
| Frontend | Streamlit |
| Pathfinding | Dijkstra + A* Algorithm |
| Maps | Folium + OSRM API |
| Data | Pandas, GeoPandas |

## Setup

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Requirements

```
streamlit
pandas
folium
geopandas
osmnx
requests
numpy
geopy
shapely
```

## Data

- `cleanPlaceWithDistanceheadquater.csv` — Places with coordinates, tags, and district info
- 24 districts with weighted road distances between them

## Usage

1. Select start and destination cities
2. Choose interest tags
3. Click **"Find Best Travel Paths"**
4. Explore routes, maps, and place recommendations across 5 tabs
