# Mapping_Earthquakes
## Project Overview
Building an interactive map for the Disaster Reporting Network--a non-profit company that provides data-driven storytelling on disasters around the world--that shows the magnitude of all global reported earthquakes over the past 7 days in relation to fault lines and tectonic plates.

## Resources
- Data Sources:
  1. Recent Earthquake data: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
  2. Major Earthquake data (4.5+ magnitude): https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson
  3. Tectonic Plate data: https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json
  
- Software: JavaScript vES6+, Bootstrap v5.2.3, CSS v3, VS Code v1.73.1

## Summary
This interactive map is updated whenever it requests the most recent weekly data from the U.S. Geological Survey Earthquake Hazards Program. It contains three different map views with three different overlays and a legend that indicates the magnitude of the earthquakes:
1. A street view map--shown with the tectonic plates and all earthquakes overlays--which indicates that most of the earthquakes that occured in the United States in the past week were on the West Coast, near the San Andreas fault line.

<img src="https://github.com/Jay-ni13/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/streets_map.png" width=95%>

2. A satellite view map--shown with the tectonic plates and all earthquakes overlays--that depicts a cluster of earthquakes in Hawai'i in the last week, possibly related to the ongoing eruption within Halema'uma'u crater.

<img src="https://github.com/Jay-ni13/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/satellite_map.png" width=95%>

3. A night navigation view map--shown with all three overlays: earthquakes, major earthquakes, and tectonic plates--pinpoints the only earthquake from the past week with a magnitude greater than 6, which occured on 12/14/2022 at approx. 12:40pm in the Rat Islands/Aleutian Islands with a magnitude of 6.3 on the Richter scale.

<img src="https://github.com/Jay-ni13/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/night_navigation_map.png" width=95%>
