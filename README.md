♻️ EcoScan: AI-Powered Waste Classification System

Overview

EcoScan is an AI-powered waste classification system designed to identify different types of waste from images and promote sustainable waste management practices. The project leverages both Deep Learning and Machine Learning techniques to automatically classify waste into predefined categories and compare the performance of multiple state-of-the-art models.

⸻

👥 Team Members (Section B)

* Khadija
* Azeen Isha
* Urwa Ahmad
* Hibba Amir
* Eman Fatima

⸻

🎯 Project Objective

The primary objective of EcoScan is to automatically classify waste images into different categories using Artificial Intelligence and assist users in proper waste disposal. The project also evaluates and compares the performance of multiple AI models to identify the most effective approach for waste classification.

⸻

📊 Dataset

Unified Waste Classification Dataset

* Total Images: 64,000+
* Number of Classes: 8

Waste Categories

* Battery
* Glass
* Metal
* Organic Waste
* Paper/Cardboard
* Plastic
* Textiles
* Trash

Dataset Split

* Training Set: 44,800 Images (70%)
* Validation Set: 9,600 Images (15%)
* Test Set: 9,600 Images (15%)

⸻

🤖 Models Implemented

EfficientNet-B0

A lightweight and highly efficient convolutional neural network designed for image classification tasks with excellent accuracy-to-parameter ratio.

MobileNet

A deep learning model optimized for image classification and deployment on resource-constrained devices.

ResNet101

A deep residual neural network consisting of 101 layers that utilizes skip connections to overcome the vanishing gradient problem and achieve high classification accuracy.

Multi-Layer Perceptron (MLP)

A fully connected neural network architecture used as a baseline deep learning classifier.

YOLO (You Only Look Once)

A real-time object detection and classification model capable of identifying waste objects with high accuracy and speed.

⸻

📈 Model Performance

Model	Test Accuracy (%)

YOLO	99.40

EfficientNet-B0	98.56

MobileNet	98.05

ResNet101	96.76

MLP	51.51

🏆 Best Performing Model

YOLO — 99.40% Test Accuracy

YOLO achieved the highest performance among all evaluated models, demonstrating exceptional capability in real-time waste detection and classification.

⸻

⚙️ Project Workflow

1. Dataset Collection
2. Data Cleaning and Organization
3. Image Preprocessing
4. Data Augmentation
5. Model Training
6. Model Validation
7. Model Testing
8. Waste Classification
9. Performance Evaluation

⸻

🧠 Methodology

Image Preprocessing

* Image Resizing (224 × 224)
* Normalization
* Tensor Conversion

Data Augmentation

* Random Horizontal Flip
* Random Rotation
* Color Jitter

Training Configuration

* Framework: PyTorch
* Optimizer: AdamW
* Loss Function: CrossEntropy Loss
* Learning Rate Scheduler: ReduceLROnPlateau
* Hardware: NVIDIA Tesla T4 GPU
* Development Environment: Google Colab

⸻

📸 Results

The project includes:

* Accuracy Comparison Graphs
* Confusion Matrices
* Classification Reports
* Validation Accuracy Curves
* Prediction Test Results
* Model Comparison Analysis

⸻

🛠 Technologies Used

* Python
* PyTorch
* Torchvision
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Google Colab
* OpenCV

⸻

🌱 Future Work

* Develop a complete mobile application for real-time classification.
* Integrate camera-based waste detection.
* Add waste disposal recommendations for each category.
* Expand the dataset with more real-world images.
* Deploy the system as a cloud-based service.
* Improve generalization for unseen waste objects.

⸻

✅ Conclusion

EcoScan demonstrates the effectiveness of Artificial Intelligence in automating waste classification and supporting sustainable waste management practices. Through the comparison of multiple Machine Learning and Deep Learning models, the project achieved highly accurate waste classification results, with YOLO achieving the highest test accuracy of 99.40%.

The system highlights the potential of AI-driven solutions in promoting environmental sustainability, reducing improper waste disposal, and enabling smarter waste management systems for the future
