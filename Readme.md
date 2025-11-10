# Handwritten Digit Recognition (Kaggle)

A deep learning project for recognizing handwritten digits, developed for the Kaggle "Digit Recognizer" competition. This repository includes scripts for training a model on the MNIST dataset and an interactive GUI for real-time predictions of hand-drawn numbers.

**Author:** Pierre-Guillaume Petitmangin
**Affiliation:** École des Mines

---

## Overview

This project implements a (Convolutional Neural Network / *Specify your model type here*) using *[e.g., TensorFlow/Keras or PyTorch]* to classify images of handwritten digits from 0 to 9.

The primary goal is to achieve high accuracy on the Kaggle competition dataset. A secondary feature is an interactive canvas application where a user can draw a digit with their mouse, and the trained model will predict the number.


---

## 🛠️ Technical Stack & Setup

This project uses several deep learning and data processing libraries. To ensure a stable and reproducible environment, **Poetry** is highly recommended for dependency management.

### Key Libraries
* Python 3.9+
* Poetry
* TensorFlow / PyTorch *(select one)*
* NumPy
* Pandas
* Scikit-learn (for metrics)
* *Optional (for GUI):* Tkinter / Pygame / Gradio

---


---

## 📊 Dataset

The model is trained on data from the **Kaggle "Digit Recognizer" competition**, which is a high-resolution version of the classic MNIST dataset.

You must download the following files from the [Kaggle competition page](https://www.kaggle.com/c/digit-recognizer/data) and place them in the `data/` directory:
* `train.csv`
* `test.csv`
If you had git clone the rep it's already done.
---
