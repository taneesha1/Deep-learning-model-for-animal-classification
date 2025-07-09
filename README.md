# Deep-learning-model-for-animal-classification

# CNN-Based Dog vs Cat Image Classifier

This project contains a **Jupyter Notebook** that implements a **Convolutional Neural Network (CNN)** to classify images of dogs and cats using Keras and TensorFlow. The notebook walks through all the steps — from data loading and preprocessing to model training and evaluation.

---

## Training Overview

The model was trained for **15 epochs**, achieving:

- **Training Accuracy**: up to **98.7%**
- **Validation Accuracy**: peaked at **84.0%**
- Slight overfitting observed after epoch 6

---

## Model Summary

- **Layers**:
  - 2× Conv2D + MaxPooling
  - Flatten → Dense → Dropout → Sigmoid
- **Loss Function**: Binary Crossentropy
- **Optimizer**: Adam
- **Frameworks**: TensorFlow, Keras

---

## How to Run

1. Open the notebook in Jupyter or Google Colab
2. Make sure you have the necessary libraries: tensorflow numpy matplotlib


## Planned Improvements

This project will be improved further to better handle **overfitting** and increase the model's **generalization performance**. The following enhancements are planned:

- **Applying data augmentation**  
  Introduce random transformations such as flipping, rotation, and zooming to increase dataset variability.

- **Introducing early stopping and learning rate scheduling**  
  Halt training when validation loss stops improving, and dynamically adjust the learning rate for stability.

- **Experimenting with dropout rates**  
  Fine-tune dropout layers to reduce reliance on specific neurons and improve regularization.

- **Exploring transfer learning with pretrained CNN models**  
  Use powerful architectures like **ResNet**, **MobileNet**, or **EfficientNet** for improved feature extraction on limited data.

