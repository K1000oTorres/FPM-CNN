They present a method that models the Fourier Ptychograph forward process using a CNN and recovers the complex object information in the network training process. In the proposed approach, the network’s input is the Point Spread Function (PSF) in the spatial domain. The object is treated as 2D learnable weights of a convolution layer. The output of the network is modeled as the loss function that is intended to be minimized.


## BiBTeX

```
@article{Jiang:18,
author = {Shaowei Jiang and Kaikai Guo and Jun Liao and Guoan Zheng},
journal = {Biomed. Opt. Express},
keywords = {Microscopy; Image reconstruction techniques; Pattern recognition, neural networks ; Imaging systems; Machine learning; Neural networks; Phase retrieval; Single pixel imaging; Structured illumination microscopy},
number = {7},
pages = {3306--3319},
publisher = {Optica Publishing Group},
title = {Solving Fourier ptychographic imaging problems via neural network modeling and TensorFlow},
volume = {9},
month = {Jul},
year = {2018},
url = {https://opg.optica.org/boe/abstract.cfm?URI=boe-9-7-3306},
doi = {10.1364/BOE.9.003306},
abstract = {Fourier ptychography is a recently developed imaging approach for large field-of-view and high-resolution microscopy. Here we model the Fourier ptychographic forward imaging process using a convolutional neural network (CNN) and recover the complex object information in a network training process. In this approach, the input of the network is the point spread function in the spatial domain or the coherent transfer function in the Fourier domain. The object is treated as 2D learnable weights of a convolutional or a multiplication layer. The output of the network is modeled as the loss function we aim to minimize. The batch size of the network corresponds to the number of captured low-resolution images in one forward/backward pass. We use a popular open-source machine learning library, TensorFlow, for setting up the network and conducting the optimization process. We analyze the performance of different learning rates, different solvers, and different batch sizes. It is shown that a large batch size with the Adam optimizer achieves the best performance in general. To accelerate the phase retrieval process, we also discuss a strategy to implement Fourier-magnitude projection using a multiplication neural network model. Since convolution and multiplication are the two most-common operations in imaging modeling, the reported approach may provide a new perspective to examine many coherent and incoherent systems. As a demonstration, we discuss the extensions of the reported networks for modeling single-pixel imaging and structured illumination microscopy (SIM). 4-frame resolution doubling is demonstrated using a neural network for SIM. The link between imaging systems and neural network modeling may enable the use of machine-learning hardware such as neural engine and tensor processing unit for accelerating the image reconstruction process. We have made our implementation code open-source for researchers.},
}
}
```
