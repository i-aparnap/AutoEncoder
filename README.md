# AutoEncoder
# MNIST Handwritten Digit Autoencoder
## Overview

This project builds and trains a basic autoencoder using the MNIST dataset of handwritten digits. The autoencoder compresses 28×28 grayscale images into a smaller latent representation (encoder) and reconstructs the images back from this latent space (decoder). The goal is to learn efficient image representations and evaluate reconstruction quality.

## Dataset

MNIST Dataset (handwritten digits 0–9)

Training images: 60,000

Test images: 10,000

Image size: 28×28 pixels, grayscale

Pixel values normalized to range [0, 1] for faster training

## Autoencoder Architecture

Encoder: Compresses input images into a lower-dimensional latent space

Decoder: Reconstructs original images from latent representation

Activation functions: ReLU for hidden layers, Sigmoid for output layer

Loss function: Mean Squared Error (MSE)

Optimizer: Adam

## Training

Trained on MNIST training dataset

Validation performed on test set

Training monitored with loss curves

Early stopping optional to prevent overfitting

## Evaluation & Visualization

Model summary displayed clearly

Training vs validation loss curves plotted to monitor convergence

Reconstructed images compared side-by-side with original images to assess quality

## Results

Autoencoder successfully learned to reconstruct MNIST digits

Reconstructed images closely resemble original digits, with minor blurring due to compression

Loss curves show smooth convergence, indicating stable training

## How to Run

Open AutoEncoder.ipynb in Jupyter Notebook or Colab

Execute sequentially: load data → preprocess → build model → train → evaluate → visualize results

## Deliverables

Model summary of autoencoder

Training vs validation loss curves

Side-by-side comparison of original vs reconstructed images

Short explanation of results

## Dependencies

Python 3.8+

TensorFlow / Keras

NumPy

Matplotlib

## Author

Aparna P
