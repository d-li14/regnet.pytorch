# RegNet Implementation with TorchVision Style
PyTorch implementation of [Designing Network Design Spaces](https://arxiv.org/abs/2003.13678) by Ilija Radosavovic, Raj Prateek Kosaraju, Ross Girshick, Kaiming He, and Piotr Dollár.

Compared to the [official codebase](https://github.com/facebookresearch/pycls), this repository follows the [torchvision's ResNeXt](https://github.com/pytorch/vision/blob/master/torchvision/models/resnet.py) style, which is expected to be more easily interpreted and utilized by pre-existing downstream applications.

# Pre-trained Models

| Model                                                        | Params (M) | GFLOPs | Top-1 acc (%) (our impl.) | Top-1 acc (%) (official) |
| ------------------------------------------------------------ | ---------- | ------ | ------------------------- | ------------------------ |
| [RegNetX-200M](https://hkustconnect-my.sharepoint.com/:u:/g/personal/dlibh_connect_ust_hk/EcDivRLCy7BHmVuoKVyqfZsB8t7OpFoCEdnLOD495UKWCw?e=r0h5fh) | 2.685      | 0.199  | 68.210                    | 68.9                     |
| [RegNetX-400M](https://hkustconnect-my.sharepoint.com/:u:/g/personal/dlibh_connect_ust_hk/EaL_0Di7OK5DsCLtvGcw418BqZGg5BD875kOIFMnALcMLQ?e=1mEB0v) | 5.158      | 0.398  | 72.278                    | 72.7                     |
| [RegNetX-600M](https://hkustconnect-my.sharepoint.com/:u:/g/personal/dlibh_connect_ust_hk/EcDivRLCy7BHmVuoKVyqfZsB8t7OpFoCEdnLOD495UKWCw?e=TBggeK) | 6.196      | 0.601  | 73.862                    | 74.1                     |
| [RegNetX-800M](https://hkustconnect-my.sharepoint.com/:u:/g/personal/dlibh_connect_ust_hk/Ecd7nKqHLnZCmlgitigejWIBYLhcpqkDCoBx_CEILtQcCg?e=8Xt961) | 7.260      | 0.800  | 74.940                    | 75.2                     |
| [RegNetX-1.6G](https://hkustconnect-my.sharepoint.com/:u:/g/personal/dlibh_connect_ust_hk/EXOeBD6xco5JmvLziY4zySEB1bR00A7DqCx9t4IbI_MAng?e=ZG5PxS) | 9.190      | 1.603  | 76.706                    | 77.0                     |
| [RegNetX-3.2G](https://hkustconnect-my.sharepoint.com/:u:/g/personal/dlibh_connect_ust_hk/EQ1o8qVNLuhBg21Kgf_bss8BHFrhm8PLI3xMrMtD7a192Q?e=RG2LoH) | 15.296     | 3.177  | 78.188                    | 78.3                     |
| [RegNetX-4.0G](https://hkustconnect-my.sharepoint.com/:u:/g/personal/dlibh_connect_ust_hk/ET7rz66druZGqPe-IFC21MQBd_kcLoYwXIoR9YQbJpGOqA?e=wfYSsA) | 22.118     | 3.965  | 78.690                    | 78.6                     |
| [RegNetX-6.4G](https://hkustconnect-my.sharepoint.com/:u:/g/personal/dlibh_connect_ust_hk/EQkGuWBHehlDnkr3cASqgS4Btul3Lb_iuO4IGHIeHrkWbA?e=ndLLQs) | 26.209     | 6.460  | 79.152                    | 79.2                     |
| [RgeNetX-8.0G](https://hkustconnect-my.sharepoint.com/:u:/g/personal/dlibh_connect_ust_hk/EYTpeCq4OnNIr9ly3KmokywBodWSZHHBNPhiwirhk9Urag?e=PDsrFu) | 39.573     | 7.995  | 79.380                    | 79.3                     |

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
