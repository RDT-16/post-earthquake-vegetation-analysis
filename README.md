# post-earthquake-vegetation-analysis

This repository documents the impact of a major earthquake on vegetation health in Northern India using NDVI data and predictive machine learning models. It includes figures only (no code), stored in the `doc/` folder.

---

## 📘 Project Summary

- **Objective**: To assess vegetation health before and after an earthquake using NDVI from Landsat imagery and predict future trends using machine learning.
- **Tools Used**:
  - NDVI derived from Landsat data
  - Precipitation data from CHIRPS
  - Machine Learning: Random Forest, SVR, Gradient Boosting
- **Best Model**: Random Forest  
  - **R²**: 91.05%  
  - **RMSE**: 0.04  

---

## 📂 Figures Overview

All figures are located in the `doc/` folder. Each corresponds to a specific stage of the research.

| File Name     | Description |
|---------------|-------------|
| `fig(a).png`  | Organizing climate data (CHIRPS merge) |
| `fig(b).png`  | Loading Landsat NDVI data |
| `fig(c).png`  | Pre- and post-earthquake NDVI comparison |
| `fig(d).png`  | Average NDVI summary values |
| `fig(e).png`  | Training/testing data split |
| `fig(f).png`  | Model comparison (Random Forest, SVR, etc.) |
| `fig(g).png`  | Random Forest prediction tuning |
| `fig(h).png`  | NDVI prediction trends with accuracy metrics |
| `fig(i).png`  | Pre-earthquake NDVI plot |
| `fig(j).png`  | Post-earthquake NDVI plot |
| `fig(k).png`  | Historical NDVI time series |
| `fig(l).png`  | Future NDVI forecast plot |
| `fig(m).png`  | System architecture/workflow |
| `fig(n).png`  | Data preprocessing and feature engineering |

---

## 🔍 Key Insights

- NDVI significantly dropped post-earthquake, indicating vegetation stress.
- Forecasting models show gradual recovery with seasonal variation.
- Time-aware validation (TimeSeriesSplit) ensured robust model performance.

---

## 🌱 Future Enhancements

- Add variables like soil moisture, pollutants, and surface temperature.
- Incorporate drone or high-resolution imagery.
- Extend to other disasters: floods, droughts, wildfires.
- Enable real-time vegetation monitoring with AutoML and ensemble models.

---

## 📎 References

- Landsat (NDVI data)
- CHIRPS (Precipitation)
- Peer-reviewed literature on erosion modeling and vegetation recovery  
(Full citations available in the `REFERENCES` section of the report.)

---

## 👤 Author

**Rithik Thakur**  
🧠 CSE Core | 📊 Data & Earth Analytics | 🌏 Sustainable Tech  
🔗 [LinkedIn](https://www.linkedin.com/)  
📩 Reach out via issues or discussions tab for project queries.

---

📁 *This repository contains only images and documentation; code is not included.*
