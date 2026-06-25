🍔 FOOD RECOGNITION & CALORIE ESTIMATION USING DEEP LEARNING

====================================================
📌 PROJECT OVERVIEW
====================================================

This project implements a Food Recognition and Calorie Estimation System using Transfer Learning with MobileNetV2. The model identifies food items from images and provides an estimated calorie value for the predicted food category.

The objective is to assist users in understanding their dietary intake and promote healthier food choices through AI-powered image classification.

====================================================
🎯 PROJECT OBJECTIVES
====================================================

✅ Recognize food items from images

✅ Estimate calorie values for detected foods

✅ Apply Transfer Learning for efficient classification

✅ Visualize model performance using training metrics

✅ Generate prediction confidence analysis

====================================================
🧠 TECHNOLOGIES USED
====================================================

• Python
• TensorFlow
• Keras
• MobileNetV2
• NumPy
• Matplotlib

====================================================
📂 DATASET
====================================================

Dataset Name : Food-101

The dataset contains 101 food categories with thousands of food images used for training and evaluation.

====================================================
⚙️ MODEL ARCHITECTURE
====================================================

📸 Input Image (128 × 128 × 3)

⬇️

🔄 Data Augmentation
   • Random Flip
   • Random Rotation
   • Random Zoom

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

====================================================
🚀 KEY FEATURES
====================================================

✨ Automated Food Recognition

✨ Transfer Learning with MobileNetV2

✨ Real-Time Food Prediction

✨ Calorie Estimation System

✨ Accuracy & Loss Visualization

✨ Prediction Confidence Analysis

====================================================
📈 TRAINING CONFIGURATION
====================================================

Image Size      : 128 × 128

Batch Size      : 32

Epochs          : 5

Optimizer       : Adam

Loss Function   : Sparse Categorical Crossentropy

====================================================
📊 OUTPUT RESULTS
====================================================

1️⃣ Accuracy & Loss Graph

Displays training and validation performance across epochs.

Output File:
accuracy_loss_graph.png


2️⃣ Food Prediction Result

The model predicts the food category from a test image and displays prediction confidence.

Output File:
food_prediction_result.png


3️⃣ Calorie Estimation

Estimated calorie values for predicted foods.

Examples:

🍕 Pizza            → 285 Calories

🍔 Hamburger        → 295 Calories

🍨 Ice Cream        → 207 Calories

🍩 Donuts           → 452 Calories

====================================================
🏆 LEARNING OUTCOMES
====================================================

🔹 Deep Learning

🔹 Transfer Learning

🔹 Computer Vision

🔹 TensorFlow & Keras

🔹 Image Classification

🔹 Model Evaluation

🔹 AI-Based Food Analytics

====================================================
📁 GENERATED FILES
====================================================

📊 accuracy_loss_graph.png

📈 food_prediction_result.png

💾 food_classifier.h5

====================================================
🌟 FUTURE ENHANCEMENTS
====================================================

🚀 Improve prediction accuracy through fine-tuning

🚀 Expand calorie database for all 101 food categories

🚀 Develop a Streamlit Web Application

🚀 Real-Time Food Recognition using Webcam

🚀 Nutritional Analysis Dashboard

====================================================
🙏 ACKNOWLEDGEMENT
====================================================

This project was completed as part of my Machine Learning Internship at Prodigy InfoTech. The task provided practical exposure to Deep Learning, Computer Vision, Transfer Learning, and AI-powered Food Recognition systems.

I am grateful to Prodigy InfoTech for providing this opportunity to enhance my technical and problem-solving skills through hands-on projects.
