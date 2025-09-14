---
title: "Peatland Breathing: Murnauer Moos"
categories: ["Geospatial", "Remote Sensing", "Environmental Monitoring"]
image: ../../images/peatlands.png
description: Multi-source remote sensing and rainfall data for monthly peatland ecosystem monitoring in 2024.
---

<a href="https://github.com/fyeqaa/Peatland-breathing.git" target="_blank">
  <button style="background-color:#24292e; color:white; padding:8px 16px; border:none; border-radius:5px; cursor:pointer;">
    View on GitHub
  </button>
</a>

### Project Overview

Peatlands are vital carbon sinks, storing more carbon than all the world’s forests combined—but their stability is sensitive to water level changes.
The surface “breathing” of peatlands, observed through remote sensing, is a strong proxy for ecosystem health and CO₂ release, making large-scale monitoring essential for climate action.

In this project, I developed a monthly monitoring framework for the temperate peatland ecosystem of Murnauer Moos in 2024. By integrating multi-source remote sensing datasets and climate variables—including Sentinel-1 SAR radar, Sentinel-2 NDVI, and rainfall data,I tracked vegetation and moisture dynamics to assess peatland ecosystem health and environmental responses.


#### Data Sources

- Sentinel-1 SAR (COPERNICUS/S1_GRD) 
- Sentinel-2 (COPERNICUS/S2_SR_HARMONIZED)
- Rainfall (UCSB-CHG/CHIRPS/DAILY)  

#### Methodology

- **Study Area**: The Murnauer Moos peatland, a key temperate wetland ecosystem.
- **Sentinel-1 Processing**: Computation of VH/VV backscatter ratio to track surface water and vegetation moisture content.
- **Sentinel-2 Processing**: NDVI calculation from harmonized surface reflectance to monitor vegetation health.
- **Rainfall Data**: Aggregated from daily to monthly scale to capture precipitation patterns affecting the peatland.
- **Time Series Analysis**: Monthly aggregation and alignment of all variables to facilitate integrated temporal analysis.

#### Results

The VH/VV ratio increases with higher rainfall, indicating enhanced peat surface wetness. Conversely, as vegetation greenness (NDVI) rises during summer, the ratio declines, suggesting canopy growth dampens the radar signal. This highlights the coupled influence of rainfall and vegetation on peatland “breathing” dynamics in Murnauer Moos


![Monthly Plot](../../images//Monthly_plot.png) 


#### Future Work

- **InSAR Displacement Monitoring**: Incorporate Interferometric Synthetic Aperture Radar (InSAR) to measure peatland surface displacement and subsidence, enhancing understanding of ground stability and deformation processes.
- **Water Table Integration**: Combine water table level measurements or groundwater models to better link hydrological conditions with vegetation and surface dynamics.



