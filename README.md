# KNN Classification

A machine learning project that implements the **K-Nearest Neighbors (KNN)** algorithm for binary classification using the Breast Cancer Wisconsin dataset.

## Overview

KNN is a supervised, distance-based algorithm that classifies a new data point based on the classes of its nearest neighbors.

### Workflow

**Data Preprocessing → Train/Test Split → Feature Scaling → K Selection → Model Training → Prediction → Evaluation**

## Dataset

The model uses cellular characteristics such as:

- Cl.thickness
- Cell.size
- Cell.shape
- Marg.adhesion
- Epith.c.size
- Bare.nuclei
- Bl.cromatin
- Normal.nucleoli
- Mitoses

**Target:** `Class`

The `Id` column is excluded because it is only an identifier.

## Model

- Algorithm: **K-Nearest Neighbors**
- Distance Metric: **Euclidean Distance**
- Scaling: **StandardScaler**
- K: Selected by comparing multiple K values

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Technologies

`Python` `Pandas` `NumPy` `Scikit-learn` `Matplotlib` `Joblib` `Jupyter Notebook`

## Project Structure

```text
KNN-model-ML/
├── KNN.ipynb
├── BreastCancer.txt
├── knn_model.pkl
├── standard_scaler.pkl
└── README.md
