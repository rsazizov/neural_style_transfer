# Neural Style Transfer

This repo contains my implementation of the [original NST](https://arxiv.org/abs/1508.06576) algorithm :art:. The main idea of NST is using feature maps from a pre-trained CNN (VGG19 in my case) to define a loss function, which is then minimized with respect to a white noise image.

## Results

Style:

![The Starry Night](https://raw.githubusercontent.com/rsazizov/neural_style_transfer/master/data/starry_night.jpg)


Zurich:

![Zurich](https://raw.githubusercontent.com/rsazizov/neural_style_transfer/master/data/zurich.jpg)

The Starry Zurich:

![The Starry Zurich](https://raw.githubusercontent.com/rsazizov/neural_style_transfer/master/data/starry_zurich.png)

Baku:

![Baku](https://raw.githubusercontent.com/rsazizov/neural_style_transfer/master/data/baku.jpg)

The Starry Baku:

![The Starry Baku](https://raw.githubusercontent.com/rsazizov/neural_style_transfer/master/data/starry_baku.png)
