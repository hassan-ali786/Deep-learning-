# CNN Image Classification using CIFAR-10

A Deep Learning project implementing a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset.  
The goal is to understand how CNNs learn visual features and classify images into multiple categories.

---

## Project Overview

This project is my final project for the Data Science course.  
It demonstrates how to design, train, and evaluate a CNN for image classification tasks.

- Implemented a CNN model using Python and deep learning libraries  
- Worked with CIFAR-10 dataset containing 60,000 color images (32×32 pixels) across 10 classes  
- Learned practical concepts of feature extraction, convolution, pooling, and classification  

---

## About the Dataset (CIFAR-10)

The CIFAR-10 dataset consists of:

- 60,000 color images, 32×32 pixels  
- 10 Classes:  
  - Airplane  
  - Automobile  
  - Bird  
  - Cat  
  - Deer  
  - Dog  
  - Frog  
  - Horse  
  - Ship  
  - Truck  

Some images are low-resolution and visually challenging, making classification a difficult task.

---

## Project Structure

```bash
cnn-cifar10-classifier/
├── notebooks/
│   └── CIFAR.ipynb
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Model Architecture

**Model Used:** Convolutional Neural Network (CNN)  

**Components:**  

- Convolution layers  
- Pooling layers  
- Fully connected (Dense) layers  
- Softmax output layer  

**Implemented using:** Python, TensorFlow/Keras (or PyTorch if used)

---

## Challenges Faced

- Training on CPU instead of GPU, causing slow training  
- Limited computational resources  

**Outcome:** Achieved ~70% accuracy despite challenges, demonstrating effective learning on a complex dataset.

---

## Results

- Accuracy: ~70%  
- The model automatically extracted features like edges, shapes, and object patterns  
- Demonstrates how CNNs learn from data and improve through errors  

---

## Technologies Used

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-007D9C?style=flat&logo=matplotlib&logoColor=white) ![Deep Learning](https://img.shields.io/badge/Deep%20Learning-9B59B6?style=flat)
---

## Learning Outcomes

- Practical understanding of CNN architecture  
- Experience with image classification pipelines  
- Understanding impact of hardware (CPU vs GPU) on deep learning performance  
- Improved knowledge of model training, evaluation, and feature learning  

---

## Future Improvements

- Train the model using GPU for faster convergence  
- Implement data augmentation to improve accuracy  
- Experiment with deeper architectures (ResNet, VGG)  
- Deploy as a web app for real-time image classification  
- Visualize feature maps and learned filters  

---

## Author

Hassan Ali  
Data Scientist & Machine Learning Engineer


GitHub: https://github.com/hassan-ali786  

