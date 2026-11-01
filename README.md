# CIFAR-10 Image Classification Using CNN

## Project Overview

This project implements a Convolutional Neural Network (CNN) to classify images into 10 categories using the CIFAR-10 dataset. The model was developed with Python and TensorFlow/Keras and trained from scratch.

## Dataset

- Dataset: CIFAR-10
- Total images: 60,000
- Training images used: 45,000
- Validation images: 5,000
- Test images: 10,000
- Image dimensions: 32 × 32 × 3
- Number of classes: 10

Classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

Dataset source: https://www.cs.toronto.edu/~kriz/cifar.html

Dataset creators: Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton.

## Model Architecture

The improved CNN includes convolutional layers, batch normalization, max pooling, dropout, data augmentation (horizontal flipping, rotation, and translation), global average pooling, and a dense classification layer.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Model Performance

| Metric | Result |
|---|---:|
| Original CNN validation accuracy | 73.62% |
| Improved CNN validation accuracy | 81.22% |
| Improved CNN test accuracy | 80.48% |
| Improved CNN test loss | 0.5807 |

The test accuracy was measured on the separate 10,000-image CIFAR-10 test set.

## Results

Place generated evaluation plots in a `results/` directory:

- `results/accuracy_comparison.png`
- `results/loss_comparison.png`
- `results/confusion_matrix.png`

The project also generated a classification report.

## Hardware

- Processor: Intel Core i5-1235U
- RAM: 16 GB
- Graphics: Integrated Intel graphics
- Training device: CPU

## Running the Project

1. Install dependencies from `requirements.txt`.
2. Obtain CIFAR-10 from its official source and review the applicable dataset terms.
3. Open `CNN_Image_Classifier.ipynb` in Jupyter Notebook.
4. Run the notebook cells in order.

## Dataset and Attribution Notice

This project uses CIFAR-10 for educational and experimental purposes. The dataset and its original images are not owned by this project.

Consult the official dataset source and applicable terms before obtaining, using, or redistributing the dataset. This repository does not include the raw CIFAR-10 archive or extracted image files. Trained model weights are also not included.
