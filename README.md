# GAN.pth
a pytorch gan framework


# Features
* As GAN develop so quickly, keeping up to date matters
* Providing GAN specific features as possible i.e modular,but keep Flexible as possible
  - AdaIn, Spectral normalization, skip connections, resnets
  - Out-of-box Models
  - Trainer:train_generator, train_discriminator
  - GAN Loss
  - Metrics
  - Demo
  
* Documentation
* Production oriented, Research Friendly
  - distributed training(multiple gpus and multiple machines)
  - easy to deploy on production(performance optimized for mobile platform and server side)
* Custom Datasets & Pretrained Models provided in GANHub
* Easy to extension For Example 
  - do config through args file for each model
  - train_gene
  - well structured code(object oriented programming)
* well tested, as close as possible to official sota effect

Inspired by following frameworks

[torchgan](https://torchgan.readthedocs.io/en/latest/)

[PytorchGANZoo](https://github.com/facebookresearch/pytorch_GAN_zoo)

[PyTorch-GAN](https://github.com/eriklindernoren/PyTorch-GAN)

StarGAN_v2-Tensorflow

# Classical Models
StyleGAN/StyleGAN2

StarGAN/StarGAN2

FUNIT

# Components

## Discriminator
progressive growing (pggan)
self-attention


## Generator
style-based generator(stylegan)



# GAN Loss
Non-Saturating Loss + R1/R2
WGAN+GP


# Metrics 
IS(Inception Score)
FID(Inception Distance)
LPIPS
PPL

# Datasets
face aligner


# Utils
video interpolation
reporter: tensorboard reporter



# Demos
use GAN.pth framework to develop following apps as demos


## Demo GANS
* Vanilla GAN
* DCGAN

## Faceswap

## AI Stylist


## AI Portraits

Please access [GANHub]https://github.com/habout632/GANHub) for more demos, datasets, pretrained networks.


[Documentation](https://ganpth.readthedocs.io/en/latest/)
built with readthedocs
