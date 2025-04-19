# Neural-Networks
🧠 CIFAR-10 Image Classification with a Custom Convolutional Neural Network
Module: Neural Networks & Deep Learning (ECS659P/ECS7026P)
MSc Big Data Science | Queen Mary University of London

This project involved building and improving a Convolutional Neural Network (CNN) for image classification on the CIFAR-10 dataset, which contains 60,000 colour images (32x32 pixels) across 10 object categories.

🔧 Project Highlights:
Custom CNN Architecture:
Designed a deep CNN with 3 convolutional blocks, each containing 4 convolutional layers:

Block 1: 3 ➝ 64 channels

Block 2: 64 ➝ 128 channels

Block 3: 128 ➝ 256 channels
This structure significantly enhanced feature extraction and allowed the model to learn hierarchical patterns effectively.

Regularisation & Stability Enhancements:

Batch Normalisation after each convolutional layer

ReLU activation for non-linearity

Dropout (p=0.5) in fully connected layers to reduce overfitting

Adaptive Average-Max Pooling to reduce spatial dimensions and emphasise key features

Training Details:

Optimizer: Adam (learning rate = 0.01)

Loss Function: Cross-entropy (multi-class classification)

Batch Size: 64 (increased to 100 during training)

Epochs: 50

Achieved 85.39% test accuracy at epoch 44

Visualisation:
Tracked training/testing accuracy and loss over 50 epochs, showing consistent improvement and model convergence.

📌 Summary:
This project demonstrates practical experience in designing, training, and evaluating deep learning models for image recognition. Through architectural enhancements, parameter tuning, and visual tracking, I successfully surpassed an 85% accuracy threshold on CIFAR-10 — showcasing effective deep learning model development.

👉 Explore the full notebook, training logs, and architecture on GitHub:
