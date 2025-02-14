# PlantSeedlingsClassifier
This project focuses on developing a deep learning-based plant seedling classification system using Convolutional Neural Networks (CNNs) and transfer learning techniques. The goal is to accurately classify different plant species from images at various growth stages, contributing to advancements in agriculture, ecology, and conservation.


# **Plant Seedlings Classification Using CNNs and Transfer Learning**

This project focuses on classifying plant seedlings using **Convolutional Neural Networks (CNNs)** and **Transfer Learning (Xception model)**. The dataset used is the **V2 Plant Seedlings Dataset** from Kaggle, which contains images of seedlings from **12 different species**. The goal is to develop an accurate classification model to assist in agricultural and ecological research.

---

## **Dataset**
- **Source:** [Kaggle - Plant Seedlings Classification](https://www.kaggle.com/competitions/plant-seedlings-classification)
- **Images:** 5,539 images of 12 plant species.
- **Train/Test Split:** 80-20 ratio for model training and evaluation.

---

## **Model Architectures**
### 🌱 **1. CNN Model**
A custom-built **Convolutional Neural Network (CNN)** designed for feature extraction and classification.

### 🚀 **2. Transfer Learning (Xception)**
A pre-trained **Xception model** (trained on ImageNet) is fine-tuned to leverage deep feature representations.

---

## **Setup Instructions**
### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/plant-seedlings-classification.git
cd plant-seedlings-classification
```

### **2. Install Dependencies**
Ensure you have Python 3.8+ installed, then run:
```bash
pip install -r requirements.txt
```

### **3. Run the Notebooks**
Open Jupyter Notebook and run the training notebooks:
```bash
jupyter notebook
```
- Run **CNN.ipynb** to train the CNN model.
- Run **transfer-learning-xception-96.ipynb** to train the Xception model.

---

## **Results**
| Model                     | Accuracy | Macro F1 Score |
|---------------------------|---------|---------------|
| **Baseline CNN**          | 88.5%   | 0.87          |
| **Xception Transfer Learning** | **96.2%** | **0.927** |

✅ **Achieved 96.2% accuracy** using transfer learning with Xception!

---

## **Future Improvements**
- Experiment with **other transfer learning models** like ResNet and EfficientNet.
- Implement **hyperparameter tuning** for CNN models.
- Improve **dataset augmentation** techniques.

---

## **Contributors**
- **Phalguna Peravali**
- **Deepak Palavarapu**
- **Shashank Jaganntham**
- **Jaya Chandra Kanth Reddy Cheemarla**
- **Charithesh Puppireddy**

---

## **License**
This project is open-source under the **MIT License**.

---
