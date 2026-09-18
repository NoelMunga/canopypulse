# 🌲 CanopyPulse: Time-Series Forest Loss Platform

An open-source, cloud-native geospatial platform designed to track, quantify, and visualize historical forest canopy degradation across a 15-year timeline (2011, 2016, 2021, and 2026).

CanopyPulse integrates Google Earth Engine (GEE) satellite archives with machine learning workflows and an interactive Streamlit frontend to democratize remote sensing data for climate research, conservation auditing, and environmental policy analysis[cite: 1].

---

## 🚀 Key Features

* **Democratizing Climate Science:** Delivers instant, web-based satellite deforestation analysis without requiring desktop GIS software (such as QGIS or ArcGIS)[cite: 1].
* **Carbon Stock & Reserve Auditing:** Provides baseline verification for carbon credit projects and conservation zones to monitor forest stability over multi-year periods[cite: 1].
* **Actionable Metrics:** Converts raw satellite pixels into hectares lost, percentage change figures, and estimated $CO_{2}$ emissions[cite: 1].

---

## 🛠️ Architecture & Tech Stack

| Component | Technology | Purpose |
| :--- | :--- | :--- |
| **Model Validation** | Google Colab | Cloud environment for model scripting and validation[cite: 1] |
| **Data Archive** | Google Earth Engine | Multi-spectral Landsat & Sentinel-2 satellite imagery[cite: 1] |
| **Frontend UI** | Streamlit | Cloud dashboard with interactive widgets and analytics[cite: 1] |
| **Mapping Engine** | Geemap & Folium | Geospatial visual layers and interactive map components[cite: 1] |
| **Version Control** | GitHub | Source code repository and automated CI/CD deployment[cite: 1] |

---

## 📁 Repository Structure

```text
├── app.py              # Main Streamlit web application[cite: 1]
├── requirements.txt    # Python runtime dependencies[cite: 1]
└── README.md           # Project documentation and setup guide
