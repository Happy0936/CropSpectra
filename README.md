CropSpectra – Crop Disease Detection System

CropSpectra is a deep learning–based web application that helps in identifying crop diseases from leaf images.
The system is designed to accurately predict diseases only for valid crop images and reject invalid/random images, making it more reliable and practical for real-world use.


🚀 Live Demo

🔗 Render App:
(https://cropspectra-g8om.onrender.com/home)


📌 Key Features

🌿 Crop disease prediction using CNN (TensorFlow/Keras)

🖼 Upload leaf images for instant prediction

❌ Automatically detects invalid / non-crop images

📊 Confidence-based filtering to avoid wrong predictions



📄 Detailed disease information:

Description

Symptoms

Treatment

Prevention

⚡ Fast, lightweight, and cloud-deployed using Render



🧠 Model Details

Framework: TensorFlow & Keras

Architecture: Convolutional Neural Network (CNN)

Input Size: 224 × 224 RGB images

Output: Crop disease class with confidence score

Validation Logic:
Predictions below confidence threshold are marked as “Not a valid crop image”





🗂 Project Structure
CropSpectra/
│── app.py
│── crop_disease_model.h5
│── classes.json
│── disease_info.json
│── requirements.txt
│── README.md
