# Repository for the paper 'Lidar-Camera Co-Training for Semi-Supervised Road Detection'  
### Important links:
* Link to paper preprint: 
* Link to youtube playlist with comparison videos: [click here](https://www.youtube.com/playlist?list=PLKaUu00MYU2j06UY99kMS7FOEdjesKYJ_)
* Link to KITTI road benchmark and data set: http://www.cvlibs.net/datasets/kitti/eval_road.php
* Link to KITTI raw data set: http://www.cvlibs.net/datasets/kitti/raw_data.php

### Info about the CNNs:
* Code for the U-Net implementation used in this work:  https://github.com/jvanvugt/pytorch-unet
* The FCN-Resnet50 is implemented in torchvision: https://pytorch.org/docs/master/torchvision/models.html#semantic-segmentation 

### Data set splits:
In the folder sets, you can find the 20 data set splits used for generating the results reported in the paper.

### Code for generating data sets and training:
I will upload the code for generating the data sets and for training the networks once we have completed the work
on a follow-up paper. If you are a researcher and you would like to access the code before it is publicly available
in order to reproduce our results, please send me an email.


### Citation:
Preprint citation of the paper:
```
@article{CaltagironeEtAl2019,
  title={Lidar-Camera Co-Training for Semi-Supervised Road Detection},
  author={Caltagirone, Luca and Lennart, Svensson and Wahde, Mattias and Sanfridson, Martin},
  journal={arXiv preprint arXiv:},
  year={2019}
}
