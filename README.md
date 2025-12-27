# 🛰️ Urbanization Monitoring – Anuradhapura, Sri Lanka (2015–2025)

Satellite-based urban growth analysis using Landsat imagery and geospatial data science techniques to monitor urban expansion, vegetation change, and future development potential in Anuradhapura District, Sri Lanka.

## 📌 Project Description

This project analyzes urbanization trends from 2015 to 2025 in Anuradhapura District using Landsat 8 satellite imagery.
It focuses on detecting urban growth, evaluating land cover and vegetation changes, and identifying potential future development zones to support sustainable urban planning and environmental management.

The study combines remote sensing, GIS, and time-series analysis using Python.

## 🎯 Key Objectives
Monitor spatial and temporal urban expansion (2015–2025)
Detect urban land cover changes using spectral indices
Analyze vegetation trends using NDVI
Perform change detection between baseline and endpoint years
Identify potential future urban growth areas
Generate maps, graphs, and analytical visual outputs

## 📍 Study Area
Location: Anuradhapura District, North Central Province, Sri Lanka
Significance: UNESCO World Heritage region
Climate: Dry zone
Key Activities: Agriculture, tourism, administration

## 🛰️ Data Sources
### Satellite Imagery
>Source: USGS EarthExplorer

>Satellite: Landsat 8

>Product: Collection 2 – Level 2 Surface Reflectance

>Spatial Resolution: 30 m

>Temporal Coverage: 2015–2025

>Scenes Used: 100+ (multi-temporal)

### Ancillary Data
>Administrative boundaries from GADM
>Visual validation using Google Earth

## ⚙️ Methodology (Overview)
### Data Preprocessing
>Scene selection (cloud & season control)
>Band selection
>Atmospheric correction
>Image clipping to AOI
>Reprojection and alignment

### Spectral Index Analysis
>NDVI – vegetation health
>NDBI – built-up area detection
>Threshold-based urban classification

### Temporal Analysis
>Annual & monthly urban extent calculation
>Growth rate and seasonal pattern analysis

### Change Detection
>Pixel-wise comparison (2015 vs 2025)
>Same-season comparison to reduce false change

### Vegetation & Land Cover Analysis
>NDVI trend analysis
>Estimation of land-use conversion

### Potential Growth Area Mapping
>Multi-criteria suitability analysis
>Weighted overlay classification (5 zones)

### Predictive Modeling
>ARIMA
>Prophet
>Random Forest Regression
>Urban growth projection (2026–2030)

## 🛠️ Tech Stack
### Programming
Python 3.8+
Jupyter Notebook

### Libraries 
rasterio,geopandas, numpy, pandas, matplotlib, seaborn, plotly, scipy

### Data Formats
>GeoTIFF – raster outputs
>CSV – statistical data
> GeoJSON – vector boundaries


## 📊 Key Findings (Summary)
Urban area increased from ~35.30 km² (2015) to ~36.94 km² (2025)
Net urban growth of ~1.64 km²
Expansion concentrated along major transport corridors
District-wide vegetation improved (NDVI: 0.18 → 0.29)
Agricultural land was the main contributor to urban expansion
High-potential future growth zones identified near existing infrastructure

## ⚠️ Limitations
30 m resolution limits small-scale urban feature detection
No ground-truth accuracy assessment
Predictive models based only on historical trends

### 🔮 Future Improvements

High-resolution imagery integration
Inclusion of socio-economic data
Urban heat island and flood risk analysis
Automated monitoring dashboard


## 📚 References

Key references include NDVI/NDBI foundational studies, USGS Landsat documentation, and Sri Lankan urban planning resources.
(See full reference list in the project report.)

