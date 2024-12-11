# handwritten-tect-recognition
## Overview
This project implements a deep learning-based model for recognizing handwritten text using the IAM dataset. The system is capable of detecting and interpreting handwritten words from images, converting them into digital text for various applications.

## Key Features
- Dataset: Uses the IAM dataset with over 115,000 labeled words contributed by 657 writers.
- Preprocessing: Includes resizing, normalizing images, and mapping characters to integers.
- Model Architecture:
- Convolutional Neural Networks (CNNs): For feature extraction.
- Recurrent Neural Networks (RNNs): With bidirectional LSTM layers for sequence modeling.
- Connectionist Temporal Classification (CTC): For aligning predictions with target sequences.
- Implementation: Includes visualization of data, training, validation, and accuracy monitoring.
- Evaluation Metric: Edit distance for measuring recognition accuracy
