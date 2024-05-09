# Sketch-to-Image Generation with Conditional Generative Adversarial Network (cGAN)

## Introduction
The cGAN is conditioned on class labels to synthesize images that represent the characteristics associated with the provided label. The model is trained on unpaired sketches and generates images accordingly.Dataset used is ISIC dataset.

## Experiments
### Experiment 1: Training cGAN
- Implement a conditional GAN architecture conditioned on class labels to synthesize realistic images.

### Experiment 2: Evaluation
- Evaluate the generated images by considering them as test images.
- Report the accuracy of the generated images using a classifier trained on the original training data.
- Calculate Frechet Inception Distance (FID) and Inception Score (IS) to assess image quality, diversity, and realism.

## How to Use
1. Clone this repository.
2. Download the ISIC dataset and place it in the `data/` directory.
3. Run the `main.ipynb` to train the cGAN.
