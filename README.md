# EECT-2-Calculation
# Entropy–Ecological Cycles Theory (EECT) – EEI 2.0 Workflow
This repository provides the complete workflow, datasets, and scripts used in the paper:

**"Satellite-Derived Entropy Indicators for Early Warning of Ecosystem Collapse: A Machine Learning Approach Based on the Extended Entropy–Ecological Cycles Theory (EECT)"**  
Submitted to *International Journal of Applied Earth Observation and Geoinformation (JAG)*.

---

## 🔹 Overview
The project operationalizes the Extended Entropy–Ecological Cycles Theory (EECT) using multi-source Earth observation data and machine learning.  
It introduces **EEI 2.0**, an entropy-based geoinformatic indicator for detecting early-warning signals of ecosystem collapse.

---

## 🔹 Workflow Summary
1. **Data Collection:** MODIS (NDVI, LST), Sentinel-2 (LAI), SMAP (Soil Moisture), ERA5 (climate), and auxiliary layers.  
2. **Preprocessing:** Temporal harmonization and cloud masking (Google Earth Engine).  
3. **Entropy Modelling:** EEI = Σ (wᵢ × H(xᵢ)) with SHAP-informed variable weighting.  
4. **Threshold Detection:** Bayesian change-point analysis for collapse regime identification.  
5. **Validation:** Comparison with NDVI stability and land-use transition rates.

---

## 🔹 Repository Structure
