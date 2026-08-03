#  Medical Image Classification AI

##  Overview

Deep Learning application for breast cancer histopathological image classification.

The objective of this project is to classify IDC (Invasive Ductal Carcinoma) breast cancer images using Convolutional Neural Networks and Transfer Learning approaches.

The project compares a custom CNN model with pretrained architectures such as DenseNet121 and ResNet50V2.

---

##  Dataset

This project uses a histopathological image dataset for breast cancer classification.

The dataset contains microscopic images categorized into two classes:

- **IDC Negative**: Non-cancerous tissue
- **IDC Positive**: Invasive Ductal Carcinoma (cancerous tissue)

Due to the large size of the dataset, the images are not included in this repository.

For experimentation and model training, a representative subset of the dataset was used.

### Dataset characteristics

- Image type: Histopathological microscopy images
- Task: Binary image classification
- Classes: IDC Negative / IDC Positive
- Preprocessing:
  - Image resizing
  - Normalization
  - Data preparation before training

---

##  Technologies

- Python
- TensorFlow / Keras
- PyTorch
- OpenCV
- NumPy
- Scikit-learn
- Streamlit
- Jupyter Notebook

---

##  Models

Implemented models:

| Model | Type |
|---|---|
| Custom CNN | Deep Learning |
| DenseNet121 | Transfer Learning |
| ResNet50V2 | Transfer Learning |

---

##  Results

### Custom CNN

Accuracy:

**96.94%**

### Transfer Learning Models

- DenseNet121
- ResNet50V2

Evaluation metrics:
- Accuracy
- Loss curves
- Confusion Matrix
- Classification Report

---

##  Features

 Image preprocessing  
 CNN model training  
 Transfer learning experiments  
 Model evaluation  
 Breast cancer image classification  
 Streamlit prediction interface  

 ##  Project Structure


medical-image-classification-ai/

├── README.md
├── requirements.txt
├── breast_cancer_classification.ipynb
└── breast_cancer_classification_cnn.ipynb


---

##  Installation

Clone the repository:

bash
git clone https://github.com/Ichrakb27/medical-image-classification-ai.git

pip install -r requirements.txt

jupyter notebook

Author

Belhoula Ichrak

🎓 Master Professional in Data Science
    AI & Machine Learning Enthusiast
💻 Full Stack Developer

