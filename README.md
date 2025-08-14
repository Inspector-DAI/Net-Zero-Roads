# Net-Zero-Roads
README – Supplementary Data for Net-Zero Roads: Global Road Infrastructure Carbon Footprint and Decarbonization Pathways
Overview

This supplementary dataset supports the findings presented in the manuscript "Net-Zero Roads: Global Road Infrastructure Carbon Footprint and Decarbonization Pathways".
It contains the raw and processed data used for road length predictions, life-cycle carbon emission accounting, and decarbonization scenario analysis for 223 countries from 2000 to 2050.
The dataset is publicly available at: https://github.com/Inspector-DAI/Net-Zero-Roads

File Structure
**1. Raw_Data/**
Contains original source data compiled from:
CIA World Factbook
International Road Federation (IRF)
World Bank (WDI)
Knoema, Statista, IIASA SSP1 scenario datasets
National road design standards and material composition records
Files:
Road_Length_2020.csv – Baseline total lane-kilometers and density by country
GDP_PPP_2000-2050.csv – Population, GDP per capita (PPP), land area, by year
Energy_CarbonIntensity_2021.csv – Carbon intensity (kg CO₂e/MJ) by region, extrapolated to 2050
Road_Structure_Types.csv – Pavement composition, structural layer thickness by representative country

**2. Processed_Data/**
Model-ready datasets with cleaned and feature-engineered variables.
Files:
Prediction_Features.csv – Variables for XGBoost, Random Forest, and Ridge regression models
Road_Length_Predictions_2030_2040_2050.csv – Country-level predictions (2020–2050)
Lifecycle_Emission_Factors.csv – Emission factors for materials and energy sources
Maintenance_Cycles.csv – Preventive vs. corrective maintenance schedules

**3. Emission_Results/**
Outputs from the LCA-based carbon emission accounting.
Files:
Annual_Emissions_By_Country.csv – Total construction, maintenance, and use-phase emissions (Mt CO₂e)
Emission_Composition_By_Stage.csv – Share of emissions from materials vs. energy consumption
Scenario_Reductions.csv – Emission reduction by High-carbon, Middle-carbon, and Low-carbon scenarios

**Data Usage**
All data are for non-commercial academic research only. Please cite the main paper when using any part of this dataset:
Li, H., et al. (2025). Net-Zero Roads: Global Road Infrastructure Carbon Footprint and Decarbonization Pathways. [Manuscript in review].

Contact
For questions about the dataset, please contact:
Hui Li – Professor, Tongji University College of Transportation
Email: zhenhua@tongji.edu.cn
