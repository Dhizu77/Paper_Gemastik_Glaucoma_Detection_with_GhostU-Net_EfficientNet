# GlaucoNet: Ghost U-Net and EfficientNetV2 for Glaucoma Detection

This repository contains the results of our research conducted for GEMASTIK XVII in the Data Mining category. We developed a Ghost U-Net model for retinal image segmentation and an EfficientNetV2-B2 model for classification, aimed at early detection of glaucoma.

Authors:
Willy Wijaya (Author 1): d1041221028@student.untan.ac.id
Dhimas Fauzan Al Asri (Author 2): d1041221036@student.untan.ac.id
Hergi Alfizar (Author 3): d1041221018@student.untan.ac.id
Fauzan Asrin (Supervisor)
## Overview

Glaucoma is the second leading cause of irreversible blindness globally, often undetected in its early stages due to the complex diagnosis process. **GlaucoNet** is a solution that leverages deep learning techniques to help clinicians detect glaucoma early, providing high accuracy and efficient resource usage.

- **Ghost U-Net** was used for optic cup and disc segmentation, achieving a segmentation accuracy of **90.78%**.
- **EfficientNetV2-B2** was used for classifying the segmented images, achieving a classification accuracy of **92.75%** on the test set.

This solution is designed to detect glaucoma with **high accuracy** and **low computational cost**, making it ideal for deployment in clinics with limited resources.

## Key Features

- **Accurate Retina Segmentation**: Ghost U-Net effectively segments the optic cup and disc from retinal images.
- **High Classification Accuracy**: EfficientNetV2-B2 classifies retinal images for glaucoma detection with 92.75% accuracy.
- **Resource Efficiency**: Both models are designed to perform well even in resource-constrained environments, suitable for remote or rural clinics.
  
## Results

| Model             | Task             | Accuracy (Test)  | Parameters       |
|-------------------|------------------|------------------|------------------|
| Ghost U-Net       | Segmentation     | 90.78%           | 1.8M             |
| EfficientNetV2-B2 | Classification   | 92.75%           | 8.9M             |
