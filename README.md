# Network Anomaly Detection with LSTM and KNN (SMOTE)

This repository contains coursework artifacts for network anomaly detection experiments using LSTM and KNN models with SMOTE-based data augmentation.

## Project Contents

- `70_30ipynb.ipynb`: Main 70/30 train-test workflow notebook.
- `MACHINE LEARNING PROJECT.ipynb`: Additional project notebook and analysis.
- `knn lstm reproduced.ipynb`: Reproduction notebook for KNN + LSTM results.
- `cicid2017 comparison with csv 3.ipynb`: Dataset/model comparison notebook.
- `orig ppr outputs.ipynb`: Original paper output reproduction notebook.
- `Improved Research Paper.pdf`: Project paper/report.
- `dataset pics/`: Screenshots/figures related to prepared dataset and outputs.
- `old dataset/`: Screenshots/figures from earlier dataset versions.

## Dataset Context

The experiments are based on CICIDS2017-style network traffic data prepared for binary/multiclass anomaly detection tasks. Data balancing is handled using SMOTE in selected workflows.

## Typical Workflow

1. Open a notebook in Jupyter.
2. Load and clean the dataset.
3. Apply feature preprocessing and scaling.
4. Balance classes with SMOTE where required.
5. Train and evaluate KNN and LSTM models.
6. Compare metrics (accuracy, precision, recall, F1-score, confusion matrix).

## Notes

- Notebooks may include absolute/local file paths; update them for your environment before running.
- Results can vary depending on preprocessing choices and random seeds.
