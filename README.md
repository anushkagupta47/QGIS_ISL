# Remote Sensing and GIS Terrain & Network Analysis using QGIS

This project demonstrates terrain analysis and road network analysis using QGIS. 
SRTM Digital Elevation Model (DEM) data was used to generate terrain derivatives 
such as hillshade, slope, aspect, and contour maps to understand elevation and 
surface characteristics of the study area. OpenStreetMap datasets including roads, 
buildings, police stations, and points of interest were integrated to perform 
spatial and network analysis.

The project further applies QGIS network analysis tools to determine the shortest 
path between locations and evaluate the service coverage area of police stations. 
The results highlight how GIS techniques can support terrain modeling, spatial 
analysis, and accessibility assessment for urban planning and emergency services.


---

# Project Overview

Geographic Information Systems (GIS) and Remote Sensing provide powerful tools for analyzing spatial data and supporting decision-making.

In this project, multiple spatial analyses were performed using **QGIS**, including terrain analysis and road network analysis.

The key analyses performed in this project include:

- Terrain analysis using **SRTM Digital Elevation Model (DEM)**
- Generation of **Hillshade, Slope, Aspect, and Contours**
- **Shortest Path Analysis** using road network data
- **Service Area Analysis** for police stations

These analyses demonstrate how GIS techniques can support **urban planning, infrastructure management, and emergency service accessibility analysis**.

---

## Key Insights

- Terrain analysis was performed using **SRTM Digital Elevation Model (DEM)** to understand elevation patterns of the study region.
- Derived terrain products including **Hillshade, Slope, and Aspect maps** to analyze surface characteristics.
- Generated **Contour Lines** to represent elevation changes and terrain gradients.
- Conducted **Shortest Path Network Analysis** on the road network to determine the optimal route between locations.
- Performed **Service Area Analysis** to evaluate the accessibility of police stations across the study region.
- Integrated **OpenStreetMap datasets** including roads, buildings, police stations, and points of interest to support spatial analysis.
- The project demonstrates how **QGIS can be used for terrain modeling and urban accessibility analysis**.

---

# Tools and Technologies

- **QGIS 3.40**
- **OpenStreetMap (OSM) datasets**
- **SRTM Digital Elevation Model (DEM)**

QGIS was used to perform raster analysis, vector analysis, and network analysis.

---

# Datasets Used

The project uses the following datasets:

| Dataset | Description | Source |
|-------|-------------|------|
| DEM Data | Elevation raster dataset | SRTM |
| Road Network | Transportation network | OpenStreetMap |
| Police Stations | Location of police stations | OpenStreetMap |
| Buildings | Building footprints | OpenStreetMap |
| Points of Interest | Public facility locations | OpenStreetMap |

Due to large file size, the datasets are not included in this repository.  
They can be downloaded from the following sources:

OpenStreetMap Data  
https://download.geofabrik.de/

SRTM DEM  
https://earthexplorer.usgs.gov/

---

# Methodology

The workflow followed in this project includes the following steps:

### 1. Data Collection
Spatial datasets including DEM data, road networks, buildings, police stations, and points of interest were collected from OpenStreetMap and SRTM sources.

### 2. DEM Processing
The DEM raster dataset was imported into QGIS and processed using terrain analysis tools.

### 3. Terrain Analysis
The following terrain derivatives were generated:

- Hillshade Map
- Slope Map
- Aspect Map
- Contour Lines

These layers help understand terrain morphology and elevation patterns.

### 4. Network Analysis

Two types of network analysis were performed:

**Shortest Path Analysis**

This analysis determines the most efficient route between two locations using the road network.

**Police Station Service Area Analysis**

This analysis identifies areas reachable from police stations using the road network and helps evaluate accessibility coverage.

### 5. Visualization

All generated spatial layers were visualized in QGIS to analyze terrain characteristics and accessibility patterns.

---

# Results

Key outcomes of the analysis include:

- Hillshade visualization improves terrain interpretation
- Slope and aspect maps represent terrain steepness and orientation
- Contour lines visualize elevation variation
- Shortest path analysis identifies optimal travel routes
- Service area analysis evaluates police station coverage and accessibility

These results demonstrate the usefulness of GIS in **urban planning and emergency infrastructure planning**.

---

## Project Outputs

### Slope Map
![Slope Map](SRTM%20.png)

### Hillshade Map
![Hillshade](hillshade.png)

### Aspect Map
![Aspect Map](Aspect%20.png)

### Contour Lines
![Contours](Contours.png)

### Shortest Path Analysis
![Shortest Path](Shortest%20path.png)

### Police Service Area
![Service Area](Service%20Area%20.png)

---

# Repository Structure

QGIS_ISL
│
├── README.md
├── Remote_Sensing_GIS_Project.qgz
├── readme.txt
├── srtm_52_05.hdr
├── srtm_52_05.tfw
├── hillshade.png
├── SRTM .png
├── Aspect .png
├── Contours.png
├── Shortest path.png
└── Service Area .png

---

# Author

**Anushka Gupta**

B.Tech – Computer Science & Artificial Intelligence  
Babu Banarasi Das University  

Technical Intern – India Space Lab  
Chairperson – IEEE Student Branch  

GitHub  
https://github.com/anushkagupta47

---

# License

This project is created for **academic and educational purposes** as part of a Remote Sensing and GIS internship project.

# Repository Structure
