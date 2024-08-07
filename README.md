# CIFAR-10-Image-Generation

This project implements a Generative Adversarial Network (GAN) in Python using PyTorch and Torchvision to generate realistic images from the CIFAR-10 dataset. The code focuses on improving both the generator and discriminator network architectures and experimenting with various optimization strategies and hyperparameter tuning to enhance training stability and image quality.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Generative Adversarial Networks (GANs) are a class of machine learning frameworks designed by Ian Goodfellow and his colleagues in 2014. This project aims to generate realistic images from the CIFAR-10 dataset using a GAN model implemented in PyTorch.

## Prerequisites
- Python 3.x
- PyTorch
- Torchvision
- Matplotlib
- NumPy

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/cifar10-gan.git
    cd cifar10-gan
    ```
2. Install the required libraries:
    ```bash
    pip install torch torchvision matplotlib numpy
    ```

## Usage
1. Run the training script:
    ```bash
    python train.py
    ```
2. The training script will:
    - Load the CIFAR-10 dataset
    - Train the GAN model for the specified number of epochs
    - Display and save generated images at regular intervals

## Results
During training, the script will output generated images at the end of each epoch. Below are examples of training results:
- Final discriminator loss: 0.4473
- Final generator loss: 0.9555

Example of images generated by the model after training:

![Generated Images](results/generated_images.png)

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any bug fixes or enhancements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
