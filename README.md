# ViT-Convolutions
My final project for TTIC 31230, Fundamentals of Deep Learning. Incorporating Convolutions into Vision Transformers

Based off of the [Vision Transformer paper](https://arxiv.org/abs/2010.11929)

My project's extension was to incorporate Convolutions into the Vision Transformer, which famously is a faithful implementation of the Transformer and Attention architectures applied towards Computer Vision, and thus does not use
convolutions. Despite convolutional networks being the dominant standard in the field of Vision, the Vision Transformer was a successful challenge to that philosophy, yet suffers from substandard performance on smaller to medium sized datasets. Thus, my project is aimed at incorporating convolutions in some way while maintaining the Vision Transformer architecture as best I can, at the aim of examining its effects on performance and computation on smaller datasets, with little training time. My architectures were run on CIFAR-10, with only 25 epochs of training.

With influence and inspiration taken from [these](https://arxiv.org/abs/2103.15808) [papers](https://arxiv.org/abs/2103.11816).
