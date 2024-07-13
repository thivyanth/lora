# LoRA Implementation with PyTorch

This repository contains a PyTorch implementation of the Low-Rank Adaptation (LoRA) technique, which is designed to adapt large language models efficiently by introducing low-rank matrices. This method reduces the number of trainable parameters, allowing for quick adaptations without significant computational overhead.

## Overview

LoRA modifies the weights of a pre-trained model using low-rank matrices, significantly reducing the number of parameters that need to be trained for adaptation tasks. This implementation showcases the application of LoRA to a simple model on the MNIST dataset.

## Getting Started

### Prerequisites

Ensure you have Python and PyTorch installed. You can install the necessary Python packages using:

    pip install torch torchvision

### Installation

Clone this repository to your local machine to get started:

    git clone https://github.com/thivyanth/lora.git
    cd lora

## Usage

This repository contains two Jupyter notebooks:

- `lora.ipynb`: Demonstrates the implementation of the LoRA technique on a neural network for the MNIST digit classification task.
- `svd.ipynb`: Provides a tutorial on using Singular Value Decomposition (SVD) in PyTorch, which is essential for understanding part of the LoRA technique.

To run these notebooks, use:

    jupyter notebook lora.ipynb
    jupyter notebook svd.ipynb