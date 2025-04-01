# Landslide-Detection
Satellite Based Landslide Detection
This repository contains a deep learning-based solution for detecting landslides using Sentinel-2 satellite imagery, with data acquisition facilitated by the Google Earth Engine (GEE) API. We leverage the U-Net architecture, a convolutional neural network optimized for image segmentation, to identify and delineate landslide regions in high-resolution satellite images.

Key Features:
Data Source: Utilizes Sentinel-2 imagery downloaded via the Google Earth Engine API, providing multi-spectral data for accurate environmental analysis.
Model: Implements a U-Net model with TensorFlow/Keras for semantic segmentation, trained to distinguish landslide areas from surrounding terrain.
Pipeline:
Downloads and preprocesses Sentinel-2 .tif images using the GEE API.
Trains the U-Net model on labeled datasets to predict landslide boundaries.
Converts model predictions into geospatial polygons for further analysis (e.g., GIS integration).
Output: Generates predicted masks as .tif files and converts them into GeoJSON polygons for mapping and visualization.
Tools: Uses libraries such as TensorFlow, rasterio, OpenCV, GeoPandas, numpy, matplotlib, scikit-learn, and the Google Earth Engine API for data retrieval and processing.

