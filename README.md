This repository presents a binary image classification model that categorizes food items into Fruits and Vegetables using deep learning.

🚀 Project Overview

The objective is to classify images from a dataset containing ~36 distinct food categories into two primary classes: Fruits and Vegetables.

To achieve high performance with limited training time, Transfer Learning was applied using the MobileNetV2 architecture, leveraging pre-trained ImageNet weights.

📁 Dataset Structure

Fruits:
Banana, Apple, Pear, Grapes, Orange, Kiwi, Watermelon, Pomegranate, Pineapple, Mango

Vegetables:
Cucumber, Carrot, Capsicum, Onion, Potato, Lemon, Tomato, Radish, Beetroot, Cabbage, Lettuce, Spinach, Soybean, Cauliflower, Bell Pepper, Chilly, Pepper, Turnip, Corn, Sweetcorn, Sweet Potato, Paprika, Jalapeño, Ginger, Garlic, Peas, Eggplant

🛠️ Tech Stack
Language: Python
Libraries: TensorFlow, Keras, Matplotlib, Kagglehub, OS, Shutil
Model: MobileNetV2 (Pre-trained on ImageNet)
⚙️ Workflow
Data Acquisition
Dataset fetched directly using kagglehub
Data Reorganization
Automated script used to restructure 36 classes into 2 categories
Preprocessing
Image resizing to 224×224
Pixel normalization for improved model convergence
Model Development
Applied Transfer Learning with MobileNetV2
Fine-tuned layers for classification task
Training & Evaluation
Model trained with monitoring of accuracy and loss metrics
Visualization
Training performance visualized using graphs
📊 Results

The model achieves high classification accuracy, with training and validation performance visualized in the notebook through accuracy and loss curves.
