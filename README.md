# Facial Expression Recognition System 

A deep learning-based web application that detects human faces in real-time and classifies facial expressions into multiple emotion categories using a Convolutional Neural Network (CNN).

---

##  Overview
This project uses computer vision and deep learning techniques to recognize facial expressions from images, videos, and live webcam feeds. The system integrates face detection, emotion classification, and additional features like age and gender prediction.

---

##  Features
- Real-time face detection using YOLOv2
- Emotion classification (6 classes: Happy, Sad, Angry, Fear, Surprise, Neutral)
- Age and gender prediction
- Works on images, videos, and live webcam
- Flask-based web interface
- MySQL database integration for storing predictions

---

##  Tech Stack
- Python
- TensorFlow / Keras
- OpenCV
- YOLOv2
- Flask
- MySQL

---

##  Project Architecture
1. Input (Image / Video / Webcam)
2. Face Detection (YOLOv2)
3. Preprocessing (Resize, Normalize)
4. CNN Model (Emotion Classification)
5. Additional Models (Age & Gender)
6. Output Display (Flask UI + Database Logging)

---

##  Model Details
- Custom CNN architecture
- Activation: ReLU, Softmax
- Regularization: Dropout
- Optimization: Adam Optimizer
- Loss Function: Categorical Crossentropy

---

##  Performance
- Reduced overfitting using dropout and cross-validation
- Performance monitored using accuracy and loss graphs

---

##  Dataset
- Facial expression dataset (FER-based or custom dataset)
- Preprocessing includes:
  - Resizing images
  - Normalization
  - Data augmentation

---
