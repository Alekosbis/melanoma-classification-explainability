# Melanoma Classification and Explainability

This repository contains the technical material developed for a diploma thesis on the recognition and classification of skin lesions using deep learning and explainable AI techniques.

The experiments focus on dermoscopic image classification, model evaluation and visual explainability. The main datasets used in the thesis include HAM10000, ISIC, SIIM-ISIC 2020, PH2, Derm7pt and PAD-UFES-20. Due to size and access restrictions, the datasets are not included in this repository.

## Repository Structure

- `notebooks/`: Jupyter/Colab notebooks used for the main experiments.
- `scripts/`: Python scripts for preprocessing, training, evaluation and explainability.
- `results/`: selected outputs, metrics, confusion matrices and explainability examples.
- `requirements.txt`: main Python libraries used in the experiments.

## Main Methods

The experiments include:

- CNN-based models such as ResNet, EfficientNet and ConvNeXt.
- Transformer-based models such as Vision Transformer and Swin Transformer.
- Fine-tuning experiments on skin lesion datasets.
- Evaluation using accuracy, precision, recall, F1-score and AUC.
- Explainability techniques including Grad-CAM, Grad-CAM++, Score-CAM and SHAP.

## Notes

The repository is intended as supplementary technical material for the thesis. It does not include the original datasets or large model checkpoints. Dataset paths may need to be adjusted depending on the local or Google Drive environment.
