
# Waste Management using Deep Learning

This repository contains code and documentation for an AI-powered waste management system that automates waste segregation into biodegradable and non-biodegradable categories. 

## Problem Statement

Rapid economic growth and urbanization has led to escalating waste generation globally. Unmanaged waste accumulation poses significant environmental and health hazards. An intelligent waste segregation system can enable proper waste disposal and recycling.

## Proposed Solution 

This project implements an automated waste classification system using deep convolutional neural networks. The key components are:

- Image classification models (CNN, VGG16, ResNet50) pretrained on the [Waste Image Dataset](https://www.kaggle.com/datasets/asdasdasasdas/waste-image-dataset) from Kaggle containing 15,150 labelled waste images 

- Custom compartments with servo motors to segregate biodegradable and non-biodegradable waste into separate bins

- Infrared sensors, load cells and camera modules for real-time waste monitoring

- IoT connectivity for data analytics and tracking

## Technical Implementation

- TensorFlow and Keras used for training deep learning classification models
- OpenCV for image preprocessing and augmentation
- Embedded system with Intel Core 15 processor for overall system control

## Results

The models achieve the following accuracy on the test set:

- CNN: 76.07%
- VGG16: 88.83% 
- ResNet50: 97.47%

ResNet50 delivers the best performance for classifying waste images.

## Future Work

- Deploy the solution in real-world pilot projects 
- Expand for multi-class classification with more waste categories
- Optimize hardware design for scalability

## Contributing

Contributions are welcome! Please refer to `contributing.md` for guidelines.
