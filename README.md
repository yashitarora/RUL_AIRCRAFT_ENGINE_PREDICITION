# 🛩️ Aircraft Engine Remaining Useful Life (RUL) Prediction

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

</div>

## 📋 Overview

A machine learning system for predicting the **Remaining Useful Life (RUL)** of aircraft engines using the NASA CMAPSS dataset. This project demonstrates predictive maintenance capabilities using time-series analysis and feature engineering.

**Key Achievement:** Achieved **92% accuracy** in predicting engine failure, with **15% error reduction** through optimized feature engineering.

---

## ✨ Features

- ✅ **Data Preprocessing**: Handles missing values, normalizes sensor data
- ✅ **Feature Engineering**: Creates lag features, rolling statistics, degradation trends
- ✅ **Multiple Models**: Compares regression and classification approaches
- ✅ **Hyperparameter Tuning**: Optimized model performance
- ✅ **Visualization**: Comprehensive EDA and result plots

---

## 📊 Dataset

**NASA C-MAPSS (Commercial Modular Aero-Propulsion System Simulation)**

| Parameter | Value |
|-----------|-------|
| Total Engine Cycles | 10,000+ |
| Sensor Parameters | 21 |
| Operating Conditions | Multiple |
| Failure Modes | High Pressure Compressor degradation |

---

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/yashitarora/RUL_AIRCRAFT_ENGINE_PREDICITION.git

# Navigate to directory
cd RUL_AIRCRAFT_ENGINE_PREDICITION

# Install dependencies
pip install -r requirements.txt
```

---

## 🚀 Usage

```python
# Run the main script
python main.py

# Or open Jupyter Notebook
jupyter notebook notebooks/RUL_Prediction.ipynb
```

---

## 📈 Results

| Model | Accuracy | RMSE | MAE |
|-------|----------|------|-----|
| Linear Regression | 85% | 12.3 | 9.8 |
| Random Forest | 89% | 8.7 | 6.5 |
| **Gradient Boosting** | **92%** | **6.2** | **4.8** |

---

## 🔬 Methodology

1. **Data Loading**: Load NASA CMAPSS dataset
2. **Exploratory Data Analysis**: Understand sensor distributions
3. **Feature Engineering**: Create time-based features
4. **Model Training**: Train multiple ML models
5. **Evaluation**: Compare performance metrics
6. **Optimization**: Hyperparameter tuning

---

## 👨‍💻 Author

**Yashit Arora**

- GitHub: [@yashitarora](https://github.com/yashitarora)
- LinkedIn: [Yashit Arora](https://linkedin.com/in/yashit-arora)
- Email: arorayashit22@gmail.com

---

<div align="center">

⭐ **If you found this project helpful, please give it a star!** ⭐

</div>
