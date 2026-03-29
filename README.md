# 🧠 Case Study 03 – Computer Vision

## 🍎 Fruits vs 🥕 Vegetables Classification

---

## 📌 Problem Statement

This project focuses on building a **machine learning model** to classify images into two categories:

* **Fruits**
* **Vegetables**

The dataset contains multiple food categories which are grouped into these two main classes. 

---

## 📂 Dataset

The dataset is sourced from Kaggle:

👉 https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition

⚠️ Dataset size: ~2GB (not included in this repository)

---

### 🍉 Fruits Categories

Banana, Apple, Pear, Grapes, Orange, Kiwi, Watermelon, Pomegranate, Pineapple, Mango

### 🥦 Vegetables Categories

Cucumber, Carrot, Capsicum, Onion, Potato, Lemon, Tomato, Radish, Beetroot, Cabbage, Lettuce, Spinach, Soybean, Cauliflower, Bell Pepper, Chilly, Pepper, Turnip, Corn, Sweetcorn, Sweet Potato, Paprika, Jalapeño, Ginger, Garlic, Peas, Eggplant

---

## 🎯 Objective

* Build an image classification model
* Classify images into Fruits and Vegetables
* Use Python for implementation
* Upload the project to GitHub as required

---

## 🛠️ Tools & Technologies

* **Language:** Python
* **Libraries:** TensorFlow, Keras, Matplotlib, OS, Shutil, Kagglehub
* **Model:** MobileNetV2 (Transfer Learning)

---

## ⚙️ Steps Performed

### 1️⃣ Data Loading

* Dataset loaded using Kaggle API / kagglehub

### 2️⃣ Data Preprocessing

* Images resized to **224×224**
* Normalization applied

### 3️⃣ Data Organization

* Converted multiple classes into:

  * Fruits
  * Vegetables

### 4️⃣ Model Building

* Used **MobileNetV2** pre-trained on ImageNet
* Added custom classification layers

### 5️⃣ Model Training

* Trained model on dataset
* Monitored:

  * Accuracy
  * Loss

### 6️⃣ Model Evaluation

* Evaluated performance using validation data

### 7️⃣ Visualization

* Plotted:

  * Accuracy graph
  * Loss graph

---

## 📊 Results

* Model achieved **high accuracy** in classification
* Training and validation graphs are included in the notebook

---

## 📁 Repository Contents

```
Case-Study-03/
│── model_code.ipynb
│── README.md
│── outputs/ (optional)
```

---

## ▶️ How to Run

### 1. Clone Repository

```
git clone https://github.com/your-username/case-study-03.git
cd case-study-03
```

### 2. Install Libraries

```
pip install tensorflow keras matplotlib kagglehub
```

### 3. Download Dataset

* Download from Kaggle link above
* Extract and place in project folder

### 4. Run Notebook

Open:

```
model_code.ipynb
```

---

## 📌 Important Instructions (As per Case Study)

✔ Notebook must include outputs
✔ Repository must be **public**
✔ Upload `.ipynb` file to GitHub
✔ Share GitHub link in submission portal 

---

## 👨‍💻 Author

**Adithya S S**

---

## 🙌 Acknowledgment

* Kaggle for dataset
* TensorFlow & Keras

---
