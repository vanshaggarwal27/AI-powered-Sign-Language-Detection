# 🤟 American Sign Language (ASL) Image Classification using CNN

This project implements a **Convolutional Neural Network (CNN)** to classify **American Sign Language (ASL) hand gesture images** into their respective alphabet classes. The model is built and trained using deep learning techniques to recognize hand signs from images accurately.

---

## 📌 Project Overview

American Sign Language (ASL) is a vital communication method for the deaf and hard-of-hearing community. This project aims to automate ASL alphabet recognition using computer vision and deep learning.

The project covers the complete ML pipeline:
- Image preprocessing
- CNN model building
- Training and validation
- Model evaluation
- Prediction on unseen images

---

## 🧠 Model Architecture

The CNN model consists of:
- Convolutional (Conv2D) layers for feature extraction  
- Batch Normalization for faster convergence  
- MaxPooling layers to reduce spatial dimensions  
- Dropout layers to prevent overfitting  
- Fully Connected (Dense) layers for classification  

---

## 📂 Dataset

- The dataset contains labeled images of **ASL alphabet hand signs**
- Each class represents a letter of the English alphabet
- Images are resized and normalized before training

> Dataset Source: Public ASL image dataset (e.g., Kaggle)

---

## ⚙️ Tech Stack

- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Matplotlib**
- **OpenCV**
- **Jupyter Notebook**

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/asl-cnn-classifier.git
