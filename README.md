# RegNet Implementation with TorchVision Style
PyTorch implementation of [Designing Network Design Spaces](https://arxiv.org/abs/2003.13678) by Ilija Radosavovic, Raj Prateek Kosaraju, Ross Girshick, Kaiming He, and Piotr Dollár.

Compared to the [official codebase](https://github.com/facebookresearch/pycls), this repo follows the [torchvision's ResNeXt](https://github.com/pytorch/vision/blob/master/torchvision/models/resnet.py) style, which is expected to be more easily interpredted and utilized by pre-existing downstream applications.

# Pre-trained Models

| Model                                                        | Params (M) | GFLOPs | Top-1 acc (%) (our impl.) | Top-1 acc (%) (official) |
| ------------------------------------------------------------ | ---------- | ------ | ------------------------- | ------------------------ |
| [RegNetX-200M](https://hkustconnect-my.sharepoint.com/:u:/g/personal/dlibh_connect_ust_hk/EcDivRLCy7BHmVuoKVyqfZsB8t7OpFoCEdnLOD495UKWCw?e=r0h5fh) | 2.685      | 0.199  | 68.210                    | 68.9                     |
| [RegNetX-400M](https://hkustconnect-my.sharepoint.com/:u:/g/personal/dlibh_connect_ust_hk/EaL_0Di7OK5DsCLtvGcw418BqZGg5BD875kOIFMnALcMLQ?e=1mEB0v) | 5.158      | 0.398  | 72.278                    | 72.7                     |
| [RegNetX-600M](https://hkustconnect-my.sharepoint.com/:u:/g/personal/dlibh_connect_ust_hk/EcDivRLCy7BHmVuoKVyqfZsB8t7OpFoCEdnLOD495UKWCw?e=TBggeK) | 6.196      | 0.601  | 73.862                    | 74.1                     |
| [RegNetX-800M](https://hkustconnect-my.sharepoint.com/:u:/g/personal/dlibh_connect_ust_hk/Ecd7nKqHLnZCmlgitigejWIBYLhcpqkDCoBx_CEILtQcCg?e=8Xt961) | 7.260      | 0.800  | 74.940                    | 75.2                     |

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
