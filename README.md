# 🖋️ Handwritten Digit Classifier using CNN

This project uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify handwritten digits from the popular MNIST dataset. It includes a trained model and a Flask-based web application for real-time digit image predictions.

---

## 🔍 Project Overview

- 📚 Dataset: [MNIST Handwritten Digits](http://yann.lecun.com/exdb/mnist/)
- 🧠 Model: Convolutional Neural Network (CNN)
- 📊 Accuracy: ~99% on validation data
- 🌐 Web App: Flask-based digit prediction from image upload

---

## 🧪 Demo

Upload a handwritten digit image (28x28 grayscale) and the model will predict the correct digit (0–9).

---

## 📁 Repository Contents

| File/Folder                            | Description                                  |
|----------------------------------------|----------------------------------------------|
| `Convolution_Neural_Network_Handwritten.ipynb` | Jupyter Notebook with CNN training code |
| `my_model.hdf5` *(optional)*           | Trained Keras model file (save manually)     |
| `app1.py`                              | Flask app to serve the model                 |
| `templates/index.html`                 | Upload page                                  |
| `templates/result.html`                | Result page                                  |
| `static/` *(optional)*                 | Folder for uploaded/processed images         |

---

## 🧑‍💻 How to Run Locally

### 1. Clone the repo:
```bash
git clone https://github.com/your-username/Handwritten-Digit-CNN.git
cd Handwritten-Digit-CNN
