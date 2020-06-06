# RegNet Implementation with TorchVision Style
PyTorch implementation of [Designing Network Design Spaces](https://arxiv.org/abs/2003.13678) by Ilija Radosavovic, Raj Prateek Kosaraju, Ross Girshick, Kaiming He, and Piotr Dollár.

Compared to the [official codebase](https://github.com/facebookresearch/pycls), this repo follows the [torchvision's ResNeXt](https://github.com/pytorch/vision/blob/master/torchvision/models/resnet.py) style, which is expected to be more easily interpredted and utilized by pre-existing downstream applications.

We have a plan to provide pre-trained models on ImageNet.

# Citation
```bibtex
@InProceedings{Radosavovic_2020_CVPR,
author = {Radosavovic, Ilija and Kosaraju, Raj Prateek and Girshick, Ross and He, Kaiming and Doll{\'a}r, Piotr},
title = {Designing Network Design Spaces},
booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
month = {June},
year = {2020}
}
```
