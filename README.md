# 3D ResNeXt: Adapting ResNeXt to the 3D Case

This repository contains code and resources for adapting the ResNeXt architecture to the 3D case. 

## Table of Contents
- [Motivation](#motivation)
- [Model Architecture](#model-architecture)
- [Usage](#usage)
- [Citation](#citation)

## Motivation

3D data is prevalent in various domains, such as medical imaging, computer vision, and more. 
Adapting convolutional neural networks (CNNs) to handle 3D data effectively is crucial. 
This repository aims to provide a 3D adaptation of the ResNeXt architecture to address this need.

## Model Architecture

The 3D ResNeXt architecture is based on the original ResNeXt but tailored to process 3D volumes. 
It leverages the concept of cardinality and group convolutions to enhance the model's representational power.

For detailed information about the architecture, please refer to the original paper [Aggregated Residual Transformations for Deep Neural Networks](https://arxiv.org/pdf/1611.05431.pdf).
## Usage

1. **Installation**: Clone this repository and install the required dependencies.

```bash
git clone https://github.com/yourusername/3D-ResNeXt.git
cd 3D-ResNeXt
```
Then you can use the 3D-ResNeXt model for your projetcs.

```bash
@article{resnext-paper,
  title={Aggregated Residual Transformations for Deep Neural Networks},
  author={Saining Xie, Ross Girshick, Piotr Dollár, Zhuowen Tu and Kaiming He},
  year={2017},
}
```
