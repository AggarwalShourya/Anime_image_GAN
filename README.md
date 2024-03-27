# Anime_image_GAN
The aim of this project is to automatically generate anime faces by just providing a input noise vector.I have used WassersteinGAN for the following project, also in the other half of this project I have to build one CNN also which can extract the features/latent representation of the image and which in turn can be passed into the trained Generator model thereby working like an autoencoder and thereby exploiting the latent space of GANs.


Official research paper of the WassersteinGAN. https://arxiv.org/abs/1701.07875

# Prerequisites
* Computer with Linux or OSX
* PyTorch
* For training, an NVIDIA GPU is strongly recommended for speed. CPU is supported but - training is very slow.
