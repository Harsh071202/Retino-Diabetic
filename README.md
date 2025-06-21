# 👁️ Diabetic Retinopathy Detection using CNN

This project detects the severity of diabetic retinopathy using a Convolutional Neural Network (ResNet50) based image classification model. Built with PyTorch and deployed as an interactive web app using Streamlit, it allows users to upload or capture retinal images and get a prediction instantly.

## 🩺 Problem Statement

Diabetic Retinopathy (DR) is a diabetes-related eye disease that can lead to vision loss if not diagnosed early. This project aims to provide an AI-based diagnostic assistant that can classify DR into 5 stages based on retinal images.

## 🧠 Model Architecture

- **Model:** ResNet50 (pretrained)
- **Modified Layer:** Fully connected (FC) layer adapted for 5 DR stages
- **Classes:**
  - No_DR
  - Mild
  - Moderate
  - Severe
  - Proliferate_DR

## 💻 Technologies Used

- **Python**
- **PyTorch** – Model training and inference
- **Torchvision** – Pretrained ResNet50
- **Streamlit** – Web app UI for prediction
- **PIL** – Image handling
- **MySQL (optional)** – Store patient data
- **OpenCV/Camera Input** – For real-time image capture

## 🧪 Features

- Capture or upload retina images
- Predict DR stage using deep learning
- User form for name, email, age, and medical history
- Custom description for each prediction
- Option to save prediction details in a SQL database


