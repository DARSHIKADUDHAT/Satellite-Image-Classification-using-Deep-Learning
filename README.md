# 🛰️ Satellite Image Classification using Deep Learning

## 📌 Overview
This project focuses on **classifying satellite images** into different land-use/land-cover categories using **deep learning techniques**. The model learns visual patterns from satellite imagery and predicts the correct class such as buildings, forest, water, roads, etc.

This project demonstrates the application of **Computer Vision** and **Convolutional Neural Networks (CNNs)** in geospatial analysis.

---

## ✨ Features
- 🧠 Deep Learning-based image classification
- 🛰️ Works on satellite imagery datasets
- 📊 Model training, validation, and testing pipeline
- 📈 Performance evaluation with accuracy & loss graphs
- ⚙️ Easy to modify and extend architecture

---

## 🏗️ Project Structure
├── satellite_image-classification.ipynb # Main notebook
├── dataset/ # Satellite image dataset
├── models/ # Saved trained models (optional)
├── outputs/ # Predictions & results
└── README.md

---
## 📂 Dataset: SEN-2 LULC (Sentinel-2 Land Use / Land Cover)

This project uses the **SEN-2 LULC dataset**, a benchmark dataset for **land use and land cover classification** based on satellite imagery from the Sentinel-2 mission.

### 🛰️ Dataset Overview
- Source: Sentinel-2 satellite imagery  
- Type: Multi-class image classification dataset  
- Domain: Remote sensing / Geospatial analysis  

---

### 📊 Classes

The dataset contains the following land cover categories:

1. 🌆 Urban / Built-up  
2. 🌾 Agriculture  
3. 🌲 Forest  
4. 🌊 Water  
5. ⛰️ Barren land  
6. 🌿 Grassland / Vegetation  
---
## ⚙️ Installation

Install required dependencies:

```bash
pip install numpy
pip install pandas
pip install matplotlib
pip install seaborn
pip install opencv-python
pip install scikit-learn
pip install tensorflow

----
Model Architecture
Convolutional Neural Network (CNN)
Layers include:
Conv2D
MaxPooling
Flatten
Dense layers
Activation: ReLU / Softmax
