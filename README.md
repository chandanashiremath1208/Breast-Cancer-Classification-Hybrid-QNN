# Breast Cancer Image Classification using Hybrid QNN

## 📌 Overview

This project presents a hybrid quantum-classical framework for breast cancer image classification using multiple deep learning models and a Quantum Neural Network (QNN).

---

## 🚀 Models Implemented

* ResNet50 (BreastMNIST)
* EfficientNetV2-S (BreastMNIST)
* EfficientNetV2-S (BreakHis)
* EfficientNet-B5 (BreastMNIST)
* Hybrid Quantum Neural Network (QNN)

---

## 📊 Datasets

* BreastMNIST
* BreakHis

---

## 🧠 Key Results

* EfficientNet-B5: **88.50%**
* Hybrid QNN: **90.50% (Best Performance)**

---

## 📈 Results Table

| Model                                | Dataset     | Accuracy (%) | Precision  | Recall     | F1-Score   |
| ------------------------------------ | ----------- | ------------ | ---------- | ---------- | ---------- |
| ResNet50                             | BreastMNIST | 86.00        | 0.86       | 0.86       | 0.86       |
| ResNet50 + QNN                       | BreastMNIST | 89.00        | 0.89       | 0.89       | 0.89       |
| EfficientNetV2-S                     | BreastMNIST | 85.50        | 0.85       | 0.85       | 0.85       |
| EfficientNetV2-S + QNN               | BreastMNIST | 88.00        | 0.88       | 0.88       | 0.87       |
| EfficientNet-B5                      | BreastMNIST | 88.50        | 0.7818     | 0.7963     | 0.7890     |
| **EfficientNet-B5 + QNN (Proposed)** | BreastMNIST | **90.50**    | **0.8723** | **0.7593** | **0.8119** |
| EfficientNetV2-S                     | BreakHis    | 77.50        | 0.78       | 0.78       | 0.77       |
| EfficientNetV2-S + QNN               | BreakHis    | 72.50        | 0.74       | 0.72       | 0.72       |

---

## 📁 Project Structure

```
models/
   resnet_breastmnist.ipynb
   efficientnetv2_breastmnist.ipynb
   efficientnetv2_breakhis.ipynb
   efficientnet_b5.ipynb
```

---

## ⚙️ Tech Stack

* PyTorch
* PennyLane
* Google Colab

---

## 👩‍💻 Author

G Lavanya
Harshitha K
Bhomitha Kallola
Chandana S Hiremath
