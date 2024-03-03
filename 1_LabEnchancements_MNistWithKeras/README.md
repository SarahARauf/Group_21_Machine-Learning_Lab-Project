# Machine Learning - Overview of Neural Networks and CNNs using CIFAR100 and Tensorflow

This lab exercise is optimised for Google Colab. We will learn how to train a deep learning model on image data using Tensorflow. Make sure to change runtime type to "T4 GPU" as this would be computationally heavy.

---
In this lab enhancement, the following are done:

1. Using CIFAR100 RGB image dataset
- A slightly more complicated dataset compared to MNIST handwriting dataset due to being RGB (having 3 channels)
2. Proper data splitting techniques
- How to split data using train_test_split from SKLearn
2. Understanding image data dimensions (RGB vs B&W)
- Understanding that B&W will have 1 channel and RGB images have 3 channels using '.shape' 
3. Preprocessing image data using a data generator
- Using ImageDataGenerator to do quick augmentations to your image
4. Preprocessing label data using one-hot-encoding
- Using to_categorical from Keras library
5. Deeper explanations of components to a CNN model
- Explaining convolutional layers, flatten layers, dense layer
6. Deeper explanations of model training
- Explaining optimizer, loss function, metrics, batch size and epoch
- Using a custom optimizer
7. Using pretrained models
- Train CIFAR100 using ResNet50 pretrained with ImageNet weights.
---

