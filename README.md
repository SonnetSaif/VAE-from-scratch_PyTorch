# Variational Autoencoder (VAE) Implementation

This repository contains an implementation of a Variational Autoencoder (VAE) based on the original paper [Auto-Encoding Variational Bayes by Diederik P. Kingma and Max Welling](https://arxiv.org/abs/1312.6114). The code is written in PyTorch and aims to generate realistic images using the VAE architecture.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Dataset](#dataset)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Citation](#citation)

## Introduction

The Variational Autoencoder (VAE) is a probabilistic generative model that learns a low-dimensional latent space representation of data. It combines deep learning with probabilistic inference, enabling the generation of new data samples that are similar to those in the training set.

This implementation closely follows the methodology outlined in the original "Auto-Encoding Variational Bayes" paper, though some minor changes have been made.
<!-- providing a solid foundation for understanding and experimenting with VAEs. -->

## Getting Started

### Prerequisites

- Python (>=3.6)
- PyTorch (>=1.7.1)
- Other dependencies can be installed using the provided `requirements.txt` file.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/SonnetSaif/VAE-from-scratch_PyTorch.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

### Usage
- Just simply execute the **VAE_PyTorch.ipynb** cell by cell in Google Colab/Jupyter Notebook


## Dataset

This project utilizes the MNIST dataset, a widely used benchmark dataset for handwritten digit recognition. MNIST contains a training set of 60,000 grayscale images of handwritten digits (0 through 9) and a test set of 10,000 images. Each image is 28x28 pixels.

### Source

- The dataset is available directly through the torchvision library in PyTorch
- Also, available at [huggingface](https://huggingface.co/datasets/mnist)


## Results


## Contributing
If you'd like to contribute or have any suggestions to this project, feel free to open an issue or create a pull request. Contributions are welcome!


## License
- This project is licensed under the MIT License.


## Citation
If you use this code in your research, please cite the original GAN paper:
```bash
@article{kingma2013auto,
  title={Auto-encoding variational bayes},
  author={Kingma, Diederik P and Welling, Max},
  journal={arXiv preprint arXiv:1312.6114},
  year={2013}
}
```
