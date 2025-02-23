# AI Art Detection

This project aims to distinguish between human-created and AI-generated artworks using various methods.

## Features

- **Fast Fourier Transform (FFT)** for frequency-based feature extraction.
- **Vision Transformer (ViT)** for deep learning-based classification.
- **ResNet-50** for image recognition and feature analysis.
- **Human Study** to evaluate human ability to detect AI-generated art.

## Installation

```bash
git clone https://github.com/sepidehfat/AI-Art-Detection.git
cd AI-Art-Detection
pip install -r requirements.txt
```

## Dataset

We use the **AI-ArtBench dataset**, which includes:
- **Human-created artworks** from the ArtBench dataset.
- **AI-generated artworks** from latent and standard diffusion models.

## Results

- **ViT Model:** Achieved **99% accuracy** in distinguishing AI vs. human art.
- **ResNet-50:** Achieved **96% accuracy** with focused feature analysis.
- **FFT + Machine Learning Models:** XGBoost performed best among traditional classifiers.
- **
