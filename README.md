# Age Detection Using Deep Learning

This project fine-tunes a pre-trained CNN model (MobileNetV2) to predict a person's age using facial images from the UTKFace dataset.

Dataset:

-Source: UTKFace

-Path: C:/Users/HP/age_detection/dataset

-Data Format: Image filenames contain age, gender, and race (e.g., 25_1_0.jpg)

Model Details:

-Base Model: MobileNetV2 (pre-trained on ImageNet)

-Input Shape: 100x100x3

-Custom Layers: Global Average Pooling → Dense → Output

-Loss Function: Mean Squared Error

-Metric: Mean Absolute Error (MAE)

Results:

-Final Validation MAE: 8.62 years

-Evaluation: Age predictions grouped into age brackets (0-9, 10-19, ..., 70+)

-Classification Accuracy (on grouped ages): 48 percent

-Confusion Matrix and Classification Report generated and included

Requirements:

-Install dependencies with:

-pip install -r requirements.txt

Model File:

-Saved model: age_model.h5

How to Run:

-Open age_detection.ipynb in Jupyter Notebook

-Run all cells to train the model or load the existing saved model

-Outputs include MAE score, confusion matrix, and classification report
