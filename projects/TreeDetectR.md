# TreeDetectR

Detecting and segmenting individual urban trees from LiDAR point cloud data using R.


## Overview

**TreeDetectR** is an R package designed to process LiDAR point cloud data for the detection and segmentation of individual trees in urban environments. It supports ground classification, canopy height modeling, tree top detection, tree segmentation, and exporting spatial tree coordinates.

This package is built for researchers, urban ecologists, GIS professionals, and data scientists working with 3D spatial data.

---

## 🚀 Features

- Ground classification using Cloth Simulation Filter (CSF)
- Digital Terrain Model (DTM) and Canopy Height Model (CHM) generation
- Tree top detection using Local Maximum Filtering (LMF)
- Tree segmentation with Dalponte2016 algorithm
- Export coordinates of detected trees (X, Y, Z, Latitude, Longitude)
-  Simple integration with `lidR`, `terra`, `sf`, `raster`, and `RCSF` packages

---

## Project Repository

👉 [View Full Project on GitHub](https://github.com/fyeqaa/TreeDetectR)
