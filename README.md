# ♻️ Waste Management System using Machine Learning

An AI-based Waste Management System that automatically classifies waste using image recognition.  
The project includes a **web application (Flask)** and an **offline Android application** using **TensorFlow Lite**.

---

## 📌 Project Overview

Traditional waste sorting is manual, inefficient, and error-prone.  
This project solves the problem by using **Computer Vision and Deep Learning (CNN)** to classify waste images into categories such as Plastic, Paper, Metal, Glass, etc.

Initially developed as a **web-based system**, the project was later transitioned into an **offline Android application** for better accessibility and portability.

---

## 🎯 Objectives

- Automate waste classification using image recognition  
- Reduce human effort and sorting errors  
- Provide real-time waste classification  
- Enable offline waste classification through Android app  

---

## 🧠 Technologies Used

### 🔹 Machine Learning
- Convolutional Neural Network (CNN)
- TensorFlow / Keras
- TensorFlow Lite (TFLite)

### 🔹 Web Application
- Frontend: HTML, CSS, JavaScript
- Backend: Flask (Python)
- Camera Access: `getUserMedia()` API

### 🔹 Android Application
- Android Studio
- Kotlin & XML
- CameraX API
- TensorFlow Lite (Offline ML Model)

---

## 🏗️ System Architecture

### Web Application
1. User uploads or captures an image
2. Image is sent to Flask backend
3. Image is preprocessed (224×224×3)
4. CNN model predicts waste category
5. Result is displayed on the UI

### Android Application
1. Camera captures image using CameraX
2. Image processed locally
3. TFLite model predicts waste category
4. Result shown instantly (Offline)

---

## 🧪 Model Details

- Input Shape: `224 × 224 × 3`
- Layers:
  - Conv2D
  - MaxPooling
  - Flatten
  - Dense
- Output: Waste Category (Plastic, Paper, Metal, Glass, etc.)
- Accuracy Achieved: **~91%**
- Prediction Time: **~2 seconds**

---

## ✨ Features

### Web App
- Image upload
- Live camera capture
- Real-time classification
- Fast predictions

### Android App
- Offline functionality
- Camera integration (CameraX)
- Lightweight & fast
- User-friendly UI

🚀 Results & Performance
- Accuracy: **91%**
- Real-time predictions
- Positive user feedback
- Works offline on Android devices

## 🔮 Future Enhancements
- Database integration for prediction history
- Cloud syncing for model updates
- Smart bin integration
- GPS tracking for waste bins
- Hardware integration for automated sorting
