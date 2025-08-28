# Malpractice-Detection-In-Exam

This project develops a computer vision-based model to detect malpractice during examinations. The dataset consists of images categorized into different classes, representing normal behavior and cheating behavior. A custom PyTorch pipeline is implemented for data loading, preprocessing, augmentation, and classification.


## Overview

This project focuses on building an automated system to detect malpractice during examinations using computer vision and deep learning. The model analyzes exam images and classifies them into categories such as normal behavior or suspicious behavior. By leveraging deep learning, the project aims to strengthen the integrity and fairness of online/offline exams.


## Dataset

* The dataset consists of images categorized into multiple classes (e.g., cheating vs. non-cheating).
* Organized into train, validation, and test sets.
* Custom PyTorch Dataset class is used for efficient loading and preprocessing.
  

## Methodology

* Data Preprocessing & Augmentation
  * Image resizing, normalization, and augmentation (random flips, rotations, etc.) for  better generalization.

* Model Architecture
  * Built with PyTorch CNN layers.
  * Includes convolutional, pooling, and fully connected layers for classification.

* Training
  * Implemented class balancing using class weights.
  *Optimized with Adam optimizer and cross-entropy loss.

* Evaluation
  *Metrics: Accuracy, Loss curves, and Confusion Matrix.
  *Tested on unseen data to ensure reliability.
  

## Results

* Achieved promising accuracy in detecting exam malpractice.
* Visualized training performance with accuracy/loss plots.
* Provides a foundation for developing a real-time surveillance system.

## Tech Stack

* Language: Python
* Libraries: PyTorch, Torchvision, NumPy, Matplotlib, scikit-learn, PIL
* Frameworks: Deep Learning (CNNs)
