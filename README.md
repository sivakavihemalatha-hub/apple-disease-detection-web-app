# 🍎 Apple Fruit Disease Detection System using Deep Learning

<p align="center">
  <img src="Apple_demo.png" width="700">
</p>

> 🚀 An AI-powered Flask web application that detects apple fruit diseases using an EfficientNet-based CNN model with high accuracy and real-time prediction capability.

---

## 🔗 Project Links
- 💻 GitHub Repository: https://github.com/sivakavihemalatha-hub/apple-disease-detection-web-app  
- 🎥 Demo Video (Ngrok): *(Add your recorded video link or hosted video here)*  

---

## 🏆 Key Highlights
- 🍎 Detects **5 apple fruit disease classes**
- 🤖 Built using **EfficientNet-based CNN model**
- 🌐 Flask-based full-stack web application
- 👤 User & Admin authentication system
- 📊 Prediction history tracking with database
- 🗄️ SQLite integration for data storage
- ⚡ Real-time image upload and prediction system

---

## 📌 Project Overview
This project is a machine learning-based web application that detects diseases in **apple fruits from images**.  
Users upload an image, and the trained deep learning model predicts the disease category along with a confidence score.

It combines **Computer Vision, Deep Learning, and Web Development** to deliver an end-to-end AI solution for agricultural disease detection.

---

## 🎯 Objective / Problem Statement
Manual identification of fruit diseases is time-consuming and requires expert agricultural knowledge.  
This system automates the process using Artificial Intelligence.

### Goals:
- Automate apple fruit disease detection using AI  
- Reduce manual inspection time  
- Enable early disease identification  
- Improve agricultural productivity using technology  

---

## 📊 Dataset Description
The dataset was collected from multiple sources:
- Kaggle  
- Mendeley  
- Agricultural image datasets  

### Disease Classes:
- Anthracnose  
- Black Pox  
- Black Rot  
- Healthy  
- Powdery Mildew  

---

## 🤖 Machine Learning Model

- **Model Type:** Convolutional Neural Network (CNN)  
- **Architecture:** EfficientNet  
- **Framework:** TensorFlow / Keras  
- **Training Platform:** Google Colab  
- **Input Size:** 224 × 224 pixels  
- **Model Format:** `.keras` file  
- **Validation Accuracy:** 87%  

---

## 📈 Model Performance

### 📌 Metrics
- Accuracy: **87%**
- Precision (avg): 86%
- Recall (avg): 87%
- F1-score (avg): 86%

### 📊 Classification Report

| Class            | Precision | Recall | F1-score | Support |
|------------------|----------|--------|----------|---------|
| Anthracnose      | 66%      | 75%    | 70%      | 69      |
| Black Pox        | 97%      | 97%    | 97%      | 92      |
| Black Rot        | 82%      | 74%    | 78%      | 134     |
| Healthy          | 95%      | 94%    | 95%      | 143     |
| Powdery Mildew   | 91%      | 94%    | 92%      | 104     |

---

## 🔁 System Workflow

1. User registers or logs in  
2. Uploads apple fruit image  
3. Image is resized to 224×224  
4. Preprocessing and normalization applied  
5. EfficientNet model processes image  
6. Disease prediction generated  
7. Confidence score displayed  
8. Result stored in SQLite database  
9. User can view prediction history  

---

## 🌐 Web Application Features

### 👤 User Features
- User registration & login  
- Upload apple fruit images  
- Get real-time disease prediction  
- View prediction history  
- Profile management  

### 🧑‍💼 Admin Features
- Admin login  
- View all user predictions  
- Manage system records  
- Monitor user activity  

---

## 🛠️ Tech Stack

### 🔹 Frontend
- HTML  
- CSS  
- JavaScript  

### 🔹 Backend
- Python (Flask Framework)  
- SQLite Database  

### 🔹 Machine Learning
- TensorFlow  
- Keras  
- EfficientNet  
- NumPy  
- PIL  

### 🔹 Deployment
- Google Colab (Model Training)  
- Ngrok (Public tunnel for demo)  

---

## 🗄️ Database Design

### Users Table
- id  
- email  
- password  
- role (admin/user)  

### History Table
- id  
- username  
- image path  
- prediction  
- confidence  
- timestamp  

---

## 🎥 Demo (Ngrok Deployment)
- Application was deployed using **Ngrok tunnel**
- Allows real-time web access during development
- Demonstrates live image upload and prediction system

👉 *(Add your demo video link here)*

---

## 📸 Screenshots

### 🏠 Home Page
<p align="center">
  <img src="Screenshots/HomePage.png" width="600">
</p>

### 🔐 Login Page
<p align="center">
  <img src="Screenshots/Login.png" width="600">
</p>

### 📝 Signup Page
<p align="center">
  <img src="Screenshots/Signup.png" width="600">
</p>

### 📊 Dashboard
<p align="center">
  <img src="Screenshots/dashboard.png" width="600">
</p>

### 📜 User History
<p align="center">
  <img src="Screenshots/History.png" width="600">
</p>

### 👤 Profile Page
<p align="center">
  <img src="Screenshots/Profile.png" width="600">
</p>

### 🧑‍💼 Admin Dashboard
<p align="center">
  <img src="Screenshots/Admin_Dashboard.png" width="600">
</p>

### 📂 All Users History
<p align="center">
  <img src="Screenshots/All_Users_History.png" width="600">
</p>

---

## 💡 Impact
This system helps in **early detection of apple fruit diseases**, reducing agricultural loss and enabling AI-based smart farming solutions.

---

## 🚀 Future Improvements
- Improve model accuracy with larger datasets  
- Deploy on cloud platforms (AWS / Render / Hugging Face Spaces)  
- Add mobile application version  
- Extend to other fruit disease detection systems  

---

## 👨‍💻 Author

**Hemalatha Sivakavi**  
📧 Email: sivakavihemalatha@gmail.com  
💻 GitHub: https://github.com/sivakavihemalatha-hub  

---

## ⭐ Note
If you find this project useful, please give a ⭐ to the repository.
