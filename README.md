# Applied Oceanography & Climate Data Science Portfolio

A collection of 10 reproducible computational projects bridging **physical oceanography, satellite remote sensing, numerical modelling, and machine learning**. This portfolio demonstrates production-grade proficiency in processing large-scale oceanographic datasets, validating hydrodynamic models against in-situ observations, and building predictive climate pipelines using Python.

---

Portfolio Projects Overview

| **01. Argo Hydrography** | In-Situ Observations | Processing global Argo float NetCDF profiles; computing temperature-salinity (T-S) diagrams and Mixed Layer Depth (MLD). |
| **02. Ocean Circulation** | Satellite Remote Sensing | Extracting regional sea surface temperature (SST) grids via OPeNDAP to visualize the Gulf Stream current boundaries. |
| **03. Satellite Ocean Color** | Biogeochemistry | Analyzing MODIS/Copernicus chlorophyll-$a$ data with logarithmic color scaling to map coastal phytoplankton blooms. |
| **04. Coastal Bathymetry GIS** | Topography & GIS | Rendering high-resolution seafloor relief and trench morphology using ETOPO 2022 global bathymetry datasets. |
| **05. Coastal Hydrodynamics** | Numerical Modeling | Streaming HYCOM velocity components to map geostrophic current vectors and oceanic kinetic energy fields. |
| **06. Sediment Transport** | Coastal Engineering | Computing seabed bottom shear stress ($\tau_b$) and dynamic erosion thresholds for sediment mobilization. |
| **07. Model Validation** | Data Assimilation | Overlaying vertical model profiles from HYCOM against in-situ Argo float observations to quantify model bias. |
| **08. Climate Variability** | Climate Dynamics | Analyzing multi-decadal NOAA OISST reanalysis streams to isolate and shade El Niño and La Niña anomaly cycles. |
| **09. 1D Numerical Model** | Geophysical Fluid Dynamics | Building a custom finite-difference heat diffusion time-stepping engine mimicking supercomputer models like MITgcm. |
| **10. Machine Learning Forecast** | AI / Data Science | Training a Random Forest Regressor with lag-feature engineering to forecast future ocean temperature anomalies. |

---

Tech Stack & Ecosystem

* **Language:** Python 
* **Data Access & Streaming:** OPeNDAP / THREDDS Cloud Servers, NetCDF4, Xarray
* **Numerical Computing & Analysis:** NumPy, Pandas, SciPy
* **Geospatial & Visualization:** Cartopy, Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Random Forest regression, feature engineering, train-test validation)
* **Version Control & Reproducibility:** Git, GitHub, Jupyter Lab

---

## 🚀 Reproducibility & Data Architecture

To maintain a lightweight repository and adhere to best practices, **raw oceanographic data files (`.nc`) and large numerical outputs are excluded from version control via `.gitignore`**. 

Every notebook in this portfolio connects directly to open-access THREDDS/OPenDAP servers (such as NOAA and HYCOM data servers). When you run a notebook, it dynamically streams and processes the exact data subsets required, ensuring 100% reproducibility across any machine.

---

## 👤 Author

**Ojash Giri**
* *Focus:* Physical Oceanography, Climate Dynamics, and Computational Marine Science
* *GitHub:* [@ojashgiri42](https://github.com/ojashgiri42)