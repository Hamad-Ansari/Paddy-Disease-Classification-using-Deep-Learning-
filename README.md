# Paddy Disease Classification using Deep Learning 🌾

A deep learning–based image classification project for identifying diseases in paddy (rice) crops using leaf images. This project aims to support early disease detection to improve crop yield and agricultural decision-making.
<img width="1024" height="1024" alt="b_📱_LinkedIn_Visual_C" src="https://github.com/user-attachments/assets/9bbf6d1e-3241-43bc-bd55-d74b806174ac" />

---

## 📌 Project Overview

Paddy crops are vulnerable to various diseases that significantly reduce yield if not detected early. This project leverages **Convolutional Neural Networks (CNNs)** and **transfer learning** to classify paddy leaf diseases from images.

The notebook covers:
- Data exploration and visualization  
- Image preprocessing and augmentation  
- Model training using transfer learning  
- Performance evaluation and analysis  

---

## 🧠 Model Architecture

- Base Model: **EfficientNetV2-B3** (transfer learning)
- Framework: **TensorFlow / Keras**
- Loss Function: Categorical Crossentropy
- Optimizer: Adam
- Evaluation Metrics: Accuracy, Precision, Recall

> The architecture is modular and can be replaced with other CNN backbones.

---

## 📂 Dataset

- Source: Public paddy disease image dataset (e.g., Kaggle)
- Classes include multiple paddy leaf disease categories and healthy leaves.
- Images are resized and normalized before training.

⚠️ Dataset files are **not included** in this repository due to size constraints.

---

## 📊 Results

- Training and validation accuracy curves
- Confusion matrix
- Class-wise performance analysis

The trained model demonstrates strong generalization across disease classes.

---

## 🛠️ Technologies Used

- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- OpenCV  

---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/your-username/paddy-disease-classification.git
cd paddy-disease-classification
```

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![License](https://img.shields.io/badge/License-MIT-green)
<img width="1971" height="1407" alt="7e09e069-4969-4c39-a78c-00bc11cf2e9e" src="https://github.com/user-attachments/assets/77c23bad-c6fd-4bf6-a781-2010ba882a8a" />

<img width="1390" height="490" alt="e490489e-261c-4db5-8756-176b516722fb" src="https://github.com/user-attachments/assets/c3502767-0196-49c9-940d-d9bd91f41571" />
<img width="1327" height="1110" alt="f01779d7-1b28-4078-8413-8b36d6c3104a" src="https://github.com/user-attachments/assets/de5e761f-9500-456b-aa4d-88b4cf0da468" />

