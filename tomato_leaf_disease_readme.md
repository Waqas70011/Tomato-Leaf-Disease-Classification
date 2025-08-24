# 🍅 Tomato Leaf Disease Detection

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.13-orange?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-2.14-red?logo=keras&logoColor=white)](https://keras.io/)

---

## 📖 Table of Contents
- [Project Overview](#project-overview)  
- [Dataset](#dataset)  
- [Features](#features)  
- [Installation](#installation)  
- [How to Use](#how-to-use)  
- [Project Structure](#project-structure)  
- [Results](#results)  
- [Future Improvements](#future-improvements)  
- [References](#references)  

---

## 🌟 Project Overview
Detect diseases in tomato leaves using **deep learning**. Early detection helps farmers prevent crop loss and improve yield.  

Classifies leaves as **healthy** or affected by diseases like **bacterial spot, leaf mold, and late blight**.  

---

## 📂 Dataset
- Images of healthy and diseased tomato leaves  
- Labels indicate the type of disease  
- Source: [Kaggle Tomato Leaf Disease Dataset](https://www.kaggle.com/datasets)  

---

## ⚡ Features
- **Data Cleaning & Preprocessing**: Resize, normalize, handle missing data  
- **Exploratory Data Analysis (EDA)**: Visualize class distribution and sample images  
- **Modeling**:  
  - Convolutional Neural Network (CNN)  
  - Transfer Learning with pre-trained models (VGG16, MobileNet)  
- **Evaluation**: Accuracy, confusion matrix, example predictions  

---

## 🛠 Installation
```bash
git clone https://github.com/yourusername/tomato-leaf-disease.git
cd tomato-leaf-disease
pip install -r requirements.txt
```

---

## 🖥 How to Use
1. Open `Tomato_Leaf_Disease_EDA_and_Classification.ipynb`  
2. Run the notebook step by step:  
   - Load dataset  
   - Perform EDA  
   - Train model  
   - Evaluate predictions  

---

## 📁 Project Structure
```
Tomato-Leaf-Disease/
│
├─ data/          # Dataset images
├─ notebooks/     # Jupyter notebooks
├─ models/        # Saved trained models
├─ outputs/       # Plots and results
├─ requirements.txt
└─ README.md
```

---

## 📊 Results
- Model achieves **[X%] accuracy** on test data  
- Confusion matrix and sample predictions included  
- Insights: some diseases look visually similar → future work: more data or augmentation  

---

## 🚀 Future Improvements
- Add **data augmentation** to improve accuracy  
- Experiment with different CNN architectures or transformer models  
- Deploy as a **web/mobile app** for real-time detection  

---

## 📚 References
- [Kaggle Tomato Leaf Disease Dataset](https://www.kaggle.com/datasets)  
- [TensorFlow CNN Tutorial](https://www.tensorflow.org/tutorials/images/cnn)  
- [Transfer Learning Guide](https://www.tensorflow.org/tutorials/images/transfer_learning)

