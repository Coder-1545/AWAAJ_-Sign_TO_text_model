# Sign-to-Text Recognition using YOLO (IPSL)

## Project Overview

This project implements a **Sign-to-Text recognition system** that detects and classifies **Indian–Pakistani Sign Language (IPSL) gestures** using a deep learning-based object detection model.

The system uses the **YOLO (You Only Look Once) algorithm** to detect hand gestures in images and convert them into corresponding **alphabet and number characters**. The project includes the complete pipeline from dataset preparation and preprocessing to model training, evaluation, and prediction.

The goal of this project is to assist communication between **hearing-impaired individuals and non-sign language users** by translating sign gestures into readable text.

---

## Features

* Real-time gesture detection using the **YOLO object detection model**
* Recognition of **IPSL alphabet and numeric gestures**
* Image preprocessing and dataset preparation pipeline
* Model training and evaluation workflow
* Performance analysis using **confusion matrix and accuracy metrics**
* Visualization of results using **Matplotlib and Seaborn**

---

## Recognized Characters

The model detects and classifies the following gestures:

**Numbers**
1, 2, 3, 4, 5, 6, 7, 8, 9

**Alphabet Letters**
A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z

These gestures correspond to **Indian–Pakistani Sign Language (IPSL)** hand signs.

---

## Technologies and Libraries Used

* Python
* YOLO (Ultralytics)
* OpenCV
* TensorFlow
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* MediaPipe
* Gradio (for interaction/demo)

---

## Methodology / Implementation

### 1. Dataset Preparation

* Sign language gesture images were collected and organized into labeled classes.
* Each class represents a specific **alphabet or number gesture**.
* Images were structured into directories for training and evaluation.

### 2. Data Preprocessing

The preprocessing stage included:

* Image loading and resizing
* Data formatting for YOLO training
* Feature extraction and normalization
* Dataset splitting into **training and testing sets**

---

### 3. Model Training

* The **YOLO object detection model** was used to learn gesture patterns.
* The model was trained on labeled sign language images.
* During training, the model learns to detect hand gestures and associate them with the correct class label.

---

### 4. Prediction and Detection

Once trained, the model can:

* Detect hand gestures from images or frames
* Classify the gesture into the corresponding alphabet or number
* Convert the detected gesture into readable text

---

### 5. Model Evaluation

Model performance was evaluated using:

* **Accuracy Score**
* **Confusion Matrix**
* **Classification Report**

Visualization tools like **Seaborn and Matplotlib** were used to analyze prediction results and identify classification performance across gesture classes.

---

## Project Workflow

Dataset Collection
→ Image Preprocessing
→ Dataset Preparation
→ YOLO Model Training
→ Gesture Detection
→ Classification
→ Model Evaluation

---

## Project Structure

```
Sign-To-Text-Recognition
│
├── Sign_to_Text_model.ipynb
├── dataset
├── evaluation_results
└── README.md
```

---

## Applications

* Assistive technology for hearing and speech impaired individuals
* Real-time sign language interpretation
* Human-computer interaction using gestures
* Educational tools for learning sign language

---

## Future Improvements

* Add real-time webcam-based gesture recognition
* Improve dataset size for better accuracy
* Integrate the model into a mobile application
* Support full word and sentence generation from gestures


