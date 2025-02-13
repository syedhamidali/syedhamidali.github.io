---
title: 'Temperature Analysis Above 3000m Using DEM and ERA5 Land Data'
date: 2024-03-04
author: 'Hamid Ali Syed'
permalink: /posts/2024/03/fun-with-DEM-ERA5.md/
tags:
  - DEM
  - ERA5
  - Python Visualization
  - python
---

# Temperature Analysis Above 3000m in Jammu, Kashmir, and Ladakh (JKL)

- **By:** Hamid Ali Syed
- **Contact:** windcirculation[at]gmail[dot]com

## Analyzing High-Altitude Temperatures Using Digital Elevation Models and Climate Data

### Project Overview

This mini project delves into an innovative application of Digital Elevation Models (SRTM data) and ERA5 land data to explore temperatures above 3000 meters in the diverse terrains of Jammu, Kashmir, and Ladakh. Contrary to correlating elevation with temperature, our focus is on pinpointing and visualizing temperatures at elevations above 3000 meters, showcasing how DEM data complements surface-level climate data for targeted geospatial analysis.

### The Process

1. **Elevation Data Retrieval**: We use the Shuttle Radar Topography Mission (SRTM) data to obtain detailed elevation information.
2. **Climate Data Acquisition**: ERA5 land data provides us with surface temperature readings across our area of interest.
3. **Data Matching and Masking**: Key techniques include using shapefiles to mask data outside our geographic focus and matching the resolution of the DEM and ERA5 datasets for accurate analysis.
4. **Visualization**: Employing Python and its powerful libraries (`matplotlib`, `geopandas`), we plot temperatures for areas above 3000 meters elevation, providing clear, insightful visual representations of our findings.

### Notebook
[Click Here](https://syedha.com/JKL_DEM/JKL_DEM_ERA5.html)

### Learning Outcomes

Participants will learn how to:
- Integrate DEM with climate data for specialized geospatial queries.
- Apply data masking with shapefiles to focus analysis on specific regions.
- Adjust dataset resolutions to align disparate data sources.
- Employ Python for effective data visualization and geospatial analysis.

This project is a practical guide for students, data enthusiasts, and professionals looking to enhance their skills in environmental data analysis and geospatial visualization.

Join us in this analytical journey to unveil the climatic conditions of high-altitude terrains through the lens of data science.

Warm regards,

*Hamid Ali Syed*


[Notebook](https://syedha.com/JKL_DEM/JKL_DEM_ERA5.html)

### References

- Farr, T. G., & Kobrick, M. (2000). Shuttle Radar Topography Mission produces a wealth of data. *Eos, Transactions American Geophysical Union*, 81(48), 583-585.
- Muñoz-Sabater, J., Dutra, E., Agustí-Panareda, A., Albergel, C., Arduini, G., Balsamo, G., Boussetta, S., Choulga, M., Harrigan, S., Hersbach, H., et al. (2021). ERA5-Land: A state-of-the-art global reanalysis dataset for land applications. *Earth System Science Data*, 13(9), 4349-4383.

---