# Near-Time GIS for Flood Monitoring and Analysis in Niger River Basin, Nigeria
This repository hosts the resources, code, and documentation for the study **"Enhancing Disaster Response and Resilience Through Near-Time GIS for Flood Monitoring and Analysis in Niger River Basin, Nigeria"**, as presented at the ISPRS TC III Mid-term Symposium, 2024.

### Overview
Flooding in Nigeria is a critical issue affecting lives, livelihoods, and infrastructure, particularly in the Niger River Basin. This project leverages Google Earth Engine (GEE) for near-real-time flood mapping, impact analysis, and flood resilience modeling. It combines multi-temporal remote sensing datasets with geospatial analysis techniques to quantify flood hazards, assess exposure, and provide actionable insights for disaster response.

### Key Features
- **Automated Flood Monitoring**: Utilizes Sentinel-2 and Sentinel-1 datasets for accurate and timely flood mapping.
- **Impact Assessment**: Integrates population, land use, and building footprint data to quantify flood impacts.
- **Scalable Workflow**: Cloud-based processing using GEE for efficient and reproducible geospatial analytics.
## Methodology
### Data Sources
- **Sentinel-2 MSI**: Optical imagery for flood detection and land-use classification.
- **Sentinel-1 SAR**: Radar imagery for cloud-penetrating flood analysis.
- **NASA SRTM DEM**: Elevation data for terrain analysis.
- **Global Surface Water Dataset**: Historical water body dynamics.
- **Landsat 8**: Additional multi-temporal land cover analysis.
### Tools and Libraries
- **Google Earth Engine**: Primary platform for data processing and analysis.
- **ArcGIS Pro**: For additional preprocessing and visualization.
- **Python**: Supporting scripts for modeling and data manipulation.
### Workflow
1. **Data Acquisition**: Collect and preprocess satellite imagery and terrain datasets.
2. **Flood Mapping**: Apply spectral indices (e.g., NDWI) and radar analysis to delineate flood extents.
3. **Impact Analysis**:
    - Assess changes in land use and land cover.
    - Overlay flood extents with population and building datasets.
4. **Visualization**: Generate maps and reports using geospatial tools.

## Results
Flood Extent Analysis: A 53% increase in inundation area was observed during the 2022 flood peak.
Land Use Impacts:
Loss of agricultural land and vegetation due to prolonged waterlogging.
Conversion of 15,000 hectares to unproductive wetlands.
Population and Infrastructure:
Over 150,000 residents affected by flooding.
143,000 buildings identified within flood-prone zones.
Maps and Visualizations
Installation and Usage
Prerequisites
A Google Earth Engine account.
GIS software like ArcGIS or QGIS (optional).
Setup
Clone this repository:
bash
Copy code
git clone https://github.com/<your-username>/<your-repo>.git
Access the Google Earth Engine scripts provided in the code/ directory.
Update the Area of Interest (AOI) and timeframes in the script as needed.
Running the Analysis
Run the GEE scripts for data preprocessing, flood detection, and mapping.
Export results (e.g., GeoTIFFs) for further analysis in GIS software.
Applications
This workflow can be adapted for:

Real-time flood monitoring and early warning systems.
Climate change adaptation planning.
Urban and regional flood risk management.
Contributions
Contributions to improve this repository are welcome! Please open an issue or submit a pull request.

Citation
If you use this repository in your research or projects, please cite:

mathematica
Copy code
Akintola, M. O. (2024). Enhancing Disaster Response and Resilience Through Near-Time GIS for Flood Monitoring and Analysis in Niger River Basin, Nigeria. ISPRS TC III Mid-term Symposium, Belém, Brazil.
License
This project is licensed under the CC BY 4.0 License.




# Flood-Mapping
Using three different satellite imageries to leverage Google Earth Engine’s cloud computing capabilities to generate key flood 
intelligence maps before, during and after major flood events affecting the region using multi-temporal optical, thermal and radar satellite data

![Flood Extentr](https://github.com/Mercy14846/Flood-Mapping/assets/52101209/8764666d-2e9a-4a78-8370-8d5d36505bf4)
