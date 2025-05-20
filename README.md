# 🧠 CNN from Scratch (NumPy Implementation)

This project is a **from-scratch implementation of a Convolutional Neural Network (CNN)** using only **NumPy**, with no deep learning frameworks like TensorFlow or PyTorch. It's built to demonstrate a low-level understanding of how CNNs work under the hood.

<p align="center">
  <img src="images/Convolution_schematic.gif" alt="Convolution process animation" width="600"/>
</p>

---

## 🚀 Features

- Manual forward pass for:
  - Convolutional layers
  - Max pooling
  - ReLU activation
  - Flattening and fully connected layers
- Backpropagation through all layers
- Simple training loop with cross-entropy loss
- Accuracy tracking and parameter updates using SGD

---

## 📚 What You'll Learn

- How convolution works mechanically (stride, padding, kernels)
- The role of pooling layers in reducing spatial dimensions
- How activations and gradients flow through each layer
- What it takes to build a deep learning model without black-box libraries
