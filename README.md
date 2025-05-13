# Advanced AI Course Project - GAN on MNIST

This repository contains the implementation of a Generative Adversarial Network (GAN) developed as part of the Advanced AI coursework.

## Project Overview

The goal of this project is to implement a GAN to generate handwritten digits similar to those found in the MNIST dataset. The GAN consists of:

- **Generator**: Learns to generate realistic-looking digit images.
- **Discriminator**: Learns to distinguish between real and fake digit images.
- **Training Loop**: Alternates between training the discriminator and the generator to improve performance.

## Files

- `gan_model.ipynb` – Main Jupyter notebook containing the GAN implementation, training process, and visualization of generated digits.
- `README.md` – This file, providing an overview of the project.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- MNIST Dataset

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
