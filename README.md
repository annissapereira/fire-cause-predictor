# 🔥 California Wildfire Cause Prediction

This project aims to predict the **cause of wildfires** in California by analyzing daily weather data from the **NOAA (National Oceanic and Atmospheric Administration)** and fire incident data from the **FRAP (Fire and Resource Assessment Program)** dataset.

---

## 📌 Project Motivation

Wildfires are a growing threat in California, with significant social, environmental, and economic impacts. Understanding and predicting the cause of wildfires can help with:

- Preventive resource allocation
- Risk mitigation strategies
- Targeted awareness and policy-making

---

## 🧠 Problem Statement

**Objective:** Predict the _cause_ of wildfire incidents in California based on historical weather data and geospatial attributes.

---

## 📂 Datasets Used

### 🌦 NOAA Daily Weather Data
- Historical weather observations across California from NOAA stations.
- Key Features:
  - `AWND`: Average wind speed
  - `PRCP`: Precipitation
  - `TMAX`, `TMIN`: Daily max/min temperature
  - Wind directions and gusts
  
🔗 [Download NOAA Daily Weather Data](https://www.ncei.noaa.gov/data/global-historical-climatology-network-daily/)

### 🔥 FRAP Fire Incident Dataset
- Historical fire events with geolocation, size, discovery time, and cause.
- Key Features:
  - `FIRE_SIZE`, `FIRE_YEAR`
  - `DISCOVERY_DATE`, `DISCOVERY_TIME`
  - `LATITUDE`, `LONGITUDE`
  - `NWCG_CAUSE_CLASSIFICATION`, `NWCG_GENERAL_CAUSE`

🔗 [FRAP Fire Perimeters Dataset](https://frap.fire.ca.gov/mapping/gis-data/)

---

## 🤝 Acknowledgements

- California Fire and Resource Assessment Program (FRAP)
- National Oceanic and Atmospheric Administration (NOAA)
- UMass Dartmouth (for project inspiration & support)

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
