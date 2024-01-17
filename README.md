# Optimization Project Map Script

## Overview
This Python script is designed for an optimization project that requires visualizing a sequence of locations on a map. It utilizes the power of `pandas`, `geopandas`, and `folium` libraries to create an interactive map.

## Features
- **Data Handling**: Loads location data (latitude and longitude) and time information into a DataFrame.
- **Geospatial Conversion**: Converts the DataFrame into a GeoDataFrame for spatial analysis.
- **Interactive Map Creation**: Generates an interactive map using Folium centered around the initial data point.
- **Data Visualization**: Places markers on the map for each location, labeled with location ID and time information.
- **Route Visualization**: Connects the locations with a polyline to visualize the route.

## Requirements
- pandas
- geopandas
- folium

## Usage
1. **Prepare Your Data**: Ensure your data contains fields for 'Location', 'Time', 'Latitude', and 'Longitude'.
2. **Run the Script**: Execute the script to generate the map.
3. **View the Map**: Open the generated `map.html` file in a web browser to view the interactive map.

## Example Data Structure
```python
data = {
    'Location': [1, 7, 4, 3, 6, 5, 8],
    'Time': ['5:23PM', '5:57PM', '6:46PM', '7:07PM', '7:24PM', '7:41PM', '8:00PM'],
    'Latitude': [43.4672, 43.5066, 43.4427, 43.4465, 43.4386, 43.4479, 43.4807],
    'Longitude': [-80.4934, -80.5191, -80.54, -80.5084, -80.4855, -80.4641, -80.5656]
}
```
## Output
An HTML file (map.html) containing an interactive map.
![image](https://github.com/agishan/MSCI331_Map_Drone_Delivery/assets/54005039/cd364e42-17ca-479f-8184-f05b39ee6ee4)

#### Note
The script is customizable based on the specific needs of your project. You can modify the data structure, map settings, and visualization style as needed.
