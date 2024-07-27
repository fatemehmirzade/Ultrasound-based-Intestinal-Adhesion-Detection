## Introduction
This is a medical imaging data processing project focused on DICOM and NRRD files for training a YOLOv8 segmentation model to detect regions of interest in the rectum project data. This whole pipeline contains data extraction, image labeling, model training, and evaluation. Special emphasis has been given to the visualization of results and comparison of model predictions against ground truth data.

![image](https://github.com/user-attachments/assets/d4f1be49-598e-446e-8745-7c57f9aa583f)
|:-:|
|YOLOv8 Architecture

## Data Preparation
The data preparation phase involves the successful extraction and processing of frames from DICOM and NRRD files. This step creates labeled datasets, which are then divided into training, validation, and testing sets. Ensuring accurate and comprehensive data labeling is crucial for the effective training of the segmentation model.

![image](https://github.com/user-attachments/assets/8322e799-8607-4f48-bb4e-af61b89b5544)
|:-:|
|Mask samples

## Hyperparameters and Training
In this phase, segmentation is done with the help of YOLOv8; it efficiently makes use of available resources on the GPUs to speed up computation. Other key hyperparameters, such as learning rate, batch size, and number of epochs, could also be tuned to show the model's potential. Observatory practices on training progress in terms of loss curves and accuracy metrics are employed to aid in fine-tuning these parameters.

## Evaluation Metrics and Results 
The testing phase demonstrates how to load a trained model and generate a prediction. It evaluates the model against standard metrics: precision, recall, IoU. Added a method for making predictions with ground truth data to facilitate visual inspection of the model's accuracy. Detailed visualization outputs are provided to understand how well or badly your model works—shows comparisons between predicted segmentations and true labels. This paper presents a full pipeline of medical image segmentation based on YOLOv8, from data preparation to model evaluation, while putting much emphasis on result visualization and accuracy assessment.

![image](https://github.com/user-attachments/assets/2c7f4142-3305-4dd0-ae30-bef2b82c9c0b)
|:-:|
|Percision-Confidence Curve
