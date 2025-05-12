# Supplementary Data for: Digital Twin System for Hydropower Infrastructure

This repository contains supplementary datasets and generated output files used in the research paper:

**"A Digital Twin Framework for Dam Monitoring, Water Allocation, and Predictive Maintenance"**

## 📁 Description

The following CSV files are used in simulation, prediction, and decision-making processes within the Digital Twin system implemented using Unity, AWS, and Python-based data modeling.

## 📄 Files Included

### 📥 Input Datasets

- `turbine_shuffled.csv`  
  Contains historical and randomized turbine operation data. Used for simulating turbine performance and supporting predictive maintenance.

- `Finalreservoir_shuffeled.csv`  
  Includes historical and synthetic data on:
  - Water level  
  - Water volume  
  - Dam storage percentage  
  - Inflow rate  
  - Outflow rate  
  - Precipitation  
  - Storage capacity  

These files are utilized to simulate real-time dam behavior and operational conditions.

### 📤 Generated Output

- `monthly_water_allocation.csv`  
  Automatically generated using Python based on the latest reservoir status. It includes:
  - Month-wise water allocation for each Taluka (for 11 agricultural months: August–June)  
  - Recommended crop types  
  - Suitable irrigation methods  
  - Calculated water requirements (in cubic meters)
