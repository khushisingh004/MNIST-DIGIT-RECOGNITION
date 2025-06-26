# MNIST-DIGIT-RECOGNITION
A Deep Learning project for handwritten digit recognition using CNN and TensorFlow

# 🧠 Handwritten Digit Recognition using Deep Learning

This project implements a CNN-based image classification model using the MNIST dataset to recognize handwritten digits from 0 to 9. It is built using **TensorFlow**, trained in **Google Colab**, and demonstrates fundamental deep learning concepts with real-world application.


## 📊 Dataset Overview
- **Dataset**: [MNIST](http://yann.lecun.com/exdb/mnist/)
- **Type**: Grayscale images
- **Image size**: 28x28 pixels
- **Classes**: 10 digits (0 to 9)
- **Split**: 60,000 training / 10,000 testing

---

## 🧠 Model Architecture
The model is a **Convolutional Neural Network (CNN)** with the following layers:
- `Conv2D` → `MaxPooling2D`
- `Conv2D` → `MaxPooling2D`
- `Flatten`
- `Dense (64 neurons)`
- `Dense (10 neurons, Softmax)`

**Compiled with:**
- Optimizer: `Adam`
- Loss Function: `SparseCategoricalCrossentropy`
- Accuracy Metric

---

## 📈 Training Results
- **Epochs**: 5
- **Validation Split**: 10%
- **Final Test Accuracy**: ~98.1%

---

## 📷 Visualizations

### 🔹 Accuracy & Loss Graphs
![Accuracy Loss](images/acc_loss_plot.png)

### 🔹 Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)

### 🔹 Sample Predictions
![Predictions](images/predictions.png)

---

## ✅ Conclusion
- Achieved high accuracy with a simple CNN
- Effectively learned digit patterns from input images
- Demonstrated the power of deep learning on image classification

---

## 🚀 Future Improvements
- Add Dropout layers for regularization
- Increase epochs and tune hyperparameters
- Convert notebook into a web app using Streamlit or Flask

---

## 🛠️ Tools & Libraries
- TensorFlow / Keras
- Matplotlib / Seaborn
- Scikit-learn
- Google Colab

---

## 📧 Author
**Name**: Khushi 
