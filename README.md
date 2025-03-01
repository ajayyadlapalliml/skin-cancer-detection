# Skin Cancer Detection using CNN

## Problem Statement
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. This project builds a **Convolutional Neural Network (CNN)** model to detect melanoma accurately from images. The goal is to provide an automated way to help dermatologists diagnose melanoma, reducing manual effort in early detection.

## Dataset
The dataset consists of labeled skin lesion images. If the dataset is too large, please download it from the original source:
- **[Dataset Link (Kaggle/ISIC)](https://www.kaggle.com/datasets/nodoubttome/skin-cancer9-classesisic)**

## Project Workflow
1. **Data Preprocessing**: Load and preprocess images.
2. **Model Architecture**: Build a CNN model using TensorFlow/Keras.
3. **Training & Evaluation**: Train the model and analyze performance.
4. **Predictions**: Use the trained model for skin cancer classification.

## Installation
Clone this repository and install dependencies:
```bash
git clone https://github.com/<your-username>/skin-cancer-detection.git
cd skin-cancer-detection
pip install -r requirements.txt
```

## Usage
Run the Jupyter Notebook:
```bash
jupyter notebook skin-cancer-detection.ipynb
```
Or execute a Python script version:
```bash
python skin_cancer_detection.py
```

## Dependencies
To install required dependencies, use:
```bash
pip install -r requirements.txt
```

## Results
The model achieves high accuracy in detecting melanoma. See the **Results & Evaluation** section in the notebook for detailed performance metrics.

## Author
[Your Name]

