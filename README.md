# Wheat Leaf Disease Classification Enhancement with CycleGAN Synthetic Image Generation

## Overview

This GitHub repository presents an innovative approach to enhancing the classification of wheat leaf diseases by leveraging CycleGAN for synthetic image generation. Traditional machine learning models often struggle to generalize effectively with limited datasets. However, by employing CycleGAN, we can generate diverse synthetic images even with limited dataset, augmenting the dataset and improving the robustness of disease classification models.

## Dataset

The dataset used for training can be found [here](https://data.mendeley.com/datasets/wgd66f8n6h/1). 

## Key Features

### CycleGAN Implementation

The repository provides a comprehensive implementation of CycleGAN, a state-of-the-art generative adversarial network (GAN) architecture tailored for image-to-image translation tasks.

### Training Script

Users can access a detailed training script designed specifically for training the CycleGAN model on their dataset. The script includes parameter configurations and instructions for seamless training. For training stripe rust synthetic image generation, the healthy dataset should be placed in path_A and the stripe rust dataset in path_B in the code. Similarly, for training septoria synthetic image generation, the healthy dataset should be in path_A as it is, and the septoria dataset should be in path_B in the code.

### Image Generation

Upon successful training, the repository includes scripts to utilize the trained CycleGAN generator model to generate synthetic images. These images can be used to augment the original dataset, enhancing its diversity and size.

### Evaluation and Integration

Additionally, the repository offers guidance on evaluating the generated images and seamlessly integrating them into existing wheat leaf disease classification pipelines.

### Documentation and Examples

Detailed documentation and examples are provided to facilitate easy understanding and implementation of the CycleGAN-based image generation approach.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yeasintaha/Improving-Wheat-Leaf-Disease-Classification-CycleGAN-Synthetic-Image-Generation-with-Limited-Dataset.git

```

2. Follow the instructions in the documentation to train the CycleGAN model and generate synthetic images.

## Contribution

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.




