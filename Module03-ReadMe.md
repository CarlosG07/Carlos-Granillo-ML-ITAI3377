# Assignment: AI Model Deployment on a Simulated Edge Device

## Problem Statement

The goal of this assignment was to understand how an AI model can be trained, optimized, and deployed on an edge device. The challenge was to simulate a real-world environment where computing resources are limited, while still maintaining good model performance.

## Objectives

* Train a machine learning model using image data
* Convert the model into a lightweight format for edge deployment
* Simulate running the model on an edge device
* Evaluate performance such as accuracy and latency

## Approach

To solve this problem, I:

* Used the MNIST dataset of handwritten digits
* Built a Convolutional Neural Network (CNN) using TensorFlow
* Preprocessed the data by normalizing pixel values and reshaping images
* Trained the model and evaluated its performance
* Converted the trained model into TensorFlow Lite (TFLite) format
* Deployed the model using Edge Impulse to simulate an edge device

## Technologies Used

* Python
* TensorFlow
* TensorFlow Lite (TFLite)
* Edge Impulse CLI
* Node.js & npm
* Visual Studio Code

## Implementation Steps

1. Set up development environment (Python, TensorFlow, Edge Impulse)
2. Loaded and preprocessed the MNIST dataset
3. Built and trained a CNN model
4. Evaluated training and validation accuracy
5. Converted the model to TFLite format
6. Uploaded and deployed the model using Edge Impulse
7. Simulated real-time inference using the Linux Runner

## Results

* Training Accuracy: ~98%
* Validation Accuracy: ~97%
* Inference Accuracy: ~96–97%
* Latency: ~35–50 ms per prediction
* Model Size: ~1.2 MB

## Analysis

The model performed well with high accuracy and low latency, making it suitable for edge environments. There was a small drop in accuracy after converting to TFLite, which is expected due to optimization for performance. This assignment showed the trade-off between model complexity and efficiency.

## Challenges

* Setting up the Edge Impulse environment correctly
* Running commands in the correct environment (terminal vs Python)
* Managing dependencies and installation issues

I solved these by carefully following setup steps and troubleshooting errors step-by-step.

## Future Improvements

* Use more advanced or optimized models
* Apply quantization to reduce model size further
* Test on real edge hardware instead of simulation

## Conclusion

This assignment helped me understand how AI models move from development to deployment in real-world edge systems. I learned the importance of optimization, efficiency, and system integration when working with edge AI.
