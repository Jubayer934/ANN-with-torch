# 🧠 MNIST Digit Classifier (ANN)

This project uses a basic **Artificial Neural Network (ANN)** built with **PyTorch** to classify handwritten digits from the **MNIST** dataset.

## 🔧 Features
- Fully connected neural network
- Trained on MNIST dataset (28x28 grayscale images)
- Uses ReLU activation, CrossEntropyLoss, and Adam optimizer

## ⚙️ Model Details
- **Input Layer:** 784 units (28×28 pixels)
- **Hidden Layer:** 500 units (ReLU)
- **Output Layer:** 10 units (digit classes 0–9)

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install torch torchvision
   ```
2. Run the `ANN.ipynb` notebook in Jupyter or Google Colab.

## 📈 Output
- Prints training progress and final test accuracy.
