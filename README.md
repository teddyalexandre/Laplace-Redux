# Laplace Redux – Effortless Bayesian Deep Learning

Welcome to the our repository for the paper "Laplace Redux – Effortless Bayesian Deep Learning" written by Erik Daxberger, Agustinus Kristiadi, Alexander Immer, Runa Eschenhagen, Matthias Bauer, and Philipp Hennig. This paper presents a novel approach to streamline the construction of Bayesian Neural Networks (BNNs) through the use of Laplace approximation, making Bayesian deep learning more accessible and efficient.

## Overview

The paper introduces a method that simplifies the deployment of BNNs by leveraging Laplace approximation, addressing common challenges in Bayesian deep learning such as computational efficiency and the complexity of implementation. Our work is aimed at both advancing the theoretical understanding of BNNs and providing practical tools for researchers and practitioners in the field.

## Experiments

Our investigation is documented in two comprehensive Jupyter notebooks, detailing the experiments conducted to validate the proposed approaches:

1. **Training Performance Evaluation**: In `LeNet.ipynb` we assess the training performance of a Convolutional Neural Network (CNN) using the online marginal likelihood training. This series of experiments focuses on comparing the efficiency and effectiveness of online Laplace and potential of its acceleration with Nvidia CUDA.

2. **Uncertainty Quantification in Image Classification**: In `CIFAR10_LA.ipynb` we delve into an image classification task to examine how uncertainty quantification can be improved using the Laplace approximation, especially in scenarios with additive noise. The experiments highlight the robustness and reliability of the proposed method in handling uncertainty.

## Getting Started

To get started with replicating our experiments or exploring the Laplace Redux approach:

1. Clone this repository to your local machine using `git clone`.
2. Ensure you have Jupyter Notebook or JupyterLab installed to run the notebooks.
3. Install the packages listed in the requirements.txt file.
4. Navigate to the notebooks directory and launch Jupyter to open the provided notebooks.


*Teddy ALEXANDRE, Samy HOCINE, Ivan SVATKO, MVA Master, 2023-2024*
