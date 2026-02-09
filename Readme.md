# 🐱🐶 Cats vs Dogs Image Classification (CNN)

This project uses a **Convolutional Neural Network (CNN)** to classify images of **cats and dogs**.
It is a deep learning model built using **TensorFlow and Keras** and trained on a labeled image dataset.

---

## 📌 Project Overview

The goal of this project is to build an image classifier that can automatically detect whether an image contains a **cat** or a **dog**.

The model learns visual features such as:

* Edges
* Shapes
* Fur patterns
* Facial structures

using multiple convolutional layers.

---

## 🧠 Model Architecture

The CNN consists of:

* 3 Convolutional layers (Conv2D)
* 3 MaxPooling layers
* Flatten layer
* Dense (fully connected) layer
* Dropout layer (for overfitting control)
* Output layer with sigmoid activation

---

## 📂 Dataset

Dataset structure:

```
CatsDogs/
 ├── Cat/
 │    ├── cat1.jpg
 │    ├── cat2.jpg
 │    └── ...
 └── Dog/
      ├── dog1.jpg
      ├── dog2.jpg
      └── ...
```

* Two classes: **Cat** and **Dog**
* Images resized to **150 × 150**
* 80% training, 20% validation split

---

## ⚙️ Technologies Used

* Python
* TensorFlow
* Keras
* Matplotlib
* Jupyter Notebook

---

## 🚀 How to Run the Project

### Step 1: Install dependencies

```
pip install tensorflow matplotlib
```

### Step 2: Open Jupyter Notebook

```
jupyter notebook
```

Open the notebook and run all cells.

---

## 📊 Model Performance

* Validation Accuracy: **~80–90%**
* Binary classification (Cat vs Dog)

---

## 📈 Training Graph

The notebook generates:

* Accuracy vs Epoch graph
* Loss vs Epoch graph

---

## 💾 Model Output

The trained model is saved as:

```
cats_vs_dogs_model.h5
```

This model can be used later for:

* Image prediction
* Web app deployment
* Real-time classification

---

## 🧪 Future Improvements

* Use Transfer Learning (MobileNet, VGG16, ResNet)
* Data augmentation
* Hyperparameter tuning
* Deploy as a web application

---

## 👩‍💻 Author

**Aadya Patil**
AI/ML Student
GitHub: [https://github.com/aadyapatil24](https://github.com/aadyapatil24)
