🧠 Building a Brain using TensorFlow

This project demonstrates the fundamentals of building and training a neural network classifier from scratch using TensorFlow on the Fashion-MNIST dataset.

The goal of this project is to understand how neural networks learn, how images are processed as numerical data, and how model outputs can be interpreted using probabilities.

📌 Project Overview

Task: Multi-class image classification

Dataset: Fashion-MNIST (28×28 grayscale clothing images)

Framework: TensorFlow / Keras

Model Type: Artificial Neural Network (ANN)

This project focuses on conceptual clarity rather than model complexity.

🧠 Model Architecture

The neural network consists of:

Flatten Layer

Converts 28×28 images into a 1D vector (784 features)

Dense Output Layer

10 neurons (one per clothing category)

Softmax activation to output class probabilities

Input (28×28 image)
        ↓
Flatten (784 features)
        ↓
Dense (10 units, Softmax)
        ↓
Class Probabilities

⚙️ Training Details

Optimizer: Adam

Loss Function: Sparse Categorical Cross-Entropy

Metric: Accuracy

Epochs: 5

The model is trained on 60,000 images and validated on 10,000 unseen images.

📊 Model Interpretation

Instead of only checking accuracy, this project emphasizes model interpretability by:

Visualizing input images

Plotting Softmax probability distributions

Observing how confident the model is for each class

This helps understand how the model makes decisions, not just whether it is correct.

🧩 Key Learnings

Through this project, I gained hands-on understanding of:

How neural networks process images as numerical inputs

Difference between logits and probabilities

Importance of Softmax in multi-class classification

Role of loss functions and optimizers in learning

Basic workflow of training, validating, and evaluating models

🚀 Future Improvements

Planned extensions for this project:

Add hidden layers for deeper learning

Upgrade to Convolutional Neural Networks (CNNs)

Re-implement the model using PyTorch

Compare ANN vs CNN performance

📂 Repository Structure
Building-a-Brain/
│
├── notebook.ipynb        # Model implementation and visualization
├── README.md             # Project documentation

🛠️ Technologies Used

Python

TensorFlow / Keras

NumPy

Matplotlib

👤 Author

Aadhidharmar T
B.Tech – Artificial Intelligence & Data Science

🔗 GitHub: https://github.com/Aadhidharmar001

🔗 LinkedIn: https://www.linkedin.com/in/aadhi-dharmar-a35679293

⭐ Acknowledgements

Fashion-MNIST dataset by Zalando Research

TensorFlow & Keras documentation
