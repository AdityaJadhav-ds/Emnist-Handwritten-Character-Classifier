<h1 align="center">💡 EMNIST Handwritten Character Classifier</h1>

<p align="center">
  <strong>A modern Streamlit web app that recognizes handwritten digits & alphabets using a deep-learning CNN trained on the EMNIST ByClass dataset.</strong>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Framework-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"></a>
  <a href="#"><img src="https://img.shields.io/badge/UI-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"></a>
  <a href="#"><img src="https://img.shields.io/badge/Dataset-EMNIST-0052CC?style=flat-square"></a>
  <a href="#"><img src="https://img.shields.io/badge/Model-CNN-blue?style=flat-square"></a>
  <a href="#"><img src="https://img.shields.io/badge/Classes-62-success?style=flat-square"></a>
</p>

---

## 🚀 Live Demo  
👉 **https://emnist-handwritten-character-classifier-aditya.streamlit.app/**  

---

## 📌 Overview

This project delivers a full **handwriting recognition system** capable of identifying:

- 🔢 **Digits** (0–9)  
- 🔠 **Uppercase letters** (A–Z)  
- 🔡 **Lowercase letters** (a–z)

Using a **Convolutional Neural Network**, the app performs:

- Image preprocessing → resizing, grayscale, inversion  
- Deep learning inference → EMNIST-trained CNN  
- Top-5 predictions → with confidence scores  
- Works with **canvas drawing** or **image upload**  

Perfect for ML learning, model deployment demos, or handwriting research.

---

## 🧠 Model Details

| Component | Description |
|----------|-------------|
| **Dataset** | EMNIST ByClass (62 classes) |
| **Image Size** | 28×28 grayscale |
| **Architecture** | Multi-layer CNN |
| **Framework** | TensorFlow / Keras |
| **Output** | 62-dim probability vector |
| **Model File** | `cnn_emnist_digits_alphabets.pkl` |

---

## 🎨 App Features

- ✍️ **Draw** on a digital canvas  
- 📤 **Upload** a handwritten PNG/JPG image  
- ⚡ **Real-time predictions**  
- 📊 **Top-5 probability chart**  
- 🧩 **Context-aware prediction**  
- 🚀 Fast, lightweight, beginner-friendly UI  

---

## 📁 Repository Structure

Emnist-Handwritten-Character-Classifier/
├── app.py                           # Streamlit app (UI + inference)
├── cnn_emnist_digits_alphabets.pkl  # Pre-trained CNN model
├── requirements.txt                 # Dependencies
├── README.md                        # Project documentation
└── CNN_EMNIST_digit&Alphabet.zip    # Model/dataset archive

## ⚙️ Installation

git clone https://github.com/AdityaJadhav-ds/Emnist-Handwritten-Character-Classifier
cd Emnist-Handwritten-Character-Classifier

pip install -r requirements.txt

## ▶️ Run the App

streamlit run app.py


