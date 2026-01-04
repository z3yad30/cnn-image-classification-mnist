# cnn-image-classification-mnist
# CNN Image Classification on MNIST

## 📌 Project Overview
This project demonstrates building a Convolutional Neural Network (CNN) from scratch to classify handwritten digits from the MNIST dataset. The goal is to showcase a complete deep learning workflow, including data preprocessing, model architecture design, training, evaluation, and performance analysis using TensorFlow and Keras.

## 📂 Dataset
- **MNIST Handwritten Digits Dataset**
- 60,000 training images and 10,000 test images
- Grayscale images of size 28×28
- 10 classes (digits 0–9)

## 🧠 Model Architecture
The CNN model is built from scratch and includes:
- Convolutional layers for feature extraction
- MaxPooling layers for spatial reduction
- Fully connected (Dense) layers for classification
- Softmax activation for multi-class output

Regularization techniques are applied to reduce overfitting and improve generalization.

## ⚙️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook

## 📊 Training & Evaluation
- Loss Function: Categorical Crossentropy
- Optimizer: Adam
- Evaluation Metrics: Accuracy
- Performance evaluated on a held-out test set
- Training and validation curves used to monitor overfitting

## ✅ Results
The model achieves high accuracy on the MNIST test set, demonstrating the effectiveness of CNNs for image classification tasks and validating correct implementation of deep learning fundamentals.

## 🚀 How to Run
1. Clone the repository
2. Install required libraries:
   ```bash
   pip install tensorflow numpy matplotlib
3.Open the notebook:
  ```bash
   jupyter notebook
```
4.Run all cells sequentially

📌 Key Takeaways

Built a CNN from scratch without pretrained models

Gained hands-on experience with convolutional layers

Applied best practices for training and evaluation

Strengthened deep learning fundamentals

📄 Author

Developed as part of a hands-on deep learning learning journey.

