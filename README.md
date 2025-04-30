# 🐦 Bird is the Word - BirdCLEF+ 2025
### IDS 705 Principles of Machine Learning Final Project

This repository contains the code and documentation for our final project in **IDS 705: Data Science Practicum** at Duke University. We participated in the [BirdCLEF+ 2025 Kaggle competition](https://www.kaggle.com/competitions/birdclef-2025/overview), focused on building machine learning models to identify species (birds, amphibians, mammals, and insects) from audio recordings captured in Colombia's Middle Magdalena Valley.

## 📚 Background and Motivation

Biodiversity loss is one of the most urgent environmental challenges today. Traditional field-based species surveys are time-consuming and expensive. The **BirdCLEF+ 2025 competition** encourages machine learning researchers to classify animal species based on audio clips, supporting ecological conservation efforts.

Our project explores a range of audio processing and classification techniques to identify animal species from short sound clips. We go beyond the competition baseline to compare different input formats, data sources, and loss functions, aiming to improve accuracy, robustness, and efficiency of bioacoustic classification.

## 🧪 Project Overview

We conducted 5 structured experiments:

| Experiment | Focus Area                                 | Result Summary                          |
|------------|---------------------------------------------|------------------------------------------|
| 1          | Model architecture comparison               | ResNet18 chosen as baseline              |
| 2          | Multi-domain learning (2024 + 2025 data)    | Marginal gain, added complexity          |
| 3          | Input type (Spectrogram vs. MFCC)           | Spectrograms outperform MFCCs            |
| 4          | Reduced input complexity                    | Lower accuracy, faster training          |
| 5          | Handling class imbalance (focal loss, weights) | Did not outperform cross-entropy loss |

The best model achieved **72.03% accuracy** and **0.9802 ROC AUC** using a **ResNet18 model** trained on **Mel spectrograms**.

## 👥 Contributors
- Nathan Bush
- Jenny Chen
- Nruta Choudhari
- Loo Si Min
- Atreya Tadepalli


link to models and data: https://www.kaggle.com/datasets/nathanbush4611/brid-final-models-and-data
