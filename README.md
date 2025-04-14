# Time-Series-Analysis-using-ARIMA

# Time Series NDVI Analysis Using ARIMA – Debrigarh Wildlife Sanctuary

This project demonstrates how to analyze vegetation trends over time using the **ARIMA model** on **NDVI time series** derived from **Landsat imagery**. The study focuses on **Debrigarh Wildlife Sanctuary**, Odisha, India.


## Study Area

The shapefile for **Debrigarh Wildlife Sanctuary** is included in the `boundary/` folder.

- **Format**: ESRI Shapefile
- **CRS**: WGS 84 (EPSG:4326)


## Remote Sensing Data

**Data Source**: [USGS EarthExplorer](https://earthexplorer.usgs.gov/)

- **Sensor**: Landsat 8 OLI/TIRS or Landsat 5/7 depending on year
- **Temporal Coverage**: 2015–2025
- **Spatial Resolution**: 30 meters
- **Bands used for NDVI**:
  - **Red**: Band 4 (Landsat 8)
  - **NIR**: Band 5 (Landsat 8)


## 📈 NDVI Calculation

NDVI (Normalized Difference Vegetation Index) is computed using:

NDVI = (NIR - Red) / (NIR + Red)

