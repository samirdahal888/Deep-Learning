# Deep-Learning
jan17 2025  
# 📌 Deep Learning Roadmap

## 🧾 [History](https://github.com/samirdahal888/Deep-Learning/tree/main/History)  
Explore the evolution of **machine learning (ML) algorithms**, how they have transformed over time, and how **deep learning neural networks** emerged.

---

# 📖 Chapter 2: Deep Learning & Neural Networks  
🔗 **[View Chapter](https://github.com/samirdahal888/Deep-Learning/tree/main/Deep%20learning%20%20and%20neural%20networks)**  

### 📌 Topics Covered:  

### 1️⃣ [Understanding Perceptrons & Multilayer Perceptrons (MLPs)](https://github.com/samirdahal888/Deep-Learning/tree/main/Deep%20learning%20%20and%20neural%20networks/%20Understanding%20perceptrons%20and%20multilayer%20%20perceptrons)  
   - 📜 **[Course PDF](https://github.com/samirdahal888/Deep-Learning/blob/main/Deep%20learning%20%20and%20neural%20networks/%20Understanding%20perceptrons%20and%20multilayer%20%20perceptrons/Understanding%20perceptrons%20and%20multilayer%20%20perceptrons.pdf)** – In-depth explanation of perceptrons and MLPs.  
   - 💻 **[Coding Practice](https://github.com/samirdahal888/Deep-Learning/tree/main/Deep%20learning%20%20and%20neural%20networks/%20Understanding%20perceptrons%20and%20multilayer%20%20perceptrons/coding%20practice)**  
     - 🔹 **[XOR Problem](https://github.com/samirdahal888/Deep-Learning/blob/main/Deep%20learning%20%20and%20neural%20networks/%20Understanding%20perceptrons%20and%20multilayer%20%20perceptrons/coding%20practice/Xor%20problem.ipynb)** – Demonstrating the **limitations of single-layer perceptrons**.  

### 2️⃣ Working with Different Types of Activation Functions  

### 3️⃣ Training Networks with Feedforward, Error Functions & Optimization  

### 4️⃣ Performing Backpropagation  

---

# 📖 Chapter 3: Convolutional Neural Networks (CNNs)  
🔗 **[View Chapter](#)**  

### 📌 Topics Covered:  

### 1️⃣ [Classifying Images Using MLP](https://github.com/samirdahal888/Deep-Learning/tree/main/Convolutional%20neural%20networks/%20Classifying_Images_Using_MLP)) 
   - Understanding how **MLPs process image data**  
   - Exploring **MLP limitations in image classification**  

### 2️⃣ [Working with CNN Architecture to Classify Images](https://github.com/samirdahal888/Deep-Learning/tree/main/Convolutional%20neural%20networks/%20Working%20with%20CNN%20Architecture%20to%20Classify%20Images)
#### - [CNN artitecture](https://docs.google.com/document/d/1d2-ZRboACga_mpcCkZjuAaRyANUyaJf0cPXVaLX5Bys/edit?usp=sharing)
#### - [Strides and padding](https://docs.google.com/document/d/18fPzCRTfJ-MIwFQrbE8S2-wZSx8wOzp6GzN6-rib-kc/edit?tab=t.0)
#### - [Pooling layer or Subsampling](https://docs.google.com/document/d/19QjOre42a-kO6qZDNppE4XuFsdRO3uPF6IwRYVUyFpI/edit?tab=t.0#heading=h.kkhk1enabcsz)
#### -[Fully connected(FC) layer](https://docs.google.com/document/d/1iTp62yNelF8aKbzppjVEzNt7-1m8qU7xxyBe6j9A8E4/edit?usp=sharing)
#### - [Avoid overfitting](https://docs.google.com/document/d/1gIlvl-I4l9GxyYqMDrsNJ7f3CGBSxvocKsG-xV4b9yE/edit?usp=sharing)
#### -[Dropout Layer](https://docs.google.com/document/d/1HIxSIaWisN7jo9M1g2i9BYvK3aTFYE_VzVMvtBT0RXk/edit?usp=sharing)
**project**  
   #### - [mnist_cnn](https://colab.research.google.com/drive/1ijyS122nkBexcMMfUAyqQPGuOf5I5oT0?usp=sharing)

   - Understanding **Convolutional Layers, Pooling Layers, and Fully Connected Layers**  
   - Implementing **CNNs for image classification**  

### 3️⃣ [Understanding Convolution on Color Images](#)  
#### - [Convolution over color image](https://docs.google.com/document/d/1mCdtIKcq-m0J8pPocRx5TNqH35tuOaQGX_7D7W5wVj8/edit?usp=sharing)
### projects
#### - [cifar10 cnn](https://colab.research.google.com/drive/12n3rKVSh9ozMmjyuJjcUuC0Wp2ip_cCW?usp=sharing)
   - Differences between **RGB and Grayscale image processing**  

--- 


# 📌 Introduction to Convolutional Neural Networks (CNNs)

## 📝 Overview of chapter 3
Convolutional Neural Networks (CNNs) are a specialized type of **artificial neural network (ANNs)** designed for **image processing**. Unlike traditional **Multilayer Perceptrons (MLPs)**, CNNs efficiently capture **spatial hierarchies** in images using **convolutional layers, pooling layers, and fully connected layers**.

---

## 📖 Chapter Roadmap

### 📌 1. Image Classification with MLP
- Implement an **MLP-based image classifier**.
- Identify **MLP’s limitations** in handling images.
- Understand why CNNs are needed for **computer vision tasks**.

### 📌 2. Understanding CNNs
- Learn how CNNs **extract features** from images.
- Explore **CNN’s three key components**:
  - **Convolutional Layers** → Feature extraction
  - **Pooling Layers** → Dimensionality reduction
  - **Fully Connected Layers** → Final classification
- Build a **mini CNN-based image classifier**.

### 📌 3. Color Images vs. Grayscale
- Understand how **computers process color images**.
- Learn about **convolution operations over multiple channels**.

### 📌 4. End-to-End Image Classification Project
- Apply all concepts to a **full-scale project**.
- Train a CNN model for **color image classification**.

---

## 🔍 MLP vs. CNN: Key Differences

| Feature              | **MLP (ANNs)**          | **CNNs**                  |
|----------------------|------------------------|---------------------------|
| **Architecture**     | Fully connected layers | Convolutional + Pooling layers |
| **Weights & Biases** | Vector-based           | Uses **filters/kernels**  |
| **Hyperparameters**  | Optimizer, Loss, Activation | Same + CNN-specific parameters |
| **Training**        | Forward pass → Loss → Backpropagation | Same process |

---
---




 
