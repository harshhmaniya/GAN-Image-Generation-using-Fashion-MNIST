
# GAN-Image-Generation-using-Fashion-MNIST

This repository implements a Generative Adversarial Network (GAN) for generating images using the Fashion MNIST dataset. The project includes an interactive Jupyter Notebook along with pre-trained Keras models for both the generator and discriminator.

## Table of Contents
- [Overview](#overview)
- [Requirements](#requirements)
- [Step-by-Step Guide](#step-by-step-guide)
- [Generated Images](#generated-images)
- [License](#license)

## Overview
The core of this project is the Jupyter Notebook `GAN_on_Fashion_MNIST.ipynb`, which contains the interactive code to:
- Load the Fashion MNIST data.
- Initialize and train the GAN.
- Generate new images using the trained generator.

The repository also provides:
- `fashion_mnist_generator.keras` – the pre-trained generator model.
- `fashion_mnist_discriminator.keras` – the pre-trained discriminator model.
- A folder named **Generated Images** that stores sample outputs produced by the GAN.

## Requirements
- Python (ensure compatibility with Jupyter Notebook and Keras)
- Jupyter Notebook or Jupyter Lab

## Step-by-Step Guide

1. **Clone the Repository**  
   Open your terminal and clone the repository:
   ```bash
   git clone https://github.com/harshhmaniya/GAN-Image-Generation-using-Fashion-MNIST.git
   cd GAN-Image-Generation-using-Fashion-MNIST
   ```

2. **Launch the Jupyter Notebook**  
   Start Jupyter Notebook and open the notebook file:
   ```bash
   jupyter notebook GAN_on_Fashion_MNIST.ipynb
   ```
   This notebook contains all the interactive code necessary to work with the GAN.

3. **Run the Notebook Cells**  
   Execute each cell in sequence:
   - The notebook will load the Fashion MNIST dataset.
   - It will initialize and train the GAN model.
   - It will generate images using the generator model.
   
4. **View Generated Images**  
   Once the notebook completes, check the **Generated Images** folder in the repository to view the sample images produced by the GAN.

## Generated Images
The **Generated Images** folder contains outputs from the trained GAN. Explore these images to see the results of the image generation process.

## License
This project is licensed under the MIT License. Please see the [LICENSE](LICENSE) file for more details.
