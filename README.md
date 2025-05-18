# Deforestation Monitoring using Satellite Imagery

This project uses Convolutional Neural Networks (CNNs) to detect and monitor deforestation using satellite images from the EuroSAT dataset.

## 🛰️ Objective

To develop a deep learning system that uses satellite imagery for land cover classification and simulates deforestation detection using change detection techniques.

## 🔍 Features

- Preprocessing of multi-band satellite images (RGB)
- CNN model for land classification
- Change detection simulation between forest and urban areas
- Visualization of image batches and detected changes
- Report generation in DOCX format

## 📂 Dataset

We used the **EuroSAT RGB** dataset, which consists of Sentinel-2 satellite images with 10 different land use classes. It is available through `torchvision.datasets.EuroSAT`.

## 📓 Colab Notebook

You can run the full pipeline using the `DeforestationMonitoring.ipynb` notebook, which includes:

- Data loading and visualization
- Model training and evaluation
- Change detection logic
- Report generation

## 📝 Report

The `Deforestation_Monitoring_Report.docx` file summarizes:

- Goals and outcomes
- Challenges (e.g., unavailable original datasets)
- Final solution using EuroSAT
- Results and future improvements

## Clone Repository

```bash
git clone https://github.com/Khansa05/deforestation-monitoring-cnn.git
cd deforestation-monitoring-cnn
pip install -r requirements.txt

