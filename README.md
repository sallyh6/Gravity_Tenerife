# Gravity constraints on the internal structure, evolution, and stability of volcanic rift zones in Tenerife, Canary Islands: comparison with Hawaiian rift models

## 📌 Project Overview

This project investigates the hidden internal framework of the North-East Rift Zone (NERZ) in Tenerife (Canary Islands) using gravimetric data. By integrating a new, high-precision 2024 field campaign with historical datasets, we compiled a unified database to map out local gravity variations across the island. Because dense magmatic intrusions (like dikes and plumbing cores) increase the local gravitational pull, this mapping allows us to image the rift's subsurface geometry. Ultimately, we look at structural patterns like the narrowing of the rift axis to see how Tenerife’s evolution matches up against classic volcanic rift models from Hawaii.

---

## 📂 Repository Organization

The repository is structured into three main blocks to take you from raw field data to the final geophysical maps:

### 📁 0_Datasets
* **`Raw/`**: Unprocessed field measurements, including relative gravity readings from the Burris gravimeter, Earth-tide data, and raw GNSS logs.
* **`Processed/`**: The final unified gravity database, the merged digital elevation model (land topography + bathymetry), and the comparative data profiles from Hawaii.

### 📁 1_Methodology
* **`Preprocessing/`**: Python scripts and workflows for differential GNSS positioning, instrument drift corrections, and network adjustments.
* **`Reduction/`**: Codes handling gravity corrections, 3D topographic prism modeling, and regional-residual field separation using satellite data.
* **`Interpolation/`**: Physics-based gridding scripts utilizing the Equivalent Source method to turn scattered data points into continuous maps.

### 📁 2_Results_Figures
* **`Maps/`**: Final raster grids of local gravity disturbances and horizontal gravity gradients.
* **`Profiles/`**: Scripts that extract cross-sectional profiles perpendicular to the rift axes to analyze structural changes.
* **`Plotting/`**: Graphic scripts built with `PyGMT` to ensure a consistent visual design across all figures.
