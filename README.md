# Neural Network from Scratch 🧠

Welcome to **Neural Network from Scratch**, a simple and educational project where a neural network is built from the ground up using only `numpy`, without any deep learning frameworks.

This project demonstrates the **forward pass** and **backward pass (manual backpropagation)** of a neural network trained on a synthetic dataset.

## 📄 Project Overview

The **Neural Network from Scratch** project provides:

* A step-by-step implementation of a neural network.
* Detailed walkthrough of forward and backward propagation.
* Training on a synthetic spiral dataset for visualization.

This project is purely educational and focuses on understanding the core concepts behind neural networks.

## 🛠️ Tech Stack

* **Python 3** – Programming language.
* **NumPy** – Numerical computations.
* **Matplotlib** – Visualization of the data and decision boundaries.
* **nnfs** – For generating the spiral dataset.

## 🚀 Features

* Forward pass through layers.
* Manual backward pass (backpropagation).
* Loss calculation and gradient updates.
* Visualization of decision boundaries.
* Clean, well-commented code for learning purposes.

## ⚙️ Requirements

You need the following Python packages:

* `numpy`
* `matplotlib`
* `nnfs`

Install them using:

```bash
pip install numpy matplotlib nnfs
```

## 🚀 How to Run

### 📥 Clone the Repository

```bash
git clone https://github.com/SrijaaimeenakshiM/Neural_network_from_scratch.git
```

### 🔢 Navigate to the project folder

```bash
cd Neural_network_from_scratch
```

### 📦 Install the required packages

```bash
pip install numpy matplotlib nnfs
```

### 💻 Open the notebook

```bash
jupyter notebook neural_network_forward_backward_from_scratch.ipynb
```

Run the cells step by step to see the forward and backward pass of the neural network in action.

## 📊 Dataset

The project uses the spiral dataset from the nnfs package:

```python
from nnfs.datasets import spiral_data
X, y = spiral_data(samples=100, classes=3)
```

This is a synthetically generated dataset commonly used for testing classification models.

## 📂 Project Structure

```plaintext
Neural_network_from_scratch/
│
├── README.md                                            # Project documentation
├── neural_network_forward_backward_from_scratch.ipynb   # Jupyter Notebook with full neural network implementation

```


