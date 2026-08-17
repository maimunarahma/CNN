
# 🪨📄✂️ Rock-Paper-Scissors Image Classification using CNN

A Deep Learning project that uses a **Convolutional Neural Network (CNN)** built with **PyTorch** to classify images of **Rock, Paper, and Scissors**.

The project demonstrates a complete image classification workflow, starting from standard RPS dataset preparation and preprocessing to CNN training, evaluation, and real-world prediction using custom smartphone photographs.

---

## 📌 Project Overview

The objective of this project is to build a CNN-based image classifier capable of recognizing three hand gesture classes:

- 🪨 Rock
- 📄 Paper
- ✂️ Scissors

The model is trained using a standard Rock-Paper-Scissors image dataset and then tested on both unseen standard test images and custom images captured using a smartphone.

The project is implemented entirely using **PyTorch** and can be reproduced through the provided Google Colab notebook.

---

## 🎯 Objectives

The main objectives of this project are:

1. Load and preprocess a standard Rock-Paper-Scissors dataset.
2. Automatically retrieve the project repository from GitHub.
3. Apply image preprocessing using `torchvision.transforms`.
4. Split the training dataset into training and validation sets.
5. Build a CNN architecture from scratch using `torch.nn.Module`.
6. Train the CNN using Cross-Entropy Loss and Adam optimizer.
7. Evaluate the model on an unseen test dataset.
8. Save the trained model as a PyTorch `.pth` state dictionary.
9. Load custom smartphone images automatically from GitHub.
10. Classify custom real-world images using the trained CNN.
11. Display prediction confidence using Softmax probabilities.
12. Visualize training history, confusion matrix, and prediction results.

---

# 📂 Repository Structure

```text
rps-cnn-pytorch/
│
├── dataset/
│   ├── rock1.jpg
│   ├── rock2.jpg
│   ├── rock3.jpg
│   ├── paper1.jpg
│   ├── paper2.jpg
│   ├── paper3.jpg
│   ├── scissor1.jpg
│   ├── scissor2.jpg
│   ├── scissor3.jpg
│   └── ...
│
├── model/
│   └── 210121.pth
│
├── 210121.ipynb
│
└── README.md
