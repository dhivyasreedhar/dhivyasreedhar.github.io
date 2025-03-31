---
title: "Lane Detection for Self-Driving Cars"
excerpt: "A VGG-16-based CNN implementation for road segmentation"
collection: ml
---

## Project Overview
Implemented a sophisticated lane detection system for self-driving vehicles using deep learning and computer vision techniques. The system processes road imagery to accurately identify and track lane markings, providing essential information for autonomous navigation.

## Technical Approach
- Developed a **VGG-16-based Convolutional Neural Network (CNN)** for road segmentation
- Trained and validated on the industry-standard **KITTI Road/Lane Detection Evaluation dataset**
- Implemented advanced preprocessing techniques:
  - Perspective transformation to obtain bird's-eye view of the road
  - Sobel edge detection for identifying gradient changes
  - Color thresholding in multiple color spaces to isolate lane markings
- Enhanced detection accuracy through:
  - Sliding window lane detection approach
  - Region-of-interest masking to focus processing on relevant road areas
- Leveraged **transfer learning** to improve model performance and reduce training time

## Technologies Used
- Python
- TensorFlow
- Keras
- Pandas
- NumPy
- OpenCV

## Results
The system achieved **98.58% pixel-wise accuracy** in lane segmentation, demonstrating excellent performance across various road conditions and scenarios present in the KITTI dataset.

[See Repo Here](https://github.com/dhivyasreedhar/Lane-detection-for-self-driving-cars)