# Air Pollution Analysis of NO₂ Levels in India (2020-2024)

This repository contains a detailed analysis of NO₂ (Nitrogen Dioxide) pollution across India over the period of 2020 to 2024. The analysis focuses on understanding the temporal and spatial trends of NO₂ levels using Sentinel-5P satellite data.

![download](https://github.com/user-attachments/assets/3c3f3424-ded5-47d2-9b4e-892c4e7c65a0)

## Table of Contents
1. [Overview](#overview)
2. [Data Source](#data-source)
3. [Methods](#methods)
4. [Usage](#usage)
5. [Analysis and Results](#analysis-and-results)
6. [Conclusion](#conclusion)
7. [License](#license)

## Overview

This study analyzes NO₂ pollution data from **Sentinel-5P** to investigate seasonal patterns, yearly variations, and spatial distribution of NO₂ concentrations across India. The analysis spans five years, from **2020 to 2024**, with a focus on understanding the seasonal peaks during the summer and winter months, particularly in **June** and **December**.

## Data Source

The data for this analysis is obtained from **Sentinel-5P**, a satellite that provides atmospheric measurements, including NO₂ mole fraction. The data covers various atmospheric parameters, with a particular focus on trace gases like NO₂. The **SentinelHub** service is used to request and download this data for further analysis.

## Methods

The analysis is conducted in the following steps:

1. **Data Extraction**: NO₂ data for India is obtained using the **Sentinel-5P** satellite and processed using the **SentinelHub** API.
2. **Temporal Analysis**: The NO₂ concentrations are analyzed for seasonal and yearly trends, comparing values across months and years (2020–2024).
3. **Spatial Analysis**: A spatial analysis is conducted using geographical boundaries for India, and the data is rasterized to create a spatial representation of NO₂ pollution.
4. **Statistical Analysis**: The data is aggregated by year, and statistical methods are applied to identify patterns and trends in NO₂ concentrations.

## Usage

1. **Jupyter Notebook**: The analysis is performed in a Jupyter Notebook ([`no2_analysis.ipynb`](https://github.com/AumGupta/air-pollution-analysis/blob/main/no2_analysis.ipynb)). You can open and run the notebook to explore the step-by-step analysis.
   
2. **Running the Analysis**: To run the analysis, simply open the notebook and execute the cells in order. Make sure you have access to **Sentinel-5P** data via the **SentinelHub** service.

3. **Data Preparation**: Before starting, ensure you have the necessary data from **SentinelHub** for the years 2020-2024. The analysis scripts include steps for downloading and processing the data from **Sentinel-5P**.

4. **Results**: The notebook generates various visualizations of NO₂ levels, including time-series plots, seasonal variations, spatial maps, and yearly comparisons.

## Analysis and Results

- **Temporal Trends**: NO₂ concentrations show distinct seasonal variations, with peaks in **June** (summer) and **December** (winter). The highest concentrations are typically observed in **December**.
- **Spatial Distribution**: Spatial mapping of NO₂ pollution helps identify regions with the highest pollution levels, which may correlate with urbanization, traffic density, and industrial activity.
- **Yearly Comparison**: A yearly comparison of NO₂ levels across 2020-2024 highlights trends and anomalies, such as the potential impact of the COVID-19 lockdown on air quality in 2020.

## Conclusion

The study provides valuable insights into the NO₂ pollution trends across India from 2020 to 2024. The findings highlight significant seasonal spikes, particularly in **June** and **December**, and suggest potential correlations with weather, industrial activities, and vehicular emissions. The results emphasize the need for targeted air quality management and policy interventions to reduce NO₂ levels, especially during high-risk periods.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
