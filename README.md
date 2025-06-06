# Peak Value Method (PVM): Winter Wheat Mapping (2001–2020) across Bulgaria–Turkey

This repository supports the research manuscript _"The Peak Value Method (PVM): A Phenology-Guided, Training-Independent Approach for Large-Area Time-series Wheat Mapping"_ by Aparna R. Phalke. It includes code and resources used for mapping winter wheat across the cross-border region of Bulgaria and northwestern Turkey using Landsat EVI time series data.

## 📌 Overview

The **Peak Value Method (PVM)** is a phenology-guided, training-independent framework that identifies winter wheat areas based on regionally optimized **Maximum EVI** and **Day of Year (DOY)** thresholds. This method was applied to generate 30-meter winter wheat extent maps from **2001 to 2020** using Landsat 5, 7, and 8 imagery.

## 🛰️ Key Features

- Dynamic MaxEVI and MaxDOY threshold selection via sensitivity analysis  
- Region-specific adaptation for six Bulgarian regions and NW Turkey  
- Landsat-based EVI time-series preprocessing in Google Earth Engine  
- Area statistics by administrative unit (region, province, district)  
- Accuracy assessment and comparison with government statistics  

## 📂 Repository Structure


## Tools & Dependencies

- [Google Earth Engine](https://earthengine.google.com/)
- Landsat Tier 1 Surface Reflectance collections (L5, L7, L8)
- Optional: Python/Excel for post-processing CSV exports

## Citation

If you use this code or adapt the methodology, please cite:

**Phalke, A. R.** (2025). _The Peak Value Method (PVM): A Phenology-Guided, Training-Independent Approach for Large-Area Time-series Wheat Mapping_.

## Contact

**Aparna R. Phalke**  
📧 aparnapm16@gmail.com  


---

This work is part of the Aparna's PhD dissertation.
