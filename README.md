# MAST30034_Project1
First mast30000000000034 project i loose 5% of my hair for 0.0007 R^2 value for final model

### Project Overview
Investigates how weather and location affect fare per minute in New York City.

### Repo Struct
MAST30034_Project1/
├── data/                         # Raw and processed datasets (weather, taxi trips, zone shapefiles)
├── Project1.ipynb                # Main Jupyter Notebook containing all analysis and modelling
├── README.md                     # Project documentation and overview
├── .gitattributes                # Git configuration for file handling
├── fare_amount_skew.png           # Distribution of fare amount
├── fare_per_min_-nego.png          # Map including negotiated fares
├── fare_per_min_-nego_log.png      # Log-scaled version of negotiated fare map
├── fare_per_min_nego.png          # Map excluding negotiated fares
├── fare_vs_severity.png           # Average fare per minute by weather severity
├── foliumChoroplethMap.html       # Interactive geospatial map (Folium)
├── trip_distance_skew.png         # Distribution of trip distance
├── trip_duration_skew.png         # Distribution of trip duration

### How to Run
1. Install some packages - something like this
pip3 install pyspark pandas matplotlib folium

2. Download or clone the repository

3. Open the folder in VS Code or similar (I used VS Code)

4. Launch Project1.ipynb

5. Run all cells sequentially (Kernel → Restart & Run All)

Note: All PNG files were saved manually but should be visible after running, except the geopandas maps; only the code for the final map with logged legend and removed negotiations is available
