# 🍔 Food Recognition & Calorie Estimation using Deep Learning

## 📌 Project Overview

This project implements a Food Recognition and Calorie Estimation System using Transfer Learning with MobileNetV2. The model identifies food items from images and provides an estimated calorie value for the predicted food category.

The objective is to assist users in understanding their dietary intake and promote healthier food choices through AI-powered image classification.

---

## 🎯 Project Objectives

✅ Recognize food items from images

✅ Estimate calorie values for detected foods

✅ Apply Transfer Learning for efficient classification

✅ Visualize model performance using training metrics

✅ Generate prediction confidence analysis

---

## 🧠 Technologies Used

• Python

• TensorFlow

• Keras

• MobileNetV2

• NumPy

• Matplotlib

---

## 📂 Dataset

**Dataset:** Food-101

The dataset contains 101 food categories with thousands of food images used for training and evaluation.

---

## ⚙️ Model Architecture

📸 Input Image (128 × 128 × 3)

⬇️

🔄 Data Augmentation
- Random Flip
- Random Rotation
- Random Zoom

⬇️

🧠 MobileNetV2 (Pre-trained on ImageNet)

⬇️

📊 Global Average Pooling

⬇️

🎯 Dense Softmax Layer

⬇️

🍽️ Food Category Prediction

⬇️

🔥 Calorie Estimation

---

## 🚀 Key Features

✨ Automated Food Recognition

✨ Transfer Learning with MobileNetV2

✨ Real-Time Food Prediction

✨ Calorie Estimation System

✨ Accuracy & Loss Visualization

✨ Prediction Confidence Analysis

---

## 📈 Training Configuration

- Image Size: 128 × 128
- Batch Size: 32
- Epochs: 5
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy

---

## 📊 Output Results

### 📈 Accuracy & Loss Graph

Displays training and validation performance across epochs.

**Output File:**
- accuracy_loss_graph.png

### 🍽️ Food Prediction Result

The model predicts the food category from a test image and displays confidence scores.

**Output File:**
- food_prediction_result.png

### 🔥 Calorie Estimation

Examples:

🍕 Pizza → 285 Calories

🍔 Hamburger → 295 Calories

🍨 Ice Cream → 207 Calories

🍩 Donuts → 452 Calories

---

## 🏆 Learning Outcomes

🔹 Deep Learning

🔹 Transfer Learning

🔹 Computer Vision

🔹 TensorFlow & Keras

🔹 Image Classification

🔹 Model Evaluation & Visualization

🔹 AI-Based Food Analytics

---

## 📁 Generated Files

📓 food_recognition.ipynb

📊 accuracy_loss_graph.png

📈 food_prediction_result.png

💾 food_classifier.h5

📄 README.md
---

## 🌟 Future Enhancements

🚀 Improve prediction accuracy through fine-tuning

🚀 Expand calorie database for all food categories

🚀 Develop a Streamlit Web Application

🚀 Real-Time Food Recognition using Webcam

🚀 Nutritional Analysis Dashboard

---

## 🙏 Acknowledgement

This project was completed as part of my Machine Learning Internship at Prodigy InfoTech.

I am grateful to Prodigy InfoTech for providing this opportunity to gain hands-on experience in Deep Learning, Computer Vision, Transfer Learning, and AI-powered Food Recognition systems.

---

⭐ If you found this project interesting, consider giving it a star on GitHub!
