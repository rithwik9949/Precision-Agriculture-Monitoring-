​
# Precision Agriculture Monitoring using GoogLeNet

This project is a Deep Learning based Precision Agriculture system developed for automatic crop disease detection using crop leaf images. The model uses the pretrained GoogLeNet Convolutional Neural Network (CNN) architecture with Transfer Learning to classify healthy and diseased crops accurately.

The system performs image preprocessing, data augmentation, model training, validation, and prediction using PyTorch and Torchvision libraries. Crop images are transformed using resizing, normalization, horizontal flipping, and augmentation techniques to improve model robustness and accuracy.

The pretrained GoogLeNet model is fine-tuned by modifying the final fully connected layer to classify agricultural crop categories such as Apple Healthy, Apple Rust, Corn Healthy, and Corn Blight. Training is performed using CrossEntropyLoss, Adam optimizer, and learning rate scheduling for better convergence and performance.

This project demonstrates how Artificial Intelligence and Deep Learning can support smart farming by enabling early crop disease detection, reducing crop damage, improving productivity, and supporting Precision Agriculture automation.

## Technologies Used

* Python
* PyTorch
* Torchvision
* NumPy
* Matplotlib
* Deep Learning
* CNN (GoogLeNet)
* Transfer Learning

## Features

* Crop disease classification
* Precision Agriculture monitoring
* Pretrained GoogLeNet implementation
* Data augmentation and preprocessing
* Accuracy and loss visualization
* Transfer Learning based training
* Real-time crop image prediction support

## Future Scope

* Mobile application integration
* IoT and sensor connectivity
* Drone-based crop monitoring
* Real-time field analysis
* Multi-disease crop detection
