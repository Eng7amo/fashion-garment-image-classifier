# CNN-Based Garment Classifier

## Objective
The objective of this project is to develop a convolutional neural network capable of classifying images of clothing items into distinct garment categories.

The classifier is designed to support automated product categorization in e-commerce environments.

---

## Dataset
The project uses the **FashionMNIST** dataset, which consists of:
- 60,000 training images
- 10,000 test images
- 10 garment categories

Images are grayscale with a resolution of 28×28 pixels.

---

## Methodology

### 1. Data Loading
- FashionMNIST is loaded using `torchvision.datasets`
- Images are converted to tensors
- Data is batched using PyTorch DataLoaders

### 2. Model Architecture
The CNN consists of:
- Two convolutional layers with ReLU activation
- Max pooling layers for spatial reduction
- Dropout for regularization
- Fully connected layers for classification

### 3. Training
- Loss function: CrossEntropyLoss
- Optimizer: Adam
- Training performed for a small number of epochs for demonstration

### 4. Evaluation
Model performance is evaluated on the test set using:
- Accuracy
- Precision (per class)
- Recall (per class)

---

## Tools Used
- PyTorch
- Torchvision
- TorchMetrics
- NumPy

---

## Outputs
- Trained CNN model
- Classification metrics
- Reproducible training and evaluation pipeline

---

## Notes
This project emphasizes clarity, modularity, and practical application of deep learning for image classification.
