# PCA Analysis on Multiple Datasets

This project applies Principal Component Analysis (PCA) to two different datasets:
- Occupancy Detection Dataset
- Pesticide Classification Dataset (Weed vs Crop)

The goal is to explore the variance structure of each dataset, implement PCA manually, and visualize results using variance plots and projections into principal component space.

## 📁 Structure

```
PCA_MultiDataset_Analysis/
├── notebooks/
│   └── PCA_Occupancy_Pesticide_Analysis.ipynb
├── data/
│   └── OccupancyTrain.csv
│   └── IDSWeedCropTrain.csv
│   └── IDSWeedCropTest.csv
├── requirements.txt
└── README.md
```

## 📦 Datasets

- **Occupancy**: [UCI Occupancy Detection Dataset](https://archive.ics.uci.edu/ml/datasets/Occupancy+Detection+)
- **Pesticide**: Based on IDSWeedCropTrain.csv,IDSWeedCropTest.csv — used for pesticide classification (weed vs crop).

## ▶️ Instructions

1. Download the datasets in the `data/` folder.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook in `notebooks/` and follow the analysis.

## ✅ Features

- Manual PCA (using NumPy)
- Explained variance plots
- 2D principal component projections
- Comparative insight across datasets

---
MIT License