Deep Learning Mini Projects (PyTorch)

This repository contains two Deep Learning mini projects implemented using PyTorch, focusing on model training and evaluation for classification and regression problems.

These projects demonstrate core deep learning concepts, including data preprocessing, neural network design, training loops, and evaluation metrics.

📌 Project 1: MNIST Image Classification
🔍 Problem Type

Multi-class Classification

📊 Dataset

MNIST handwritten digits

28×28 grayscale images

Classes: digits 0–9

🧠 Model

Fully Connected Neural Network (MLP)

Layers:

Flatten

Dense (32) + ReLU

Dense (16) + ReLU

Dense (10)

⚙️ Training Setup

Loss Function: CrossEntropyLoss

Optimizer: Adam

Batch Size: 64

Epochs: 20

📈 Evaluation

Metric: Accuracy

Evaluated on test dataset

🎯 Objective

Understand how neural networks perform image classification using PyTorch.

📌 Project 2: Auto MPG Regression
🔍 Problem Type

Regression

📊 Dataset

Auto MPG Dataset (UCI Repository)

Target: Miles Per Gallon (MPG)

🧹 Preprocessing

Removed missing values

Normalized numerical features

Bucketized model year

One-hot encoded origin feature

Train/test split (80/20)

🧠 Model

Fully Connected Neural Network

Layers:

Dense (8) + ReLU

Dense (4) + ReLU

Dense (1)

⚙️ Training Setup

Loss Function: Mean Squared Error (MSE)

Optimizer: SGD

Batch Size: 8

Epochs: 200

📈 Evaluation

Metrics:

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

🎯 Objective

Learn how neural networks can be applied to continuous value prediction.

🛠️ Technologies Used

Python

PyTorch

Torchvision

NumPy

Pandas

Scikit-learn

📂 Project Structure
Mini_project_dl/
│
├── Classification/
│   └── mnist_classification.py
│
├── Regression/
│   └── regression.py
│
├── requirements.txt
└── README.md

▶️ How to Run
pip install -r requirements.txt

Classification
python Classification/mnist_classification.py

Regression
python Regression/regression.py

🎯 What This Project Demonstrates

Neural network implementation using PyTorch

Difference between classification and regression

Proper preprocessing for tabular & image data

Training and evaluation workflows

Usage of DataLoader and loss functions

🚀 Possible Extensions (to make it end-to-end later)

Save trained models

Add inference scripts

Add FastAPI for predictions

Add visualization of metrics

Deploy using Docker
