# YOLOv8_segmentation
This code is targeted at the processing of medical imaging data—in particular, the DICOM and NRRD files—required for training a YOLOv8 segmentation model targeting regions of interest detection in the rectum project data. Extracting data, it saves images together with their labels, training a model, and evaluating it is all done without missing several result visualizations and model prediction comparisons against ground truth data.

Analysis of Results

Data Preparation: Successfully extracts and processes frames from DICOM and NRRD files, creating labeled datasets for training, validation, and testing.

Model Training: Utilizes YOLOv8 for segmentation, showing efficient use of GPU resources if available.

Visual Outputs: This provides detailed visualization of training progress and model performance to understand the model's accuracy and areas for improvement.

Prediction and Evaluation: Show how an already trained model could be loaded, how to make predictions, and include in it a method for running the predictions beside the truth data to show model accuracy.
