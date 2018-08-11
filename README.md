# Test-CTPN
This repo serves as a record of the prcess that I took to test the model illustrated in this paper (https://arxiv.org/abs/1609.03605) and implemented in this repo (https://github.com/YCG09/chinese-ocr/tree/master/ctpn)

## Environment

Training environment was set up in a Gcloud Compute Engine with following sepcs:

+ Ubuntu 16.04
+ Nvidia Tesla P-100, 16 GB memory
+ 64 GB persistent storage
+ 8 CPU cores with 16 GB memory
+ CUDA 8.0
+ CUDNN 6.0
+ Python 3.4
+ Tensorflow 1.3

## General Results
### Pretrained Model
<img src="results_1/img_4844.jpg" width=320 height=240 /><img src="data/oriented_results/002.jpg" width=320 height=240 />
<img src="results_1/img_5319.jpg" width=320 height=240 /><img src="data/oriented_results/004.jpg" width=320 height=240 />
<img src="results_1/img_5975.jpg" width=320 height=480 /><img src="data/oriented_results/010.png" width=320 height=320 />
<img src="results_1/img_6936.jpg" width=320 height=480 /><img src="data/oriented_results/010.png" width=320 height=320 />
### Manually trained Model
Model is trained using dataset dowloaed from following link(https://drive.google.com/drive/folders/0B_WmJoEtfQhDRl82b1dJTjB2ZGc), and hyperperameters are set according to this file(text.yml)

![alt text](https://github.com/Yiming992/Test-CTPN/blob/master/Screenshot from 2018-08-11 01-07-41.png)
<img src="results_2/img_4844.jpg" width=320 height=240 /><img src="data/oriented_results/002.jpg" width=320 height=240 />
<img src="results_2/img_5319.jpg" width=320 height=240 /><img src="data/oriented_results/004.jpg" width=320 height=240 />
<img src="results_2/img_5975.jpg" width=320 height=480 /><img src="data/oriented_results/010.png" width=320 height=320 />
<img src="results_2/img_6936.jpg" width=320 height=480 /><img src="data/oriented_results/010.png" width=320 height=320 />
