---
title: "Object Detection in 3D Point Clouds via Local Correlation-Aware Point Embedding"
author: "<strong>C. Wu</strong>, J. Pfrommer, J. Beyerer, K. Li, B. Neubert"
collection: publications
category: conferences
permalink: /publication/2020-08-26-PointEmbedding
excerpt: ''
date: 2020-08-26
venue: '4th International Conference on Imaging, Vision & Pattern Recognition (IVPR)'
paperurl: 'https://arxiv.org/abs/2301.04613'
githuburl: 'https://github.com/stevenczwu/PointEmbedding'
---

Abstract: We present an improved approach for 3D object detection in point cloud data based on the Frustum PointNet (F-PointNet). Compared to the original F-PointNet, our newly proposed method considers the point neighborhood when computing point features. The newly introduced local neighborhood embedding operation mimics the convolutional operations in 2D neural networks. Thus features of each point are not only computed with the features of its own or of the whole point cloud but also computed especially with respect to the features of its neighbors. Experiments show that our proposed method achieves better performance than the F-Pointnet baseline on 3D object detection tasks.


If you are interested in this work, please cite as below:

```text
@inproceedings{wu2020object,
  title={Object detection in 3D point clouds via local correlation-aware point embedding},
  author={Wu, Chengzhi and Pfrommer, Julius and Beyerer, J{\"u}rgen and Li, Kangning and Neubert, Boris},
  booktitle={2020 Joint 9th International Conference on Informatics, Electronics \& Vision (ICIEV) and 2020 4th International Conference on Imaging, Vision \& Pattern Recognition (icIVPR)},
  pages={1--8},
  year={2020},
  organization={IEEE}
}
```
