# 🌸 Flower Recognition using CNN

This project is a deep learning-based flower classification model built with TensorFlow and Keras. It can classify flower images into five categories using a Convolutional Neural Network (CNN) architecture.

## 🧠 Model Overview

- **Input:** Flower images (resized to 128x128 pixels)
- **Architecture:** Multiple convolutional and pooling layers, followed by fully connected layers
- **Output:** One of 5 flower classes
- **Augmentation:** Rotation, zoom, width/height shifts, flips
- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy

## 🗂 Dataset

- Assumes a directory structure like:  
  `/path/to/flowers/<class_name>/<image>.jpg`

Images are loaded, resized, and normalized before training. Labels are one-hot encoded using `LabelEncoder`.

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/flower-recognition-cnn.git
   cd flower-recognition-cnn
Set your dataset path in the notebook:

python
Copy
Edit
folder_dir = '/content/drive/MyDrive/Flower Detection/flowers'
Run the Jupyter Notebook (Untitled0.ipynb) in your preferred environment (Google Colab, Jupyter, etc.).

🏆 Results
Achieves good classification accuracy after training for 64 epochs.

Includes visualization of correct vs incorrect predictions with class labels.

🛠 Libraries Used
TensorFlow / Keras

NumPy

OpenCV

Matplotlib

Scikit-learn

