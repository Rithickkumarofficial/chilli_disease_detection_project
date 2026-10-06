# 🌱 Chilli Plant Disease Detection

An AI-powered computer vision system for detecting diseases in chilli plant leaves using deep learning and image classification.

## 📌 Overview

Chilli plants are affected by various diseases that can reduce crop quality and yield. Early identification of these diseases can help farmers take timely preventive action.

This project uses a Convolutional Neural Network (CNN) to analyze chilli leaf images and classify them into different health conditions.

The system is designed as an end-to-end application with separate machine learning, backend, and frontend components.

## 🎯 Problem Statement

Manual identification of plant diseases can be time-consuming and requires agricultural expertise.

The objective of this project is to develop an AI-based system that can:

- Analyze chilli plant leaf images
- Detect potential diseases
- Classify the detected condition
- Provide prediction confidence
- Provide a simple interface for users

## 🔍 Disease Classes

The current system focuses on:

- Healthy Leaf
- Leaf Anthracnose
- Leaf Curl Virus

## 🧠 Approach

The system follows this pipeline:

```text
Chilli Leaf Image
        ↓
Image Preprocessing
        ↓
CNN Model
        ↓
Feature Extraction
        ↓
Disease Classification
        ↓
Prediction + Confidence Score

🛠️ Tech Stack
Machine Learning
- Python
- TensorFlow / Keras
- Convolutional Neural Networks (CNN)
- Image Processing
- NumPy
Backend
- Python
- Flask
- REST API
Frontend
- HTML
- CSS
- JavaScript
Tools
- Git
- GitHub
- Google Colab / Jupyter Notebook

📁 Project Structure
chilli_disease_detection_project/
│
├── frontend/
│   ├── index.html
│   ├── package.json
│   └── package-lock.json
│
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   └── package-lock.json
│
├── ml/
│   ├── train.py
│   └── requirements.txt
│
├── data/
│
└── README.md

⚙️ Workflow
1. Dataset Preparation
Chilli leaf images are collected and organized according to their disease categories.
2. Image Preprocessing
Images are prepared for model training through preprocessing operations such as resizing and normalization.
3. Model Training
A CNN-based deep learning model is trained using labeled chilli leaf images.
4. Model Evaluation
The trained model is evaluated to understand its classification performance.
5. Prediction
A new chilli leaf image is provided to the system.
The model predicts the corresponding disease category and confidence score.
6. Application
The trained model is integrated with the backend and frontend to provide an accessible prediction interface.
🚀 Future Improvements
- Improve model accuracy with a larger dataset
- Experiment with transfer learning models
- Add more chilli plant diseases
- Extend detection to other crops
- Develop a mobile application
- Add multilingual support
- Integrate cloud and IoT-based monitoring
🌾 Applications
This project can potentially assist:
- Farmers
- Agricultural researchers
- Students
- Plant disease monitoring systems
- Smart agriculture applications
⚠️ Disclaimer
This project is an educational AI/ML prototype and should not be considered a replacement for professional agricultural diagnosis.
👨‍💻 Author
Rithick Kumar
AI & Data Science Student
GitHub: https://github.com/Rithickkumarofficial

The future-improvement ideas also align with your project documentation, which proposes mobile deployment, expanded disease coverage, cloud/IoT integration, and multilingual support. :chatgpt-content-reference{index="2"}

### But don't push this yet

There is **one thing I want to verify first**: your actual `train.py` and `backend/app.py`.

Run:

```bash
cat chilli_disease_detection_project/ml/train.py