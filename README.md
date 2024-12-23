# Near-Time GIS for Flood Monitoring and Analysis in Niger River Basin, Nigeria
This repository hosts the resources, code, and documentation for the study **"Enhancing Disaster Response and Resilience Through Near-Time GIS for Flood Monitoring and Analysis in Niger River Basin, Nigeria"**, as presented at the ISPRS TC III Mid-term Symposium, 2024.

### Overview
Flooding in Nigeria is a critical issue affecting lives, livelihoods, and infrastructure, particularly in the Niger River Basin. This project leverages Google Earth Engine (GEE) for near-real-time flood mapping, impact analysis, and flood resilience modeling. It combines multi-temporal remote sensing datasets with geospatial analysis techniques to quantify flood hazards, assess exposure, and provide actionable insights for disaster response.
![NBStudy Area](https://github.com/user-attachments/assets/10e3a850-08ad-445a-bbec-3c156ef0209b)

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
<img width="1971" alt="Methodology" src="https://github.com/user-attachments/assets/72f9f6cf-798c-415e-8a90-d6563372ea5e" />

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
![Workflow](https://github.com/user-attachments/assets/62cb3e19-2faa-4ace-9d4f-a2ffeebea2f2)

## Results
- **Flood Extent Analysis**: A 53% increase in inundation area was observed during the 2022 flood peak.
![hills](https://github.com/user-attachments/assets/987b0b9f-a73a-424e-8eec-f14a5e874335)
- **Land Use Impacts**:
    - Loss of agricultural land and vegetation due to prolonged waterlogging.
    - Conversion of 15,000 hectares to unproductive wetlands.
![Flood Extentr](https://github.com/user-attachments/assets/25277f75-15ab-4438-ab34-53bb56e42ebe)
- **Population and Infrastructure**:
    - Over 150,000 residents were affected by flooding.
    - 143,000 buildings identified within flood-prone zones.
![build foot](https://github.com/user-attachments/assets/9f6d3447-810a-4655-8778-4ed91527e029)
## Maps and Visualizations
![B_wetness](https://github.com/user-attachments/assets/833bbded-fbcb-45b1-b89f-8a495f803296)
![A_wetness](https://github.com/user-attachments/assets/2412bea4-2829-4097-90de-9464ae34c8d4)
![Before NDWI](https://github.com/user-attachments/assets/92d51198-92d4-44a6-84ed-bfcf781c11c0)
![After NDWI](https://github.com/user-attachments/assets/4734139a-ab87-45c7-94e0-92ffdf55dab4)
![Before LULC](https://github.com/user-attachments/assets/27c2a401-6381-4ee5-9f50-5b3cf7a8cd84)
![After LULC](https://github.com/user-attachments/assets/399daff4-08c7-43dc-b9bc-49ac0b235da9)

### Installation and Usage
#### Prerequisites
- A Google Earth Engine account.
- GIS software like ArcGIS.
#### Setup
1. Clone this repository:
```bash
git clone https://github.com/<your-username>/<your-repo>.git
```
2. Access the Google Earth Engine scripts provided in the code/ directory.
3. Update the Area of Interest (AOI) and timeframes in the script as needed.
### Running the Analysis
- Run the GEE scripts for data preprocessing, flood detection, and mapping.
- Export results (e.g., GeoTIFFs) for further analysis in GIS software.
## Applications
This workflow can be adapted for:
- Real-time flood monitoring and early warning systems.
- Climate change adaptation planning.
- Urban and regional flood risk management.

## Contributions
Contributions to improve this repository are welcome! Please open an issue or submit a pull request.

## Citation
If you use this repository in your research or projects, please cite:

```mathematica
Akintola, M. O. (2024). Enhancing Disaster Response and Resilience Through Near-Time GIS for Flood Monitoring and Analysis in Niger River Basin, Nigeria. ISPRS TC III Mid-term Symposium, Belém, Brazil.
```
## License
This project is licensed [GPL-3.0 License](LICENSE)
