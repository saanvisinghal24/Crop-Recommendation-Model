# 🌾 Crop Recommendation Model

> Satellite-driven crop recommendation system for Muzaffarnagar, UP — powered by Sentinel-1/2 NDVI-gap history, OPTRAM soil moisture, and ERA5 weather features.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-Boosting-green)
![Status](https://img.shields.io/badge/status-active-brightgreen)

## 📌 Overview

This project builds a **multi-label crop recommendation system** for the Muzaffarnagar agricultural region using multi-year satellite remote sensing data. It integrates:

- 🛰️ **Sentinel-1/2** derived NDVI-gap history & peak NDVI
- 💧 **OPTRAM-based** soil moisture estimates
- 🌦️ **ERA5** weather features

...into an ensemble ML pipeline (Random Forest, XGBoost, TabNet) that recommends suitable crops based on field-level conditions. Part of a broader crop sequence mapping research effort aimed at an IEEE/Scopus-level publication.

## 🧠 Models Explored

| Model | Purpose |
|---|---|
| Random Forest Classifier | Multi-output crop classification |
| XGBoost | Gradient-boosted comparison model |
| SVC / KNN / Decision Tree | Baseline benchmarks |
| TabNet (Multi-task) | Deep tabular learning approach |

## 📂 Repository Structure

```
├── Crop_Recommendation_Model.ipynb   # Main notebook — data processing, training, evaluation
├── requirements.txt                  # Python dependencies
└── README.md
```

## ⚙️ Tech Stack

`Python` · `pandas` · `numpy` · `scikit-learn` · `XGBoost` · `pytorch-tabnet` · `matplotlib`

## 🚀 Getting Started

```bash
git clone <your-repo-url>
cd crop-recommendation-model
pip install -r requirements.txt
```

Open `Crop_Recommendation_Model.ipynb` in Jupyter or Google Colab and run cells sequentially.

## 📊 Key Highlights

- Multi-label classification approach for recommending multiple viable crops per field
- Feature importance analysis to identify key remote sensing drivers
- Model comparison across classical ML and deep tabular learning methods

## 👤 Author

**Saanvi**
Final Year B.Tech CSE, ABVGIET (HPTU) 