# ✍️ Handwritten Character Recognition - CodeAlpha Internship Project

This project is part of the **CodeAlpha Machine Learning Internship**, aimed at building a deep learning model that recognizes handwritten English **letters (A–Z)** using the EMNIST dataset.

---

## 📌 Objective

To classify handwritten characters using image processing and convolutional neural networks (CNNs). The model is trained on EMNIST-Letters dataset, which includes thousands of grayscale images of handwritten letters.

---

## 📁 Dataset Used

- **EMNIST Letters** dataset  
- 28x28 grayscale images of handwritten characters (A-Z)

---

## 🧠 Technologies Used

- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib  
- Scikit-learn

---

## 🔍 Model Architecture

- Input Layer: 28x28 image  
- 2 Conv2D layers with MaxPooling  
- Flatten + Dense hidden layer  
- Output layer with 26 classes (A-Z)

---

## 🔢 Sample Output

```python
Input: 28x28 image of handwritten "B"  
Output Prediction: B  
Accuracy: 92.3%
