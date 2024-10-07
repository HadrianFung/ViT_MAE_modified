# ViTMAE: Masked Autoencoder with Vision Transformer Backbone

## Overview

ViTMAE is a Python implementation of a Masked Autoencoder that utilizes a Vision Transformer (ViT) architecture. This model is designed for image processing tasks, enabling efficient representation learning through the use of transformer-based techniques.

## Features

- **Patch Embedding**: Converts images into patches for processing. [Allow rectangular patches and images for arbitrary input size]
- **Masked Autoencoding**: Randomly masks parts of the input to learn robust representations.
- **Transformer Blocks**: Utilizes multi-head self-attention and feed-forward networks for encoding.
- **Decoder**: Reconstructs the original image from the encoded representation.
