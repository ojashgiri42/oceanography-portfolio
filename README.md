# Applied Oceanography & Climate Data Science Portfolio

A collection of 13 reproducible computational projects bridging **physical oceanography, satellite remote sensing, biogeochemistry, climate dynamics, and machine learning**. This portfolio demonstrates production-grade proficiency in processing large-scale oceanographic datasets, validating hydrodynamic models against in-situ observations, and building predictive climate pipelines using Python.

---

## 🔬 Portfolio Projects Overview

| Project | Domain | Description & Key Skills |
| :--- | :--- | :--- |
| **01. Argo Hydrography** | In-Situ Observations | Processing global Argo float NetCDF profiles; computing temperature-salinity (T-S) diagrams and Mixed Layer Depth (MLD). |
| **02. Ocean Circulation** | Satellite Remote Sensing | Extracting regional sea surface temperature (SST) grids via OPeNDAP to visualize Gulf Stream current boundaries. |
| **03. Satellite Ocean Color** | Biogeochemistry | Analyzing MODIS/Copernicus chlorophyll-$a$ data with logarithmic color scaling to map coastal phytoplankton blooms. |
| **04. Coastal Bathymetry GIS** | Topography & GIS | Rendering high-resolution seafloor relief and trench morphology using ETOPO global bathymetry datasets. |
| **05. Coastal Hydrodynamics** | Numerical Modeling | Streaming HYCOM velocity components to map geostrophic current vectors and oceanic kinetic energy fields. |
| **06. Sediment Transport** | Coastal Engineering | Computing seabed bottom shear stress ($\tau_b$) and dynamic erosion thresholds for sediment mobilization. |
| **07. Model Validation** | Data Assimilation | Overlaying vertical model profiles from HYCOM against in-situ Argo float observations to quantify model bias. |
| **08. Climate Variability** | Climate Dynamics | Analyzing multi-decadal NOAA OISST reanalysis streams to isolate and shade El Niño and La Niña anomaly cycles. |
| **09. 1D Numerical Model** | Geophysical Fluid Dynamics | Building a custom finite-difference heat diffusion time-stepping engine mimicking supercomputer models like MITgcm. |
| **10. Machine Learning Forecast** | AI / Data Science | Training a Random Forest Regressor with lag-feature engineering to forecast future ocean temperature anomalies. |
| **11. Satellite Altimetry & Eddies** | Remote Sensing & Dynamics | Deriving geostrophic velocity vectors ($u_g, v_g$) and Eddy Kinetic Energy (EKE) from Sea Surface Height ($\eta$) gradients. |
| **12. Marine Heatwaves (MHW)** | Climate Extremes | Processing 30-year SST baselines to detect, quantify, and categorize Marine Heatwaves using the Hobday et al. framework. |
| **13. BGC-Argo Carbon Pump** | Biogeochemistry | Analyzing vertical profiles of oxygen, nitrate, and chlorophyll-$a$ to compute Apparent Oxygen Utilization (AOU) and carbon remineralization. |

---

## 🛠️ Tech Stack & Ecosystem

* **Language:** Python 
* **Data Access & Streaming:** OPeNDAP / THREDDS Cloud Servers, NetCDF4, Xarray
* **Numerical Computing & Analysis:** NumPy, Pandas, SciPy
* **Geospatial & Visualization:** Cartopy, Matplotlib, Seaborn
* **Machine Learning & Signal Processing:** Scikit-Learn (Random Forest regression, feature engineering, time-series analysis)
* **Version Control & Reproducibility:** Git, GitHub, Jupyter Lab

---

## 🚀 Reproducibility & Data Architecture

To maintain a lightweight repository and adhere to software engineering best practices, **raw oceanographic data files (`.nc`) and large numerical outputs are excluded from version control via `.gitignore`**. 

Every notebook in this portfolio connects directly to open-access cloud data servers or includes inline data generation scripts, ensuring 100% execution reproducibility across any machine.

---

## 👤 Author

**Ojash Giri**
* *Focus:* Physical Oceanography, Climate Dynamics, and Computational Marine Science
* *GitHub:* [@ojashgiri42](https://github.com/ojashgiri42)