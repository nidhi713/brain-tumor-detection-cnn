# Brain Tumor Classification using Deep Learning (ResNet18)

## Overview

This project focuses on detecting and classifying brain tumors from MRI images using deep learning. It leverages transfer learning with a pretrained ResNet18 model to classify images into four categories:

* Glioma Tumor
* Meningioma Tumor
* Pituitary Tumor
* No Tumor

The model is trained on labeled MRI datasets and achieves high accuracy in medical image classification tasks.

---

## Key Features

* Multi-class brain tumor classification (4 classes)
* Transfer Learning using ResNet18
* Efficient image preprocessing using OpenCV
* PyTorch-based training pipeline
* Data splitting (Train / Validation / Test)
* One-hot encoding for labels
* GPU support (if available)

---

## Tech Stack

* Python
* PyTorch
* OpenCV
* NumPy
* Scikit-learn
* Torchvision

---

## Dataset

The dataset contains MRI brain scan images categorized into:

* Glioma
* Meningioma
* Pituitary
* No Tumor

Dataset structure:

```
data/
 ├── Training/
 ├── Testing/
```

---

## Workflow

1. Data Extraction from ZIP file
2. Image Preprocessing (Resize, Normalize)
3. Dataset Creation (Train/Test split)
4. Label Encoding (One-hot encoding)
5. Model Loading (Pretrained ResNet18)
6. Model Training
7. Validation & Testing

---

## Model Architecture

* Pretrained **ResNet18**
* Modified final fully connected layer for 4-class classification
* Loss Function: CrossEntropyLoss
* Optimizer: Adam

---

## How to Run

```bash
# Clone repository
git clone https://github.com/your-username/brain-tumor-detection-cnn.git

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook
```

---

## Results

* Accurate classification of MRI images
* Efficient learning using transfer learning
* Reduced training time compared to training from scratch

---

## Future Improvements

* Deploy as a web app (Streamlit / Flask)
* Add real-time MRI upload interface
* Improve accuracy with larger dataset
* Integrate Grad-CAM for model explainability

---

## Author

**Nidhi Kumari**
B.Tech CSE | AI/ML Enthusiast

