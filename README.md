# Sign Language Detection

# Overview
This project uses a custom-trained deep learning model to focus on real-time sign language detection. The objective is to enhance communication by recognizing sign language gestures and translating them into readable text. The model uses TensorFlow and OpenCV, offering efficient and accurate detection.

# Features
Real-time Detection: The system processes live video input and identifies sign language gestures instantly.
Custom Dataset: The model is trained on a custom dataset to improve accuracy in detecting specific gestures.
TensorFlow and OpenCV Integration: Leverages the power of TensorFlow for deep learning and OpenCV for video processing.
User-Friendly Interface: A simple and intuitive interface for easy interaction with the model.

# Project Architecture
The project is structured as follows:
```
├── dataset/
│   ├── images/
│   └── annotations/
├── models/
│   ├── sign_language_model.h5
├── notebooks/
│   ├── data_preprocessing.ipynb
│   └── model_training.ipynb
├── src/
│   ├── live_detection.py
│   ├── utils.py
├── README.md
└── requirements.txt
```
**dataset/**: Contains the images and annotations used for training.

**models/**: Pre-trained models and final model files.

**notebooks/**: Jupyter notebooks for data preprocessing and model training.

**src/**: Source code for real-time detection and utility functions.

# Installation
**Prerequisites** 

Ensure you have Python 3.8+ installed. Install the necessary libraries using the requirements.txt file:

```pip install -r requirements.txt```

Running the Project

**1. Clone the Repository**

```git clone https://github.com/cdbrain108/sign-language-detection.git```

```cd sign-language-detection```

**2. Run the live Detection in the main Code**

The script will open your webcam and detect sign language gestures in real time.

# Customizing the Model
If you wish to retrain or fine-tune the model:
```
1. Prepare the Dataset

2. Add your images to the dataset/images/ directory and update the annotations accordingly.

3. Run the Training Notebook

4. Open notebooks/model_training.ipynb and execute the cells to train the model on your custom dataset.

5. Update the Model

6. Replace the old model in models/ with the newly trained model.
```
# Demo


