# Age Detection Project

This project trains a CNN model to predict human age in 20-year bins using the UTKFace dataset.

## Files included:

training_model.ipynb : Jupyter Notebook with complete training and evaluation code.

final_age_model_4bins.h5 : Saved trained model.

requirements.txt : Python packages required.

## Dataset: Download an extract the dataset from here: https://www.kaggle.com/datasets/jangedoo/utkface-new

## Model details:

Model: EfficientNetB0 pretrained on ImageNet

Image size: 96x96

Classes: 20 age bins

Metrics: Accuracy, confusion matrix, precision, recall

Usage:

Install required packages from requirements.txt

Run training_model.ipynb in Jupyter Notebook

Requirements are listed in requirements.txt
