

## Package pre-requisites
The code runs on Python 2/3 and Pytorch 0.4 The following packages are required. 

```
pip install scipy tqdm matplotlib numpy opencv-python
```

## Dataset preparation

Download ImageNet pretrained Resnet-101([Link](https://download.pytorch.org/models/resnet101-5d3b4d8f.pth)) and place it ```./pretrained_models/```


```
python2 train_multi_split_entropy_landsat8_adapt_zy3_layer34.py    
```

### Validation 
```
python evaluate_multi_split_zy3_layer34.py 
```


## Acknowledgement

Parts of the code have been adapted from: 
[DeepLab-Resnet-Pytorch](https://github.com/speedinghzl/Pytorch-Deeplab), [AdvSemiSeg](https://github.com/hfslyc/AdvSemiSeg), [PyTorch-Encoding](https://github.com/zhanghang1989/PyTorch-Encoding)


## Citation

```
@ARTICLE{9387459,  author={Guo, Jianhua and Yang, Jingyu and Yue, Huanjing and Li, Kun},  
journal={IEEE Transactions on Geoscience and Remote Sensing},   
title={Unsupervised Domain Adaptation for Cloud Detection Based on Grouped Features Alignment and Entropy Minimization},   
year={2021},  
volume={},  
number={},  
pages={1-13},  
doi={10.1109/TGRS.2021.3067513}}
```

