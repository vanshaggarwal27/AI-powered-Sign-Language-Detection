# 🤟 American Sign Language (ASL) Image Classification using CNN

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![TensorFlow 2.x](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://tensorflow.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project implements a **Convolutional Neural Network (CNN)** to classify **American Sign Language (ASL) hand gesture images** into their respective alphabet classes (A-Z).

---

## 📌 Project Overview
ASL is a vital communication method for the deaf and hard-of-hearing community. This project aims to automate the recognition of hand signs using deep learning.

The pipeline includes:
- **Image Preprocessing:** Grayscale conversion and normalization.
- **Data Augmentation:** Real-time transformations to prevent overfitting.
- **CNN Training:** Feature extraction using deep convolutional layers.
- **Evaluation:** Analyzing performance via accuracy/loss curves.



---

## 🧠 Model Architecture
The model is built using a sequential architecture designed for spatial feature extraction:
* **Convolutional Layers:** 3 blocks of Conv2D for identifying edges and shapes.
* **Batch Normalization:** Applied after each conv layer for faster convergence.
* **MaxPooling:** Reduces the spatial dimensions of the data.
* **Dropout (0.5):** Ensures the model generalizes well to unseen images.
* **Softmax Output:** Classifies the input into one of the 26/29 alphabet categories.

---

## ⚙️ Tech Stack
* **Language:** Python
* **Deep Learning:** TensorFlow / Keras
* **Data Science:** NumPy, Matplotlib, Scikit-learn
* **Computer Vision:** OpenCV

---

## 👨‍💻 Author
Vansh Aggarwal B.Tech CSE Student

📧 Email Me: vansh27102005@gmail.com | 🔗 LinkedIn : https://www.linkedin.com/in/vanshaggarwal27/ 

---

## 📜 License
This project is open-source and available under the MIT License.


