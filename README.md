# Bundesliga Data Explorer (Python)

This interactive data analysis project is built using Python, leveraging the OpenLigaDB API to explore and visualize football data from the 1st, 2nd, and 3rd German Bundesliga leagues. It demonstrates the ability to combine real-time API integration, interactive widgets, statistical analysis, and geospatial visualization in a clear and user-focused interface.

## Technologies Used
- Python 3.11
- Jupyter Notebook
- requests, matplotlib, folium, ipywidgets, pandas

## Key Features

### 1. Interactive League Statistics Viewer
Users can:
- Select league and season (2008–2024)
- Choose key metrics such as points, goals, or match outcomes
- View bar charts with average value reference lines
- Identify teams that significantly over- or underperform using statistical thresholds

### 2. Matchday Result Analyzer
- Select a team and matchday (1–34)
- View full match information including:
  - Home and away teams with official logos
  - Final score
  - Visual indicator for win, loss, or draw

All data is dynamically fetched and displayed in a clean, readable layout.

### 3. Geospatial Team Map and Comparison Tool
- Map of all Bundesliga teams based on geographic location
- Custom team icons with interactive popups showing match statistics
- Side-by-side comparison of any two teams based on number of matches won

## Project Highlights
- Real-time API data fetching and parsing
- Statistical evaluation using standard deviation
- Fully interactive frontend with ipywidgets and Folium maps
- Modular code structure and reusable components

This project reflects practical data science and software engineering skills and is designed with clarity, extensibility, and user interaction in mind.
