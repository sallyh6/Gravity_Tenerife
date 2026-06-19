# Gravity constraints on the internal structure, evolution, and stability of volcanic rift zones in Tenerife, Canary Islands: comparison with Hawaiian rift models

## 📌 Project Overview

This project investigates the hidden internal framework of the North-East Rift Zone (NERZ) in Tenerife (Canary Islands) using gravimetric data. By integrating a new, high-precision 2024 field campaign with historical datasets, we compiled a unified database to map out local gravity variations across the island. Because dense magmatic intrusions (like dikes and plumbing cores) increase the local gravitational pull, this mapping allows us to image the rift's subsurface geometry. Ultimately, we look at structural patterns like the narrowing of the rift axis to see how Tenerife’s evolution matches up against classic volcanic rift models from Hawaii.

---

## 📂 Repository Organization

The repository is structured into three main parts, from raw field data to the final gravity maps:

### 📁 0_Datasets
* **`Original_datasets/`**: Unprocessed and preprocessed CSIC field measurements, as well as other datastest used from previous articles.
* **`Final/`**: The final, processed, unified gravity database: value after corrections (topo_free_disturbance) and final values after the application of the offsets (G_ref).

### 📁 1_Methodology_Processing
Here is located all the documentation, python scripts and data needed for all the steps of the processing:
* **`01_DGNSS_positionning/`**:
* **`02_Instrument_drift/`**:
* **`03_Network_adjustment/`**:
* **`04_DEM_Tenerife/`**:
* **`05_Correction_reduction_data/`**:
* **`06_Data_alignement/`**:
* **`07_Interpolation_EQS/`**:
* **`08_Regional_field_separation/`**:
* **`09_Gradient_analysis/`**:

### 📁 2_Results_Figures
* **`Maps/`**: Final raster grids of local gravity disturbances and horizontal gravity gradients.
* **`Profiles/`**: Scripts that extract cross-sectional profiles perpendicular to the rift axes to analyze structural changes.
* **`Plotting/`**: Graphic scripts built with `PyGMT` to ensure a consistent visual design across all figures.
