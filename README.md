# Training a Street Situation Detection Model 

![img](https://images.unsplash.com/photo-1475998776787-d22fa84424b6?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1359&q=80)

This project deals with the problem of detecting street situation images (images which are taken on the outside). The used dataset for training the network, was self-created. In order to get a copy of the dataset, contact s0558366@htw-berlin.de

## Getting Started

```
git clone ...
pip install tensorflow
jupyter notebook
```



## Dataset

The used dataset is a collection of street situations. The positive examples for a street image, were randomly selected from following datasets:

- [BDD100K Dataset](https://bair.berkeley.edu/blog/2018/05/30/bdd/)
- [Mapillary Vistas Dataset](https://www.mapillary.com/dataset/vistas?pKey=q0GhQpk20wJm1ba1mfwJmw&lat=20&lng=0&z=1.5)
- [Cityscapes Dataset](https://www.cityscapes-dataset.com/)
- [KITTI-Dataset](http://www.cvlibs.net/datasets/kitti/)

The negative examples were randomly selected from the [ImageNet](http://image-net.org/) validation dataset. Overall there are 12.000 images, split into a into a `train` (10.000 images) and `validation` (2000) images dataset. In each dataset the percentage of positive and negative example is 50%.

The dataset can be found on Google Drive. Contact s0558366@htw-berlin.de for more informations 



## TODO

1. Train for a longer period of time

