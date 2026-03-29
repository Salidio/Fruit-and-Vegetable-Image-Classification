# Fruit-and-Vegetable-Image-Classification
This repository contains a Computer Vision solution for Case Study 03. The goal is to build a machine learning model that classifies images into two main categories: Fruits and Vegetables.

🚀 Project Overview
The project involves processing a dataset of ~36 different food items and grouping them into binary classes. I used Transfer Learning with the MobileNetV2 architecture to achieve high accuracy efficiently.
📁 Dataset Categories
Fruits: Banana, Apple, Pear, Grapes, Orange, Kiwi, Watermelon, Pomegranate, Pineapple, Mango.
Vegetables: Cucumber, Carrot, Capsicum, Onion, Potato, Lemon, Tomato, Radish, Beetroot, Cabbage, Lettuce, Spinach, Soybean, Cauliflower, Bell Pepper, Chilly, Pepper, Turnip, Corn, Sweetcorn, Sweet Potato, Paprika, Jalapeño, Ginger, Garlic, Peas, Eggplant.
🛠️ Tech Stack
Language: Python
Libraries: TensorFlow, Keras, Matplotlib, Kagglehub, OS, Shutil
Model: MobileNetV2 (Pre-trained on ImageNet)
📝 Steps Performed
Data Loading: Used kagglehub to fetch the dataset directly into the environment.
Data Reorganization: Automated script to map 36 sub-folders into the required binary "Fruits" and "Vegetables" structure.
Preprocessing: Resized images to 224x224 and applied normalization.
Model Building: Implemented Transfer Learning to leverage pre-trained features.
Training: Trained the model and monitored accuracy/loss.
Visualization: Plotted training results to evaluate performance.
📊 Results
The model's performance, including accuracy and loss graphs, can be viewed directly within the notebook file.
