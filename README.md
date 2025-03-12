### Leaflet Earthquake Viaualization 

#Project Structure 
This project leverages the Leaflet.js library to create an interactive map displaying real-time earthquake data. The data is sourced from the USGS GeoJSON feed, and features such as popups, color-coded markers, and a legend have been incorporated to enhance user experience and data interpretation.
Files and Structure

# Project Structure

📂 Project Directory ├── index.html # Main HTML file containing the Leaflet map ├── style.css # CSS file for styling the map and legend ├── logic.js # JavaScript file for data fetching and visualization logic └── static/ ├── css/style.css # Styling for the webpage └── js/logic.js # JavaScript logic for Leaflet map

#Technologies Used
> * Leaflet.js – Interactive mapping library
> * D3.js – Data-driven visualization
> * HTML5 & CSS3 – Web structure and styling
> * JavaScript (ES6) – Fetching and processing earthquake data

# Features

> * Interactive Map: Displays earthquake locations using Leaflet.js

> * Real-time Data: Retrieves earthquake data from USGS GeoJSON feed

> * Color-Coded Markers: Represent earthquake magnitude and depth

> * Popups: Provide details on each earthquake

> * Legend: Helps users interpret the color-coded depth markers

> * Installation & Usage

Clone the repository:

git clone https://github.com/your-repository/leaflet-earthquake.git 

* Navigate to the project folder:

1. cd leaflet-earthquake. 
2. Open index.html in a browser to view the interactive map.
3. Data Source.
4. The earthquake data is retrieved from the USGS GeoJSON Feed: https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php

*Future Enhancements: 

1. Future Enhancements.

2. Implement tectonic plate overlay for better geological context.

3. Add timeline filtering to visualize earthquakes over time.

4. Improve UI with additional styling and animations.

5. License.

6. This project is open-source and available under the MIT License.
