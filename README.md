<img width="550" height="250" src="https://github.com/thuml/Transfer-Learning-Library/blob/dev/TransLearn.png"/>

## Introduction

This is the development branch for *Trans-Learn*. 
Compared with the master version, we have added

- Regression DA （including Source Only, DD)
- Unsupervised DA (including MCC)
- Partial DA (DANN, PADA, IWAN)
- Open Set DA (DANN, OSBP)
- Segmentation DA (ADVENT, FDA, CycleGAN, Cycada)

We are planning to add
- Segmentation DA (Self-training methods)
- Keypoint Detection DA
- Finetune Library (ftlib)


*Trans-Learn* is a Transfer Learning library based on pure PyTorch with high performance and friendly API. 
Our code is pythonic, and the design is consistent with torchvision. You can easily develop new algorithms, or easily apply existing algorithms..

- Latest results for unsupervised DA can be found at [Unsupervised DA benchmark](https://github.com/thuml/Transfer-Learning-Library/blob/dev/docs/dalib/benchmarks/unsupervised_da.rst)
- Results for partial DA can be found at [Partial DA benchmark](https://github.com/thuml/Transfer-Learning-Library/blob/dev/docs/dalib/benchmarks/partial_da.rst)
- Results for open-set DA can be found at [Open-set DA benchmark](https://github.com/thuml/Transfer-Learning-Library/blob/dev/docs/dalib/benchmarks/open_set_da.rst)
- Results for regression DA can be found at [Regression DA benchmark](https://github.com/thuml/Transfer-Learning-Library/blob/dev/docs/dalib/benchmarks/regression_da.rst)
- Results for segmentation DA can be found at [Segmentation DA benchmark](https://github.com/thuml/Transfer-Learning-Library/blob/dev/docs/dalib/benchmarks/segmentation_da.rst)
- A new documentation can be found at [Documentation (please open in Firefox or Safari)](http://microhhh.com/). Note that this link is only for temporary use.

There might be many errors and changes in this branch. Please refer [master](https://github.com/thuml/Transfer-Learning-Library) for stable version. Also, any suggestions are welcome!
