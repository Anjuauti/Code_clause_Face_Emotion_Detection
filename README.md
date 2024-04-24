# Code_clause_Face_Emotion_Detection

This project focuses on using machine learning techniques, specifically Convolutional Neural Networks (CNN), for the detection of emotions in human faces. Emotion recognition plays a crucial role in various applications such as human-computer interaction, sentiment analysis, and mental health assessment.The goal of this project is to develop a CNN-based model capable of analyzing facial expressions and identifying the underlying emotions. The model will be trained on a dataset containing labeled facial images representing different emotions such as happiness, sadness, anger, surprise, fear, disgust, and neutrality.

# Overview

Image Data: The model is trained on a dataset of around 28709 images. The model is trained on a dataset of thousands of labeled facial images, covering emotions like happiness, sadness, anger, surprise, fear, disgust, and neutrality.
CNN Architecture: Utilizes a deep CNN architecture, employing convolutional and pooling layers to extract hierarchical features from facial images. It's optimized to discern subtle facial cues indicative of different emotions.
Image Augmentation: Augments training data with techniques like rotation, flipping, zooming, shifting, and scaling to enhance model robustness. This enables learning from diverse facial expressions and lighting conditions.
Transfer Learning: Fine-tunes a pre-trained CNN model on the face emotion dataset. Leveraging knowledge from general image datasets, it effectively captures facial features and nuances associated with emotions.
GitHub Actions: Implements Continuous Integration (CI) using GitHub Actions for automated testing. Ensures stability by running unit tests, evaluating model performance, and validating code changes. Maintains quality and reliability of the face emotion detection system.

# How to use

Dataset: You can find the dataset used for training is [Here](https://www.kaggle.com/code/myr9988/facial-emotion-recognition-image-classification/input)

Training: The model training script is available in the face_emotion_detection.ipynb directory. Adjust the hyperparameters as needed.
Inference: Once trained, the model can be used for inference on new images. 
# Acknowledgments

Special thanks to CodeClause for providing the internship opportunity.
