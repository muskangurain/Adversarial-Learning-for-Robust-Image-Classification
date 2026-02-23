# Adversarial-Learning-for-Robust-Image-Classification
Implemented adversarial learning to strengthen CNN robustness against malicious perturbations. Generated adversarial samples using FGSM and PGD to assess vulnerability, then performed adversarial training with clean and perturbed data. The model showed improved resistance to attacks while maintaining overall accuracy.
# Overview

This project explores adversarial learning techniques to improve the robustness of deep learning models against adversarial attacks. A CNN classifier is trained on image data, attacked using FGSM and PGD methods, and then strengthened through adversarial training.

# Objectives

Understand adversarial attacks on neural networks

Generate adversarial examples (FGSM, PGD)

Evaluate model performance under attacks

Improve robustness using adversarial training

#  Methodology

Train a baseline CNN on the dataset

Generate adversarial samples using FGSM and PGD

Evaluate performance drop on attacked data

Retrain model with adversarial training

Compare accuracy and robustness

# Tech Stack

Python

TensorFlow / PyTorch

NumPy, Matplotlib

OpenCV

Jupyter Notebook

 #Results

Observed significant accuracy drop under attacks

Adversarial training improved robustness

Maintained competitive accuracy on clean data

# Future Work

Test on larger datasets (CIFAR-100, ImageNet subset)

Explore advanced defenses (defensive distillation, TRADES)

Deploy as a robustness evaluation toolkit
