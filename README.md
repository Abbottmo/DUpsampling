# DUpsampling
This repo is an unofficial pytorch implementation of CVPR19 paper: Decoders Matter for Semantic Segmentation: Data-Dependent Decoding Enables Flexible Feature Aggregation: https://arxiv.org/abs/1903.02120

### Installation

* pytorch==0.4.1
* python==3.5
* numpy
* torchvision
* matplotlib
* opencv-python
* dominate
* random
* collections
* shutil

### Dataset and pretrained model

Plesae download VOC12_aug dataset and unzip the dataset into `data` folder.

Please download MIT imagenet pretrained [resnet50-imagenet.pth](http://sceneparsing.csail.mit.edu/model/pretrained_resnet/resnet50-imagenet.pth), and put it into `checkpoints` folder.

Please modify your configuration in `options/base options.py`.

### Usage

```
bash train.sh
```

### Segmentation results on val set
![](/image/image.png)


### To do

* Add softmax with temperature
* Modify the network and improve the accuracy

under construction...

If you have any question, feel free to contact me or submit issue.


