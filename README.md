# RSNA Knee Abnormality Detection

## Overview

This repository contains the development of a Deep Learning solution for the Kaggle competition:

**RSNA Knee Abnormality Detection**

The objective of this project is to develop a machine learning model capable of detecting abnormalities in knee MRI scans using medical imaging techniques and convolutional neural networks (CNNs).

This project was developed as an individual university assignment focused on applying Data Science, Machine Learning, and Computer Vision methodologies to a real-world medical imaging problem.

---

## Competition Information

Competition:
RSNA Knee Abnormality Detection

Platform:
Kaggle

Competition Link:
https://www.kaggle.com/competitions/rsna-knee-abnormality-detection

Final Goal:
Maximize the competition evaluation score while maintaining a reproducible and well-documented machine learning workflow.

---

## Problem Statement

Magnetic Resonance Imaging (MRI) is commonly used to diagnose knee injuries and abnormalities. Manual inspection of MRI scans is time-consuming and requires specialized expertise.

The goal of this project is to build an automated system capable of identifying abnormal knee MRI studies using Deep Learning models trained on labeled medical imaging data.

---

## Project Objectives

- Understand the competition requirements.
- Perform exploratory data analysis (EDA).
- Develop preprocessing pipelines for MRI images.
- Build baseline machine learning models.
- Implement advanced deep learning architectures.
- Optimize model performance through experimentation.
- Submit predictions to the Kaggle leaderboard.
- Document findings and results.

---

## Technologies Used

### Programming Language

- Python 3.x

### Libraries

- PyTorch
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- OpenCV
- Torchvision
- Albumentations
- Jupyter Notebook

---

## Repository Structure

```text
RSNA-Knee-Project
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Preprocessing.ipynb
│   ├── 03_Baseline_Model.ipynb
│   └── 04_Final_Model.ipynb
│
├── src/
│   ├── dataset.py
│   ├── model.py
│   ├── train.py
│   ├── evaluate.py
│   └── predict.py
│
├── outputs/
│   ├── figures/
│   ├── logs/
│   └── submissions/
│
├── models/
│
├── requirements.txt
│
├── README.md
│
└── report/