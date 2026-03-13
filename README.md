# Tuberculosis Detection using DenseNet-121 🫁🧬

A state-of-the-art Deep Learning pipeline for the automated detection of **Tuberculosis (TB)** from Chest X-Rays. This repository implements research-grade architectures focusing on high sensitivity and diagnostic accuracy.

## 🌟 Overview
Early detection of TB is critical for effective treatment. This project utilizes a specialized **DenseNet-121** backbone, optimized for medical imaging features, to identify pathological patterns in lung radiographs.

## 🚀 Key Features
- **DenseNet-121 Architecture:** Leverages dense connections to improve gradient flow and feature reuse.
- **Advanced Preprocessing:** Includes Contrast Limited Adaptive Histogram Equalization (CLAHE) for enhanced lung visibility.
- **Explainable AI:** Integrated Grad-CAM visualization to highlight suspect regions for clinical review.
- **Kaggle-Ready Data Loading:** Streamlined pipeline for high-throughput training and inference.

## 🏗️ Architecture
- **Backbone:** Pre-trained DenseNet-121.
- **Input:** 224x224 grayscale radiographs.
- **Output:** Probability score + localization heatmap.

## 🛠️ Usage
```bash
pip install -r requirements.txt
python inference.py --image sample_xray.png --weights model_final.pth
```