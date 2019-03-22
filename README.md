
[TOC]

# Dataset Summary
这里包含各种数据集的简要介绍以及例子，有的数据集已经给出了下载地址，有的数据集给出了该数据集的HomePage，基本上通过访问HomePage便能找到该数据集的下载地址。
## Classification

### Mnist
Minist数据集来自美国国家标准与技术研究所（National Institute of Standards and Technology, NIST）。包含

- [x] 共60000张手写数字图像
- [x] 训练集验证集50000张手写数字图像
- [x] 测试集10000张手写数字图像
- [x] 每张图像原始大小为(28, 28, 1)
- [x] 每张图像中包含一个手写的数字（0~9）  

##### Links
 - **HomePage:** [http://yann.lecun.com/exdb/mnist/](http://yann.lecun.com/exdb/mnist/ "Mnist Dataset HomePage")
 - **DownLoad:** 
	- [train-images-idx3-ubyte.gz](http://yann.lecun.com/exdb/mnist/train-images-idx3-ubyte.gz "train images")
	- [train-labels-idx1-ubyte.gz](http://yann.lecun.com/exdb/mnist/train-labels-idx1-ubyte.gz "train labels")
	- [t10k-images-idx3-ubyte.gz](http://yann.lecun.com/exdb/mnist/t10k-images-idx3-ubyte.gz "test images")
	- [t10k-labels-idx1-ubyte.gz](http://yann.lecun.com/exdb/mnist/t10k-labels-idx1-ubyte.gz "test labels")


### ImageNet

##### Links
- **HomePage:** [http://image-net.org/index](http://image-net.org/index "ImageNet HomePage")
- **Download:**
	- [Original Source](http://image-net.org/download-images)

## Object Detection
### VOC

## Segmentation
### VOC2012
### Cityscapes
Cityscapes数据集是专注于城市街道交通场景语义理解的逐像素标记的数据集，也有部分图像具有实例分割标签，可用于做实例分割。
- [x] 50 different cities
- [x] 5000 high quality annotated frames, which include 2975 for train, 500 for evaluation and 1525 for test
- [x] 20000 weakly annotated frames

##### Examples


##### Links
- **HomePage:** [https://www.cityscapes-dataset.com](https://www.cityscapes-dataset.com/ "Cityscapes HomePage")
- **Download:**
	- [leftImg8bit_trainvaltest.zip (11GB)](https://www.cityscapes-dataset.com/file-handling/?packageID=3 "left 8-bit images - train, val, and test sets (5000 images)")
	- [gtFine_trainvaltest.zip (241MB)](https://www.cityscapes-dataset.com/file-handling/?packageID=1 "fine annotations for train and val set (3475 annotated images) and dummy annotations (ignore regions) for the test set (1525 images)")
	- [leftImg8bit_trainextra.zip (44GB)](https://www.cityscapes-dataset.com/file-handling/?packageID=4 "left 8-bit images - trainextra set (19998 images, note that the image troisdorf_000000_000073_leftImg8bit.png is corrupt/black)")
	- [gtCoarse.zip(1.3GB)](https://www.cityscapes-dataset.com/file-handling/?packageID=2 "coarse annotations for train and val set (3475 annotated images) and train_extra (19998 annotated images)")
	- [leftImg8bit_demoVideo.zip (6.6GB)](https://www.cityscapes-dataset.com/file-handling/?packageID=12 "video sequences for qualitative evaluation, left 8-bit images only")
	- [leftImg8bit_blurred.zip (11GB)](https://www.cityscapes-dataset.com/file-handling/?packageID=32 "Left 8-bit images with blurred faces and license plates. Please compute results on the original images but use the blurred ones for visualization. We thank Mapillary for blurring the images.")
	- [gtBox_cityPersons_trainval.zip (2.2MB)](https://www.cityscapes-dataset.com/file-handling/?packageID=28 "CityPersons bounding box annotations of people for train and val sets (3475 annotated images). Citation: S. Zhang, R. Benenson, and B. Schiele, CityPersons: A Diverse Dataset for Pedestrian Detection, CVPR ")

- **Benchmark Suite:** [https://www.cityscapes-dataset.com/benchmarks](https://www.cityscapes-dataset.com/benchmarks/)

- **CityscapesCcripts:** [https://github.com/mcordts/cityscapesScripts](https://github.com/mcordts/cityscapesScripts "README and scripts for the Cityscapes Dataset")


### Apollo
### COCO

## OCR
### CTW
CTW data(Chinese Text in the Wild)，该数据集由清华大学和腾讯共同推出, 包含
- [x] 32285 high resolution images
- [x] 1018402 character instances
- [x] 3850 character categories
- [x] 6 kinds of attributes

##### Example
##### Links


 - **HomePage:** [https://ctwdataset.github.io/](https://ctwdataset.github.io/ "HomePage")
 - **GitHub:** [https://github.com/yuantailing/ctw-baseline](https://github.com/yuantailing/ctw-baseline "GitHub source")
 - **Laboratory:** [http://cg.cs.tsinghua.edu.cn/](http://cg.cs.tsinghua.edu.cn/ "Laboratory")

## Instance Segmentation

