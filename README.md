# 🍌 Banana Ripeness Classification using CNN

This project uses a **Convolutional Neural Network (CNN)** to classify the ripeness stage of bananas from images.  
It is an end-to-end **Machine Learning + Computer Vision** project covering data preprocessing, model training, evaluation, and deployment-ready model exports.

---

## 📌 Problem Statement
Manual identification of banana ripeness is subjective and error-prone.  
This project automates ripeness detection using deep learning to classify bananas into four stages.

---

## 🏷️ Classes
- Unripe  
- Half-ripened  
- Ripe  
- Overripe  

---

## 🔁 Workflow (Input → Output)
1. Input banana image  
2. Resize to 224×224  
3. Normalization & augmentation  
4. CNN feature extraction  
5. Dense layer classification  
6. Softmax probabilities  
7. Final ripeness prediction  

---

## 🧠 Model Overview
- CNN built using **TensorFlow (Keras)**
- Convolution + MaxPooling layers
- Dropout for overfitting control
- Softmax output for multi-class prediction

---

## 📂 Dataset
Dataset not included in this repository due to large size (~70GB).

Source: Telkom University Dataverse
Dataset Link:
🔗 https://dataverse.telkomuniversity.ac.id/file.xhtml?persistentId=doi:10.34820/FK2/GJBZ0X/7GJYWP&version=1.0

Description:

High-quality banana images collected in Indonesia

Images categorized into ripeness stages

Suitable for image classification and CNN training

⚠️ Note:
The dataset is not included in this repository due to its large size (~70GB).
Please download it manually from the link above and place it in the following structure:

data/
├── train/
│   ├── Unripe/
│   ├── Half-ripened/
│   ├── Ripe/
│   └── Overripe/
└── test/
    ├── Unripe/
    ├── Half-ripened/
    ├── Ripe/
    └── Overripe/

---

## 🛠️ Tools & Technologies
- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📊 Evaluation
Model performance is evaluated using:
- Accuracy
- Confusion Matrix
- Prediction comparison across formats (H5, SavedModel, TFLite)

---

## 💾 Model Export
Models were saved in:
- .h5
- TensorFlow SavedModel
- TensorFlow Lite (FP32 & Dynamic)

(Models excluded from GitHub due to size)

---

## ▶️ How to Run
git clone https://github.com/Nihaal122/banana-ripeness-classification-cnn.git  
cd banana-ripeness-classification-cnn  
pip install tensorflow numpy pandas matplotlib scikit-learn pillow  
jupyter notebook banana_full_project.ipynb

---

## 🚀 Future Improvements
- Transfer learning (MobileNet / ResNet)
- Better class balancing
- Web or mobile deployment
- Real-time camera prediction

---

## 👨‍💻 Author
**Nihaal Khanna**  
GitHub: https://github.com/Nihaal122  

---

## 📜 License
MIT License
