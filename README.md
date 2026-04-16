# 🧠 Facial Similarity using Siamese Networks (PyTorch)

This project demonstrates how to use Siamese Neural Networks to determine the similarity between two images. The model learns to distinguish whether two input images belong to the same class or not.

---

## 📌 Overview

Siamese Networks are a special type of neural network architecture that compares two inputs and learns their similarity. Instead of classifying images directly, the model learns a function that maps images into an embedding space where similar images are closer together.

---

## 📂 Dataset

The project uses a face dataset where:
- Each class (person) is stored in a separate folder  
- Each folder contains multiple images of the same individual  

This structure follows the standard format used in PyTorch image datasets.

---

## ⚙️ Model Concept

- Two identical neural networks (shared weights) process two input images  
- The outputs are compared using a distance function  
- The network learns to minimize distance for similar images and maximize it for different ones  

---

## 🛠️ Technologies Used

- Python  
- PyTorch  
- NumPy  
- OpenCV / PIL  

---

