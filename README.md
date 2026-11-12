# 🔥 PyTorch Learning Journey

A hands-on learning repository focused on **PyTorch and Deep Learning**, featuring practical code examples, exercises, and implementations covering tensor operations, linear models, loss functions, autograd, gradient descent, neural networks, optimizers, and Convolutional Neural Networks (CNNs).

As a BSc (Hons) Computer Science with AI student, I am strengthening my understanding of deep learning through practical implementations, experiments, and real-world machine learning projects.

## 🎯 Learning Objectives

- Understand PyTorch fundamentals and tensor operations.
- Create and manipulate tensors using different methods.
- Understand linear models, weights, biases, and predictions.
- Learn loss functions and Mean Squared Error (MSE).
- Understand autograd and automatic differentiation.
- Implement gradient descent and backpropagation.
- Build neural networks using `nn.Module` and `nn.Sequential`.
- Work with layers, activation functions, and optimizers.
- Train and evaluate deep learning models.
- Understand CNN architecture and image processing.
- Build an MNIST handwritten digit classification model.
- Save and load trained PyTorch models.

## 📚 Topics Covered

### 1. PyTorch Setup and Tensor Fundamentals

- Installing and configuring PyTorch.
- Creating tensors using `torch.tensor()`, `torch.zeros()`, `torch.ones()`, and `torch.rand()`.
- Understanding 1D and 2D tensors.
- Exploring tensor properties such as `shape`, `dtype`, and dimensions.
- Performing tensor indexing and mathematical operations.
- Integrating NumPy with PyTorch using `torch.from_numpy()`.

### 2. Linear Models and Manual Predictions

- Understanding weights and biases.
- Implementing linear equations using `y_pred = w * x + b`.
- Making predictions using tensors.
- Understanding Mean Squared Error (MSE).
- Calculating prediction errors and loss values.

### 3. Autograd and Gradient Descent

- Understanding automatic differentiation.
- Using `requires_grad=True`.
- Exploring computation graphs.
- Calculating gradients using `loss.backward()`.
- Understanding `.grad` and gradient accumulation.
- Updating weights manually.
- Using `torch.no_grad()` for parameter updates.
- Clearing gradients using `.grad.zero_()`.
- Implementing training loops, epochs, and learning rates.

### 4. Neural Networks, Layers, and Optimizers

- Building neural networks using `nn.Module`.
- Understanding `__init__()`, `super().__init__()`, and `forward()`.
- Working with `nn.Linear()` and `nn.Sequential()`.
- Using activation functions such as ReLU.
- Implementing loss functions using `nn.MSELoss()`.
- Working with Adam optimizer.
- Understanding forward propagation and backpropagation.
- Using `optimizer.zero_grad()` and `optimizer.step()`.
- Saving model parameters using `torch.save()` and `state_dict()`.

### 5. MNIST Handwritten Digit Classification

- Exploring the MNIST handwritten digit dataset.
- Loading datasets using `torchvision.datasets.MNIST`.
- Applying image transformations using `transforms.ToTensor()`.
- Understanding `DataLoader`, batching, and shuffling.
- Building a fully connected neural network (784 → 128 → 64 → 10).
- Using ReLU activation and `CrossEntropyLoss`.
- Selecting CPU or GPU using `torch.device()`.
- Understanding training and evaluation modes.
- Making predictions using `argmax()`.
- Visualizing predictions using Matplotlib.
- Achieved **97.65% test accuracy**.

### 6. Convolutional Neural Network (CNN) Fundamentals

- Understanding CNN architecture and its applications.
- Working with `nn.Conv2d()`.
- Understanding input channels and output channels.
- Exploring kernel size, stride, and padding.
- Understanding feature maps and convolution operations.
- Working with `nn.MaxPool2d()`.
- Understanding spatial dimension reduction.
- Exploring image dimensions (28×28 → 14×14).

### 7. Final Project: CNN-Based MNIST Classification

- Building a custom `SimpleCNN` model.
- Implementing convolutional layers and ReLU activation.
- Applying max pooling for feature extraction.
- Building fully connected layers.
- Flattening feature maps using `x.view(x.size(0), -1)`.
- Calculating feature dimensions (16 × 7 × 7).
- Training and evaluating the CNN model.
- Monitoring average training loss.
- Achieved **97.92% test accuracy**.
- Saving the trained model as `simple_cnn_mnist.pth`.

### 8. Python Environment Verification

- Checking the installed Python version.
- Verifying the Python executable path.
- Checking Matplotlib version.
- Understanding virtual environment configuration.
- Verifying the development environment.

## 🛠️ Technologies Used

- **Python** — Programming language.
- **PyTorch** — Deep learning framework.
- **Torchvision** — Computer vision datasets and transformations.
- **NumPy** — Numerical computing.
- **Matplotlib** — Data visualization.
- **MNIST** — Handwritten digit dataset.
- **Jupyter Notebook / VS Code** — Coding and practice environment.
- **Git and GitHub** — Version control and project management.

## ⚙️ Installation and Setup

### Prerequisites

Install Python 3 and Git on your system.

### 1. Clone the Repository

```bash
git clone https://github.com/dilkashshekh11/Pytorch-Learning-Journey.git
```

### 2. Navigate to the Project Folder

```bash
cd Pytorch-Learning-Journey
```

### 3. Create a Virtual Environment (Optional)

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

### 4. Install Required Libraries

```bash
pip install torch torchvision numpy matplotlib jupyter
```

### 5. Verify PyTorch Installation

```python
import torch

print("PyTorch Version:", torch.__version__)
print("CUDA Available:", torch.cuda.is_available())
```

### 6. Start Practicing

```bash
jupyter notebook
```

Alternatively, open the project folder in VS Code and run the Python files or notebooks directly.

## 💻 Hands-On Practice

This repository contains practical exercises and implementations covering:

- Tensor creation, indexing, and mathematical operations.
- NumPy and PyTorch integration.
- Linear models and manual predictions.
- Loss calculation and gradient descent.
- Autograd and automatic differentiation.
- Neural network architecture and optimization.
- MNIST dataset loading and classification.
- CNN layers, convolution, and max pooling.
- Deep learning model training and evaluation.
- Model saving and environment verification.

## 📊 Learning Results

| Model | Dataset | Test Accuracy |
|---|---|---:|
| Fully Connected Neural Network | MNIST | 97.65% |
| Convolutional Neural Network (CNN) | MNIST | 97.92% |

*These are the results from my practical experiments during this learning journey.*

## 🚀 Why PyTorch Matters

PyTorch is a powerful deep learning framework used to develop and train neural networks. Understanding PyTorch helps build a strong foundation in deep learning, computer vision, neural network architectures, and modern AI applications.

Learning PyTorch also provides practical experience with model development, optimization, training, evaluation, and deployment workflows.

## 🎯 My Learning Goal

My goal is to strengthen my understanding of Deep Learning, Neural Networks, and Computer Vision through consistent practice, practical implementations, and continuous experimentation as a future **AI Engineer**.

This repository documents my progress and serves as a reference for revising PyTorch concepts and building more advanced AI projects.

## 🤝 Contributions and Feedback

This is a learning-focused repository. Suggestions, corrections, and feedback are welcome as I continue improving my programming and deep learning skills.

## 👨‍💻 Author

**Dilkash Shekh**

- GitHub: [@dilkashshekh11](https://github.com/dilkashshekh11)
- Learning Focus: Python | PyTorch | Deep Learning | Machine Learning | Computer Vision | Artificial Intelligence

---

⭐ If you find this repository useful, consider giving it a star!

*Learn consistently. Practice regularly. Build intelligently.* 🤖
