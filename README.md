# U-Net guide for custom segmentation

This tutorial is an example of training of [U-Net](https://arxiv.org/abs/1505.04597) by Ronnenberger et al., 2015.  Initially, the notebook ran on Google Colab, but should be also possible to run it locally if you set the environment right.

This notebook shows the implementation, loading and pre-processing of medical data, and training on **your own custom dataset**. The custom dataset of retinal vessel images were obtained from [Kaggle](https://www.kaggle.com/datasets/zionfuo/drive2004/data).

To train U-Net we take the following steps:

* Implement the U-Net in PyTorch
* Load custom dataset, pre-rpocess it and visualise it
* Run U-Net training
* Run U-Net inference on test images

Feel free to modify the code according to your specific needs or explore further optimizations. Happy coding!
