# Bangkit 2024 Capstone Team - Machine Learning Path

## Members
| **Student ID**   | **Name**                         | **Path**           | **University**                 |
|-------------------|----------------------------------|--------------------|---------------------------------|
| M312B4KY0437      | Alvito Muhammad Yan Fahriel     | Machine Learning  | Universitas Sebelas Maret      |
| M312B4KY0660      | Arma Nasrul Mustofa             | Machine Learning  | Universitas Sebelas Maret      |
| M312B4KY0660      | Billie Zandra Widiyanto         | Machine Learning  | Universitas Sebelas Maret      |

## Dataset
https://www.kaggle.com/datasets/mostafaabla/garbage-classification/data

## Model Architecture: ResNet50
We utilize **ResNet50**, a deep convolutional neural network that is widely recognized for its performance in image classification and feature extraction tasks. 

## Features
- **Data Augmentation**: Enhanced training with image transformations like flipping, rotation, and zooming.
- **Transfer Learning**: Leveraging pre-trained ResNet50 on ImageNet for efficient training.
- **Fine-Tuning**: Adjusting the top layers of ResNet50 for better performance.
- **Deployment-Ready**: Model export to TensorFlow.js for integration with web applications.

## Model Accuracy & Loss
<code>- accuracy: 0.9898 - loss: 0.0429 - val_accuracy: 0.9492 - val_loss: 0.1785 - learning_rate: 1.0000e-04</code>
<p align="left">
  <img src="https://github.com/capstonec242ps168/Machine-Learning-Model/blob/main/Result/Grafik.png" alt="Deskripsi Gambar" style="width:100%; border: 1px solid black;">
</p>
