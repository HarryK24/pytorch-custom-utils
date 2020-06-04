# pytorch-custom-utils

Custom utils for Pytorch.

## Usage

### Dependencies

- torch 1.4.0
- torchvision 0.5.0
- python 3.6
- matplotlib 2.2.2
- numpy 1.14.3
- seaborn 0.9.0
- sklearn
- plotly

### Installation

- `pip install torchhk` or
- `git clone https://github.com/Harry24k/pytorch-custom-utils`

```python
from torchhk import *
```

### Demos
* **rm(RecordManager)** ([code](https://github.com/Harry24k/pytorch-custom-utils/blob/master/demo/RecordManager.ipynb)): 
RecordManager will help you to watch records pretty during iterations. It also provides some useful functions such as summary, plot, etc.

* **datasets(Datasets)** ([code](https://github.com/Harry24k/pytorch-custom-utils/blob/master/demo/Datasets.ipynb), [markdown](https://github.com/Harry24k/pytorch-custom-utils/blob/master/docs/Datasets.md)): 
    > Supported Datasets: CIFAR10, CIFAR100, STL10, MNIST, FashionMNIST, SVHN, MNISTM, ImageNet, USPS

* **vis(Vis)** ([code](https://github.com/Harry24k/pytorch-custom-utils/blob/master/demo/Vis.ipynb), [markdown](https://github.com/Harry24k/pytorch-custom-utils/blob/master/docs/Vis.md)): 

* **transform(Transform)** ([code](https://github.com/Harry24k/pytorch-custom-utils/blob/master/demo/Transform.ipynb)): 
Transform will help you to construct a new model with certain layers changed.