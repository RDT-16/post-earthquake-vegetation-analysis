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
| `fig(a).png`  | Sample Landsat NDVI Data |
| `fig(b).png`  | Sample Landsat Data |
| `fig(c).png`  | Data PreProcessing and Feature Engineering |
| `fig(d).png`  | System Workflow |
| `fig(e).png`  | Organizing Climate Data |
| `fig(f).png`  | Loading Landaat Data |
| `fig(g).png`  | Pre and Post-Eartquake Data Comparison |
| `fig(h).png`  | Average NDVI Values |
| `fig(i).png`  | Testing and Training Split |
| `fig(j).png`  | Comparison of Prediction Models |
| `fig(k).png`  | Random Forest for Prediction |
| `fig(l).png`  | Predicted Trends and Accuracy validation |
| `fig(m).png`  | Pre-Eartquake Data |
| `fig(n).png`  | Post-Eartquake Data |
| `fig(o).png`  | Historical NDVI  Data |
| `fig(p).png`  | Future Prediction of Vegetation Health |

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

## 👤 Author

**Rithik Thakur**  
🧠 CSE Core | 📊 Data & Earth Analytics | 🌏 Sustainable Tech  
🔗 [LinkedIn](https://www.linkedin.com/)  
📩 Reach out via issues or discussions tab for project queries.

---

📁 *This repository contains only images and documentation; code is not included.*
