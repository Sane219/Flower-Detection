# 🌸 Flower Recognition using CNN

This project is a deep learning-based flower classification model built with TensorFlow and Keras. It classifies flower images into five categories using a Convolutional Neural Network (CNN).

## 🧠 Model Overview

- **Input:** Flower images (resized to 128x128 pixels)
- **Architecture:** Multiple convolutional and pooling layers, followed by fully connected layers
- **Output:** One of 5 flower classes
- **Augmentation:** Rotation, zoom, width/height shifts, flips
- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy

## 🗂 Dataset

The dataset is available on Kaggle:  
🔗 [Flowers Recognition Dataset](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition?resource=download)

### 📥 Download Instructions

1. Download the dataset manually from the link above (requires a Kaggle account).
2. Extract the dataset and move the `flowers` folder to the following location:

/content/drive/MyDrive/Flower Detection/flowers

bash
Copy
Edit

> This path is referenced directly in the notebook (`Untitled0.ipynb`). You may adjust it in the code if using a different setup.

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/sane206/flower-recognition-cnn.git
   cd flower-recognition-cnn
Ensure the dataset is placed at the specified path.

Open and run the notebook:

bash
Copy
Edit
jupyter notebook Untitled0.ipynb
Or run it in Google Colab for GPU support.

🏆 Results
Achieves strong classification accuracy after training for 64 epochs.

Includes side-by-side visualizations of true vs predicted labels.

🛠 Libraries Used
TensorFlow / Keras

NumPy

OpenCV

Matplotlib

Scikit-learn

📬 Contact
For questions, suggestions, or contributions, feel free to open an issue or a pull request.

GitHub: sane206

