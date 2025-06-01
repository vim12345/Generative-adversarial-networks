# Generative-adversarial-networks

# Description:
**Generative Adversarial Networks (GANs)** consist of two neural networks: a generator and a discriminator, which compete against each other. The generator creates fake data (e.g., images), and the discriminator tries to distinguish between real and fake data. The goal is for the generator to create realistic data that the discriminator cannot easily distinguish from real data.

GANs are used for tasks like image generation, style transfer, and super-resolution.

In this project, we’ll implement a basic GAN to generate images from random noise and train it using the MNIST dataset.

# ✅ What It Does:
* Defines Generator and Discriminator models as part of the GAN architecture

* Trains the discriminator to distinguish between real and fake images and the generator to create convincing fake images

* Uses binary cross-entropy loss for both the generator and discriminator

* Trains on the MNIST dataset, generating new images similar to handwritten digits
