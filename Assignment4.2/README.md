# 🖼️ CNN Image Classification using CIFAR-10

## 📌 Project Overview

This project implements a **Convolutional Neural Network (CNN)** to classify color images from the **CIFAR-10** dataset. The model is built using TensorFlow/Keras and is capable of classifying images into one of ten object categories.

---

## 🎯 Objective

- Load and preprocess the CIFAR-10 dataset.
- Build a CNN using Conv2D, ReLU, MaxPooling, Flatten, Dense, and Softmax layers.
- Train and evaluate the model.
- Predict classes for sample test images.
- Generate a confusion matrix to analyze model performance.

---

## 📂 Dataset

- **Dataset:** CIFAR-10
- **Source:** TensorFlow/Keras Datasets
- **Training Images:** 50,000
- **Testing Images:** 10,000
- **Image Size:** 32 × 32 × 3
- **Classes:** 10

### Classes

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧠 CNN Architecture

- Conv2D (32 Filters, ReLU)
- MaxPooling2D
- Conv2D (64 Filters, ReLU)
- MaxPooling2D
- Flatten
- Dense (64, ReLU)
- Dense (10, Softmax)

---

## 📊 Model Evaluation

The model was evaluated using:

- Test Accuracy
- Test Loss
- Training Accuracy Curve
- Validation Accuracy Curve
- Training Loss Curve
- Validation Loss Curve
- Confusion Matrix
- Sample Predictions

---

## 📁 Project Structure

```
CNN-Image-Classification-CIFAR10/
│
├── model/
│   └── cifar10_cnn.keras
│
├── CNN_Image_Classification.ipynb
├── report/
│   └── Project_Report.pdf
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## 🚀 How to Run

1. Clone the repository.

```bash
git clone <repository-link>
```

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Open the notebook.

4. Run all cells sequentially.

---

## 📌 Results

- Successfully trained a CNN model on the CIFAR-10 dataset.
- Evaluated the model using test accuracy and test loss.
- Generated a confusion matrix.
- Predicted sample test images successfully.

---

## 👩‍💻 

**Sudiksha Chauhan**

