# eds220-hwk4
# Comparison of the Eaton and Palisades Fires
***
#### Author: William Mullins

#### [View Repository on Github](https://github.com/willrmull/eds220-hwk4)

## About 
***
### Purpose
- On 2025 January 7, 2025 the Eaton and Palisades wilfires broke out simulationously and devistated sections of the Los Angeles County. The goal of this notebook is to show the impact that these fires had using satalite imagry data and fire boundary data. The satalite imagrey data will use a false color composite, allowing the affect of the fire to be more clearly seen. 

### Highlights
- Regular color image of the are visualized using RGB values
- False color image of the area
- Boundary visualizations of the Eaton and Palisades fires overlayed on false color image

# Repository Structure
```
eds220-hwk4
└───README.md
└───hwk4-task2-false-color-Mullins.ipynb
└───.gitignore
    └───data
        └───landsat8-2025-02-23-palisades-eaton.nc
        └───Palisades_Perimeter_20250121.geojson
        └───Eaton_Perimeter_20250121.geojson
```


### About the data
- The satalite imagry is a clip of the [Landsat Collection 2 Level-2](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2) collected  Landsat-8 satellite. The data was preclipped to cover the desired area.

- Boundary data for the Palisades and Eaton fires.

## References
- Earth Resources Observation and Science (EROS) Center. (2020). Landsat 8-9 Operational Land Imager / Thermal Infrared Sensor Level-2, Collection 2 [dataset]. U.S. Geological Survey. https://doi.org/10.5066/P9OGBGM6 
- Palisades and Eaton Dissolved Fire Perimeters as of 2025/01/21. (2025). ArcGIS REST Services Directory. Retrieved November 22, 2025, from https://services.arcgis.com/RmCCgQtiZLDCtblq/arcgis/rest/services/Palisades_and_Eaton_Dissolved_Fire_Perimeters_as_of_20250121/FeatureServer