# 🩻 Pneumonia Detection Using Convolutional Neural Networks (CNN)

## 📌 Project Overview
This project implements a deep learning-based Convolutional Neural Network (CNN) model to automatically detect Pneumonia from Chest X-ray images. The model was trained and evaluated using TensorFlow/Keras on a Kaggle GPU environment. The objective is to demonstrate how AI can assist in medical image screening and early diagnosis support.

---

## 🎯 Objectives
- Build an end-to-end image classification pipeline using CNN.
- Perform image preprocessing and data augmentation.
- Train and validate the model on real-world medical images.
- Evaluate model performance on unseen test data.
- Save and reuse the trained model for inference.

---

## 🧠 Model Architecture
The CNN architecture includes:
- Convolutional layers (Conv2D) for feature extraction  
- MaxPooling layers for spatial downsampling  
- Fully connected Dense layers for classification  
- Dropout layers to reduce overfitting  
- Softmax output layer for multi-class probability prediction  

---

## 📊 Results
- ✅ Test Accuracy: **76.28%**
- ✅ Real-world pneumonia image predicted correctly with **99.9% confidence**
- ✅ Stable training using Kaggle GPU (T4)

> Note: Accuracy may vary slightly depending on training parameters and random initialization.

---

## 🗂 Dataset
- Dataset: Chest X-ray Images (Pneumonia)
- Source: Kaggle Public Dataset
- Classes:
  - Normal
  - Pneumonia

Dataset structure:
chest_xray/
├── train/
├── val/
└── test/

---

## ⚙️ Technology Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- OpenCV
- Kaggle GPU Environment

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
git clone https://github.com/<Prakhar501>/Pneumonia-CNN-Detection.git
cd Pneumonia-CNN-Detection


### 2️⃣ Install Dependencies
pip install -r requirements.txt


### 3️⃣ Run Training Notebook
jupyter notebook notebook/training.ipynb

🤝 Contributions

Contributions are welcome. Feel free to fork the repository and submit pull requests.

📜 License

This project is intended for educational and research purposes only.

👨‍💻 Author

Prakhar Bhatnagar
B.Tech in Artificial Intelligence & Machine Learning
DRDO Intern | Embedded Systems & Computer Vision Enthusiast
