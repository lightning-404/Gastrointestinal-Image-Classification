# Gastrointestinal Medical Image Classification Using InceptionV3

## Project Overview

This project focuses on the classification of gastrointestinal endoscopic images into four categories using Deep Learning and Transfer Learning.

The proposed approach utilizes the pre-trained InceptionV3 architecture to extract image features and classify them into four target classes.

## Target Classes

1. Normal
2. Polyps
3. Esophagitis
4. Ulcerative Colitis

## Dataset

- **Dataset:** Kvasir-VQA
- **Source:** Hugging Face
- **Dataset URL:** https://huggingface.co/datasets/SimulaMet-HOST/Kvasir-VQA

The project uses selected gastrointestinal images after data filtering and preprocessing.

## Methodology

- Dataset filtering and image identification.
- Image preprocessing and normalization.
- Transfer Learning using InceptionV3.
- Training a new classification layer.
- Model evaluation using multiple classification metrics.
- Grad-CAM for visual model interpretability.

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Macro Average
- Confusion Matrix

## Final Results

- **Test Accuracy:** 96.58%
- **Macro Precision:** 96.45%
- **Macro Recall:** 96.71%
- **Macro F1-Score:** 96.52%

## Repository Structure

- `notebooks/`: Final training and evaluation notebook.
- `results/`: Evaluation figures and visualizations.
- `docs/`: Project documentation and presentation.
- `data/`: Dataset source and information.
- `models/`: Model information and download instructions.

## Requirements

Install the required Python libraries using:

```bash
pip install -r requirements.txt
```

## Important Note

The dataset is not included in this repository. Please refer to the original dataset source and its license and usage conditions.

## Disclaimer

This project is an academic research project for medical image classification. Its predictions are experimental and are not intended to replace professional medical diagnosis.