# Generative Adversarial Network for Image Generation

## Overview

This repository contains an implementation of an advanced Generative Adversarial Network (GAN) designed to generate high-quality images based on the CelebA dataset. The project outputs two `.pkl` files representing the trained Generator and Critic models.

## Table of Contents
- [Introduction](#introduction)
- [Usage](#usage)
- [Training](#training)
- [Results](#results)
- [Model Checkpoints](#model-checkpoints)

## Introduction

Generative Adversarial Networks (GANs) have shown remarkable ability in generating realistic images. This project uses an advanced GAN architecture to generate images based on the CelebA dataset, which is a large-scale face attributes dataset with more than 200,000 celebrity images.

## Features

- **Advanced GAN Architecture**: Utilizes a state-of-the-art GAN architecture to generate high-quality images.
- **CelebA Dataset**: Leverages the extensive CelebA dataset for training.
- **Model Checkpoints**: Save and load trained models for reuse and further training.

### Clone the Repository

```bash
git clone https://github.com/Nouri-bit/Advanced-GAN.git
cd your-repository
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Usage


### Training

To train the GAN, run the following command:

```bash
python train.py --data_path ./data --output_path ./output
```

### Model Checkpoints

The trained Generator and Critic models will be saved as `.pkl` files in the `output` directory.

