# 🧠 Deep Learning Model Optimization – MNIST Digit Classification

This project explores the effect of different architectural designs and hyperparameters on the performance of CNN, ANN, and SVM models using the MNIST dataset. Over **24 models** were trained and evaluated to understand how tuning structure, dropout, activation functions, batch size, and optimizers impacts model performance.

---

## 🎯 Objectives

- Build and evaluate multiple deep learning architectures (CNN, ANN, SVM)
- Compare performance based on accuracy, loss, training time, and complexity
- Study the impact of:
  - Number of Conv2D and Dense layers
  - Dropout rates and placement
  - Activation functions (ReLU, Sigmoid, Tanh, Swish)
  - Optimizers (SGD, Adam, RMSprop) and learning rates
  - Batch size variations
  - Number of epochs

---

## 🧪 Models Tested

- ✅ **CNNs** – Tested structural variations:
  - 1–3 Conv2D layers
  - 0–2 Dense layers
  - Dropout added at different locations with multiple rates
- ✅ **Simple ANNs**

- ✅ **Simple SVM**

---

## 📊 Best Performing Model

| Model Type | Test Accuracy | Optimizer | Key Features |
|------------|----------------|-----------|----------------|
| CNN        | **99.30%** ✅ | Adam (lr=0.001) | 2 Conv2D + Dropout(0.5) after Flatten |

---

## ⚙️ Technologies Used

- Python 3.x
- TensorFlow / Keras
- Scikit-learn
- NumPy, Matplotlib, Seaborn
- Jupyter Notebook

---

## 📌 Key Learnings

- Proper tuning of dropout rate and its location significantly impacts accuracy and overfitting.
- Adding more layers doesn't always improve results—smarter design beats deeper design.
- Batch size and activation choice can affect training stability and convergence.

---

## 📄 Report

A full report (`report.pdf`) is included in this repository. It contains:
- Accuracy and loss graphs
- Architecture comparison
- Training time analysis
- Parameter count breakdowns
- Final recommendations

---

## ⭐️ Acknowledgements

This project was part of a deep learning coursework project focused on practical experimentation and model evaluation using the MNIST dataset.


## Project Files

Final Notebook: https://colab.research.google.com/drive/1dShUuXRdaU9a6CB5VI6bWiQXTg6VtklQ?usp=sharing#scrollTo=sSA9SNEDuWJr

Final Report: https://docs.google.com/document/d/1GSP-21gp4PETNi-F0-_MGhJIfkXnAoaYjXkxNxATW_k/edit?tab=t.0

Project plan and summary:https://docs.google.com/document/d/1-ySPEpM7SosVOKQjDzf2C1zzksfDerXhG8zv6EK6Aw4/edit?tab=t.0