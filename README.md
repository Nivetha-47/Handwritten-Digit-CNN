# 🖋️ Handwritten Digit Classifier using CNN

This project uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify handwritten digits from the popular MNIST dataset. A Flask web app is included to allow users to upload digit images and receive real-time predictions.

---

## 🔍 Project Overview

- 📚 **Dataset**: [MNIST Handwritten Digits]
- 🧠 **Model**: Convolutional Neural Network (CNN)
- 📊 **Accuracy**: ~99% on validation data
- 🌐 **Web App**: Built using Flask

---

## ⚠️ Important

> The trained model `my_model.hdf5` is **not uploaded directly** to the repository (GitHub restricts large binary files).  
> You must **generate and save it from the notebook** by running:

```python
model.save("my_model.hdf5")
