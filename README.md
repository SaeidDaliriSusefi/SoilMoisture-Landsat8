# 🌍 Soil Moisture Trend Monitoring using Google Earth Engine & Python with Landsat-8 data
This repository contains a Python-based workflow to analyze long-term soil moisture trends using Landsat-8 data. The workflow leverages Google Earth Engine (GEE) for accessing and processing satellite imagery and employs remote sensing techniques to estimate soil moisture over extended periods. It provides an efficient way to monitor soil moisture dynamics, vegetation health, and their responses to climatic and environmental changes, all through Landsat-8 imagery.



## Teortical Concept:
Soil moisture is a crucial parameter for monitoring vegetation health, agricultural practices, and water management. It is influenced by various factors such as precipitation, temperature, vegetation cover, and land use. By analyzing Landsat-8 satellite data, we can estimate soil moisture trends over time, which helps in understanding regional climate patterns and agricultural productivity.

The methodology involves using Landsat-8 thermal infrared (TIR) and vegetation indices (NDVI) to estimate soil moisture using a combination of Land Surface Temperature (LST) and NDVI. The formula for soil moisture used in this approach was derived from remote sensing principles, and the relationship between vegetation cover and soil moisture is calculated using the formula:
![image alt](https://github.com/SaeidDaliriSusefi/SoilMoisture-Landsat8/blob/2edf2ec030502260f249df001bf9ddd17fa447cf/Images/L8-Formula.png)



## 📸 Example Outputs:
![image alt](https://github.com/SaeidDaliriSusefi/SoilMoisture-Landsat8/blob/efa2e527783117ecd2cdb03fce507486834f4677/Images/soil_moisture_trend.png)
