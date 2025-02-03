# Apple Leaf Disease Classification with Deep Learning

## Project Overview

This project uses the **PlantVillage Dataset** to analyze and classify apple leaf images based on their condition or disease. The dataset includes three categories: **Apple___Apple_scab**, **Apple___Black_rot**, and **Apple___healthy**, with grayscale images of apple leaves. The focus is on applying various machine learning techniques, such as PCA, clustering algorithms, and neural networks, for dimensionality reduction, clustering, and classification.

## Steps Involved

### 1. **PCA for Variance Preservation**
   - PCA is applied to determine the number of components needed to preserve 90% of the variance in the dataset.

### 2. **Image Visualization**
   - 10 random images from the dataset are plotted in their original form (without PCA), and their PCA reconstruction (keeping 90% variance) is compared.

### 3. **Dimensionality Reduction and Clustering**
   - PCA is used to reduce dimensionality to 2D, followed by clustering with **K-Means** and **Expectation-Maximization (EM)** algorithms. 
   - The number of clusters is determined, set to 3, and clustering accuracy is reported.

### 4. **Neural Network Classification**
   - A feedforward neural network is built using **Keras (TensorFlow)** or **PyTorch**, with ReLU activation in hidden layers and 8 neurons in the output layer. 
   - The network is trained, and training/validation accuracy and loss are plotted across epochs.
   - The total number of parameters and bias parameters in the network are calculated.
