# QGIS Terrain and Network Analysis Project

This repository contains the implementation and analysis of a **Remote Sensing and GIS internship project** performed using **QGIS**.  
The project focuses on **terrain analysis using DEM data** and **network analysis for police station accessibility** using OpenStreetMap datasets.

---

# Project Overview

Geographic Information Systems (GIS) and Remote Sensing enable spatial analysis of geographic data for decision-making and planning.

In this project, the following analyses were performed:

• Terrain analysis using **SRTM Digital Elevation Model (DEM)**  
• Generation of **Hillshade, Slope, Aspect, and Contours**  
• **Shortest Path Analysis** using road network data  
• **Service Area Analysis** for police stations using GIS network analysis  

The project demonstrates how GIS can support **urban planning, emergency service accessibility analysis, and infrastructure planning**.

---

# Tools and Technologies

| Tool | Purpose |
|-----|------|
| QGIS 3.40 | Spatial analysis and visualization |
| OpenStreetMap | Road network, buildings, POI datasets |
| SRTM DEM | Elevation data for terrain analysis |

QGIS is an open-source geographic information system that allows users to analyze and visualize spatial datasets. :contentReference[oaicite:1]{index=1}

---

# Dataset Used

1. **SRTM DEM Data** – elevation raster dataset  
2. **OpenStreetMap Road Network** – transportation network  
3. **Police Station Locations** – point dataset  
4. **Building Footprints** – urban infrastructure data  
5. **Points of Interest (POI)** – public facility locations  

---

# Methodology

The workflow followed in this project:

### 1 Data Collection
Spatial datasets were collected from **OpenStreetMap and SRTM sources** and imported into QGIS.

### 2 DEM Processing
The DEM raster dataset was processed to derive terrain characteristics.

### 3 Terrain Analysis
Generated terrain derivatives:

- Hillshade Map
- Slope Map
- Aspect Map
- Contour Lines

These layers help understand terrain morphology and elevation variation.

### 4 Network Analysis

Two types of network analysis were performed:

**Shortest Path Analysis**

- Determines the optimal route between two locations.

**Police Station Service Area Analysis**

- Identifies reachable areas from police stations using road networks.

### 5 Visualization
All spatial layers were visualized within QGIS to interpret terrain features and accessibility patterns.

---

# Results

Key outcomes of the analysis:

• Hillshade visualization improved terrain interpretation  
• Slope and aspect maps provided terrain orientation and steepness  
• Contour lines represented elevation variation across the study area  
• Shortest path analysis identified optimal travel routes  
• Service area analysis evaluated police station accessibility coverage  

These analyses demonstrate the practical applications of **GIS for emergency infrastructure planning and spatial decision-making**.

---

# Repository Contents
