---
title: "Camera-based vehicle velocity estimation from monocular video"
authors: '<b>Moritz Kampelmühler</b>, Michael Müller, Christoph Feichtenhofer'
collection: publications
permalink: /publications/vehicle_velocity_estimation
excerpt: 'This paper documents the winning entry at the CVPR2017 vehicle velocity estimation challenge.'
date: 2018-02-20
venue: 'Computer Vision Winter Workshop: 23rd Computer Vision Winter Workshop'
paperurl: 'https://arxiv.org/pdf/1802.07094'
award: Best Student Paper Award
citation: 
---
[[pdf]](https://arxiv.org/pdf/1802.07094)

![sample image]({{ site.baseurl }}/images/velocity_estimation_sample.png)
<br/><br/>
This paper documents the winning entry at the CVPR2017 vehicle velocity estimation challenge. Velocity estimation is an emerging task in autonomous driving which has not yet been thoroughly explored. The goal is to estimate the relative velocity of a specific vehicle from a sequence of images. In this paper, we present a light-weight approach for directly regressing vehicle velocities from their trajectories using a multilayer perceptron. Another contribution is an explorative study of features for monocular vehicle velocity estimation. We find that light-weight trajectory based features outperform depth and motion cues extracted from deep ConvNets, especially for far-distance predictions where current disparity and optical flow estimators are challenged significantly. Our light-weight approach is real-time capable on a single CPU and outperforms all competing entries in the velocity estimation challenge. On the test set, we report an average error of 1.12 m/s which is comparable to a (ground-truth) system that combines LiDAR and radar techniques to achieve an error of around 0.71 m/s. 


Bibtex:
```
@article{kampelmuhler2018camera,
  title={Camera-based vehicle velocity estimation from monocular video},
  author={Kampelm{\"u}hler, Moritz and M{\"u}ller, Michael G and Feichtenhofer, Christoph},
  journal={Computer Vision Winter Workshop: 23rd Computer Vision Winter Workshop},
  year={2018}
}
```
