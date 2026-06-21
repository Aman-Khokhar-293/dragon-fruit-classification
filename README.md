# 🍈 Dragon Fruit Leaf & Fruit Classification using Deep Learning

## 📌 Overview

This project focuses on the automated classification of dragon fruit leaf and fruit conditions using Deep Learning and Computer Vision techniques.

The system classifies images into four categories:

- Good Leaf
- Bad Leaf
- Good Fruit
- Bad Fruit

The objective is to reduce manual inspection efforts and improve consistency in agricultural quality assessment. The project evaluates multiple CNN architectures and transfer learning models to identify the most effective approach for small-scale agricultural datasets. :contentReference[oaicite:0]{index=0}

---

## 🎯 Problem Statement

Manual inspection of dragon fruit quality is time-consuming, subjective, and prone to errors. This project aims to automate the classification process using image-based deep learning models.

Challenges addressed:

- Limited dataset size
- Class imbalance
- Variations in lighting and image backgrounds
- Multi-class classification problem

---

## 🧠 Models Evaluated

### Custom CNN
A CNN architecture built from scratch for image classification.

### VGG16
Transfer learning model using ImageNet pretrained weights.

### MobileNetV2
Lightweight transfer learning architecture optimized for efficiency and deployment.

---

## 🔄 Workflow

```text
Image Dataset
      ↓
Preprocessing
      ↓
Data Augmentation
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Performance Comparison
```

---

## 📂 Dataset

Dataset contains approximately 400–500 dragon fruit images categorized into:

- Good Leaf
- Bad Leaf
- Good Fruit
- Bad Fruit

---

## ⚙️ Data Preprocessing

- Image Resizing (224 × 224)
- Image Normalization
- Train/Test Split

### Data Augmentation

To improve generalization and reduce overfitting:

- Random Rotation
- Horizontal Flipping
- Random Zoom

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab

---

## 📊 Training Configuration

- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Epochs: 100
- Early Stopping (Patience = 10)

---

## 📈 Results

| Model | Accuracy |
|---------|---------|
| MobileNetV2 | 80.00% |
| VGG16 | 75.56% |
| Custom CNN | 72.78% |

### Best Model

🏆 MobileNetV2 achieved the highest performance with:

- Accuracy: 80.00%
- Precision: 80.64%
- Recall: 80.00%
- AUC: 0.850

MobileNetV2 outperformed other models due to its lightweight architecture and effective transfer learning capabilities on a limited dataset. :contentReference[oaicite:1]{index=1}

---

## 📚 Key Learnings

- Deep Learning Fundamentals
- Convolutional Neural Networks (CNN)
- Transfer Learning
- Data Augmentation
- Hyperparameter Tuning
- Multi-Class Classification
- Model Evaluation Metrics

---

## 🚀 Future Improvements

- Larger Dataset Collection
- Grad-CAM Explainability
- YOLO-based Defect Detection
- Mobile Application Deployment
- Edge AI Deployment

---

## 📁 Repository Contents

```text
README.md
Dragon_Fruit_Classification.ipynb
Dragon_Fruit_Classification_Presentation.pdf
```

---

## 👨‍💻 Author

**Aman Khokhar**

B.Tech Artificial Intelligence

Ganpat University
