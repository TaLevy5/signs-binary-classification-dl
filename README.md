# Binary Image Classification with Neural Network (NumPy)

This project was completed as part of the **"Basics of Deep Learning"** course at Colman College, 2024.

We implemented a feedforward neural network from scratch using NumPy to classify grayscale images of hand-sign digits (only digits 1 and 3) from a custom dataset. This assignment included designing the model architecture, implementing forward and backward propagation, and training the model using binary cross-entropy loss.

## 👨‍💻 Authors
- Tal Levy
- Omer Virshovsky

## 📊 Dataset
- Hand sign digit images (grayscale 28x28 pixels).
- Subset of 1000 images containing only digits 1 and 3.
- Data was flattened and normalized to values between 0 and 1.
- 80% training, 20% testing split.

## 🧠 Model Architecture
- Input layer: 784 neurons (flattened 28x28 images)
- 3 hidden layers: 128 neurons each, sigmoid activation
- Output layer: 1 neuron (binary classification)
- Loss: Binary Cross-Entropy (BCE)
- Optimizer: Gradient Descent

## 📈 Results
- **Accuracy**: 98% on test set
- **Confusion Matrix**:

  | Actual \ Predicted | 1 | 3 |
  |--------------------|---|---|
  | 1                  | 102 | 2 |
  | 3                  | 1   | 95 |

- Loss curve:  
  ![Loss graph](/LossGraph.png) *(add if you have image)*

## 📁 Files
- `basics_2025.ipynb` – Jupyter Notebook with full implementation
- `report.pdf` – Project documentation and discussion
- `README.md` – You’re here


## 🧠 What I Learned
- Manual implementation of a neural network using NumPy
- Fundamentals of backpropagation and gradient descent
- Evaluation using metrics such as confusion matrix and accuracy
- Working with real image data and binary classification

