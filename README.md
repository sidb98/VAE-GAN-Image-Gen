# Autoencoder and GAN Project

## Overview
This project focuses on implementing an autoencoder, variational autoencoder (VAE), and conditional GAN in PyTorch to learn latent representations of image data in an unsupervised manner. The models are trained and evaluated using the MNIST dataset.

### Autoencoder
- Implemented a basic autoencoder with convolutional encoder and decoder networks.
- Trained the model to reconstruct MNIST digits.
- Visualized reconstructions to evaluate model performance.

### Variational Autoencoder
- Extended the autoencoder to a VAE with the reparameterization trick.
- Implemented the KLD (Kullback-Leibler Divergence) loss term and tuned the beta hyperparameter.
- Analyzed latent space representations learned by the VAE.

### Conditional GAN
- Implemented a DCGAN (Deep Convolutional GAN) generator and discriminator model.
- Conditioned the generator on class labels to control digit generation.
- Used activation maximization to visualize learned representations.
