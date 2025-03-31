---
title: "COVID-19 AI Diagnosis Using Only Cough Recordings"
excerpt: "A deep learning approach for COVID-19 pre-screening that detects asymptomatic patients through audio analysis."
collection: ml
---

## Project Overview
Developed an innovative, non-invasive COVID-19 pre-screening tool that analyzes cough recordings to detect asymptomatic patients. This AI-powered solution enables rapid, remote screening without requiring physical testing infrastructure.

## Technical Approach
- Collected and processed audio samples of cough recordings from both COVID-19 positive and negative cases
- Extracted acoustic features using **Mel Frequency Cepstral Coefficients (MFCC)** to capture the unique spectral characteristics of COVID-induced coughs
- Engineered a custom **Convolutional Neural Network (CNN)** architecture optimized for audio pattern recognition
- Implemented data augmentation techniques to enhance model generalization
- Applied transfer learning to leverage pre-trained audio classification models

## Technologies Used
- Python
- TensorFlow
- Librosa (audio analysis library)
- Pandas
- NumPy
- Signal processing techniques

## Results
- Achieved **98% accuracy** in identifying COVID-19 positive cases, including asymptomatic patients
- Demonstrated a **40% improvement in early detection rates** compared to standard screening methods
- Created a practical tool to aid in the timely isolation of potential COVID-19 carriers
- Contributed to public health efforts by providing a scalable, accessible screening solution



[See Repo Here](https://github.com/dhivyasreedhar/Covid19CoughDetection)