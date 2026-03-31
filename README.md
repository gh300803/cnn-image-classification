# CNN vs Classical Methods for Image Classification

This project compares a Convolutional Neural Network (CNN) with classical computer vision methods for image classification on the CIFAR-10 dataset.

## Approach

- Implemented a CNN using PyTorch
- Applied data augmentation to improve generalisation
- Built a classical pipeline using ORB features, Bag of Visual Words, and k-NN

## Results

- CNN achieved ~77% test accuracy
- Classical method achieved ~11.6% accuracy

## Key Insights

- Deep learning significantly outperformed classical approaches
- Data augmentation improved model generalisation
- Classical methods struggled with complex image representations

## Technologies

- Python
- PyTorch

## How to Run

- Install required libraries (PyTorch, OpenCV, scikit-learn)
- Run the notebooks:
  - cnn_cifar10_exploration.ipynb
  - classical_cv_bovw_cifar.ipynb
- OpenCV
- scikit-learn
