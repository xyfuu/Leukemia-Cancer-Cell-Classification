# Leukemia Cancer Cell Classification App (Android + TFLite)

This project is an **Android application** for classifying leukemia cancer cells based on **microscopic images**, detecting whether a cell is **normal** or **abnormal**. It integrates a **TensorFlow Lite** model into an Android Studio application for real-time image-based inference.

## 🔬 About the Project

Leukemia is a type of cancer that affects blood-forming tissues, including the bone marrow and lymphatic system. Early detection is crucial for effective treatment. This application aims to assist in the early diagnosis of leukemia by classifying cell images uploaded through the app.

### Features
- 📱 Android app built using **Android Studio**
- 🧠 Deep learning model trained using **TensorFlow/Keras**
- 📦 Integrated into Android using **TensorFlow Lite (TFLite)**
- 📤 Supports image upload for classification
- ✅ Outputs prediction: **"Normal"** or **"Abnormal"**

## 🧠 Model Training

The model was trained using a custom dataset of leukemia cell images. The architecture used is based on state-of-the-art convolutional neural networks (CNNs). The training script is written in **Python** and is available in this repository.

> ⚠️ **Note**: Only the Python code used to train the model is committed to this GitHub repository. Other project files such as:
> - Android Studio project (Gradle files, assets, etc.)
> - Trained `.tflite` model
> - Training dataset  
> are too large to be pushed to GitHub and are available separately.

## 📂 Download Full Project & Data

You can download the full project including:
- Android Studio project files
- TFLite model
- Training dataset  

From this Google Drive link:

**📥 [Download Full Project & Data](https://drive.google.com/file/d/1vOZSrPgyNSJ4isCie9xIMvpGfdP-E6ET/view?usp=sharing)**  

## 📷 How to Use

1. Clone this repository to get the training code.
2. Download the Android project and model from the Google Drive link.
3. Open the project in Android Studio.
4. Connect a device or use an emulator.
5. Upload a cell image and let the app classify it as **normal** or **abnormal**.

