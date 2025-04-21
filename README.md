# Monet CycleGAN - Using GANs to create art
## Problem Description

Artists are often recognized by their distinctive styles—through unique color palettes, brushwork, and composition. Emulating such artistic expression has long been considered the domain of human creativity, but recent advancements in computer vision and deep learning have made it possible to mimic these visual styles algorithmically. In particular, Generative Adversarial Networks (GANs) have emerged as powerful tools capable of generating images that closely resemble real-world objects—and even artistic masterpieces.

This challenge explores whether data science can convincingly replicate the nuanced style of Claude Monet. The task is to build a GAN that can generate thousands of images in the impressionist style of Monet, such that even a trained classifier may be "fooled" into believing the generated images are authentic. The GAN architecture consists of two competing neural networks: a generator, which learns to create Monet-style images, and a discriminator, which learns to distinguish real Monet paintings from generated ones. These networks train in opposition, improving each other through this adversarial process.

The specific goal is to train a GAN to produce between 7,000 to 10,000 Monet-style images that reflect the visual characteristics of Monet's artwork. Success will depend on how well your generator can capture the artist’s aesthetic, and how effectively your model can fool the discriminator into believing its creations are real.
