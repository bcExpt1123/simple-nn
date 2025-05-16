# 🧠 Simple Neural Network from Scratch (NumPy)

![Simple Neural Network Diagram](/nn.png)

This repository contains a minimal implementation of a **2-layer neural network** built from scratch using only **NumPy**. It demonstrates how to:

* Generate and classify synthetic 2D data
* Implement a feedforward neural network
* Train using backpropagation and gradient descent
* Use ReLU and Sigmoid activations
* Track training loss and accuracy

---

## 🧪 Project Overview

The task is a **binary classification** problem on synthetic data where the label is determined by the rule:

> Class = 1 if `x * y > 0`, else Class = 0

This creates a non-linear decision boundary that a neural network must learn to classify accurately.

---

## 📂 Contents

* `SimpleNN` class — a 2-layer neural network
* Custom implementations of:

  * Activation functions (`ReLU`, `Sigmoid`) and derivatives
  * Loss function (`MSE`)
  * Accuracy metric
* Training loop with loss and accuracy printing
* Inference on new, unseen data

---

## 🚀 Getting Started

### Prerequisites

* Python 3.7+
* NumPy

### Run the Notebook

You can run the notebook using any Jupyter environment:

```bash
pip install notebook numpy
jupyter notebook
```

Or run directly if you're using a platform like **Kaggle**, **Colab**, or **VSCode**.

---

## 📈 Example Output

Training Progress:

```
Epoch 0: Loss = 0.2470, Accuracy = 0.6080
...
Epoch 790: Loss = 0.1290, Accuracy = 0.9730

Final Accuracy: 0.973
```

---

## 🔍 Sample Predictions

```python
Predicted classes: [(array([0]), 0), (array([0]), 0), ..., (array([1]), 1)]
```

---

## 🛠️ Customization Ideas

* Try different activation functions (e.g., Tanh)
* Switch to Binary Cross-Entropy loss for classification
* Add additional hidden layers or neurons
* Visualize decision boundaries using matplotlib

---

## 📄 License

This project is licensed under the MIT License — feel free to use, modify, and distribute.

