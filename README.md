# GAN_VAE_dl
GAN and VAE coursework at Imperial. See ```dl_cw2_2023.ipynb``` for code, detailed working process, and theoretical explanation.

# In this project
I developed two types of Generative Model: variational autoencoder (VAE) and generative adversarial network (GAN) based on the MNIST and CIFAR-10 datasets respectively.

For variational autoencoder (VAE): 
- I developed a VAE from scartch to learn the latent embeddings of the MNIST digits.
- I defined a $\beta$ loss function for VAE and discussed its theoretical intuition.
- I visualised the learnt embeddings with t-SNE plots.

For generative adversarial network (GAN):
- I developed a Deep Convolutional Generative Adversarial Network (DCGAN) from scartch and trained it on the CIFAR-10 dataset.
- I experimented with different model architectures, activation functions, and hyperparameters to achieve decent image generation results.
- I discussed tricks to avoid common issues of training a GAN, eg mode collapse.
