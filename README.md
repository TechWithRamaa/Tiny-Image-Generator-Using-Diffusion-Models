# Tiny Image Generator Using Diffusion Models

This repository contains a project for building a tiny image generator based on Diffusion Models, focusing on enhancing the generation process while incorporating user prompts or context.

## Overview

The project implements a U-Net architecture for image denoising within the context of Diffusion Models using PyTorch. It integrates context features and time embeddings to enhance image generation, effectively learning temporal and contextual dependencies. The model consists of:

- An initial convolutional layer
- A down-sampling path
- Embedding layers for time and context
- An up-sampling path
- A final output layer

The diffusion process utilizes a constructed noise schedule, and the sampling function iteratively refines images while visualizing the denoising progression. Overall, this implementation serves as a powerful tool for generative modeling tasks in computer vision.

## Notebook

The primary implementation is found in the following Jupyter Notebook:

- [Diffusion Model U-Net](https://github.com/TechWithRamaa/Tiny-Image-Generator-Using-Diffusion-Models/blob/main/Diffusion_model_UNet.ipynb)

## Features

- User prompt/context integration for personalized image generation
- Efficient image denoising with temporal and contextual learning
- Visualization of the denoising progression

## Requirements

To run this project, ensure you have the following libraries installed:

- `torch`
- `torchvision`
- `numpy`
- `matplotlib`
- `tqdm`
- Any other dependencies listed in the notebook

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/TechWithRamaa/Tiny-Image-Generator-Using-Diffusion-Models.git
   cd Tiny-Image-Generator-Using-Diffusion-Models
