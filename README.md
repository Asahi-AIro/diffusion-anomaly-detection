# Diffusion Anomaly Detection on Medical Images

## Overview
This project explores the use of diffusion models for anomaly detection in medical imaging. The goal is to identify abnormal regions in CT or X-ray scans by leveraging the generative power of diffusion-based reconstruction.

## Background
I studied medical image engineering at Tohoku University, where I focused on AI-based anomaly detection in radiology. This project is an extension of that work, applying state-of-the-art diffusion models (e.g., DDPM) for unsupervised detection.

## Key Ideas
- Use diffusion models to reconstruct "normal" images
- Compare original vs. reconstructed to detect anomalies
- Apply to real-world X-ray or CT scan datasets

## Features
- Preprocessing for medical images (DICOM → PNG)
- Diffusion-based reconstruction using pretrained models
- Pixel-wise anomaly heatmap generation

## Technologies
- Python
- PyTorch
- MONAI or MedPy (for medical imaging)
- OpenCV, NumPy

## Status
🟡 In Progress — building prototype reconstruction pipeline

## Example Output (to be added)
_(Heatmap comparisons of original vs. reconstructed images)_

## Author
Asahi Ruike（Asarse）
