---
title: "Utterance to Phoneme Mapping using Viterbi Training"
excerpt: "An ASR model using pyramidal Bi-directional LSTM with CTC Loss for optimizing utterance-to-phoneme alignment."
collection: ml
---

## Project Overview
Developed an Automatic Speech Recognition (ASR) model that maps spoken utterances to phoneme sequences, a critical component in speech recognition systems. The project focuses on optimizing the alignment between acoustic features and phoneme representations using advanced neural architectures and training techniques.

## Technical Approach
- Implemented a **pyramidal Bi-directional LSTM** architecture to efficiently process sequential audio data
- Utilized **Connectionist Temporal Classification (CTC) Loss** to address the variable-length alignment problem between input utterances and output phoneme sequences
- Incorporated multiple feature extraction and sequence modeling approaches:
  - **CNN-pBLSTMs** (Convolutional Neural Network with pyramidal Bi-directional LSTMs)
  - **CNN-LSTMs** for hierarchical feature learning
  - **ResNets** for robust representation learning

## Decoding Strategies
- Implemented **Greedy Search** for fast, real-time phoneme sequence decoding
- Developed **Beam Search** decoding to improve accuracy by evaluating multiple high-probability phoneme sequences
- Optimized beam width and search parameters for optimal performance trade-offs

## Evaluation Method
- Employed **Levenshtein Distance** (Edit Distance) to measure character-level differences between predicted and ground-truth phoneme sequences
- Analyzed confusion matrices to identify problematic phoneme pairs
- Conducted ablation studies to quantify the contribution of each architectural component

## Technologies Used
- Python
- TensorFlow
- Keras
- PyTorch
- Signal processing libraries

## Applications
This system serves as a foundation for speech recognition applications, pronunciation assessment tools, and language learning technologies. The phoneme-level processing enables fine-grained analysis of speech patterns and accent characteristics.

[See Repo Here](link_to_your_repository)