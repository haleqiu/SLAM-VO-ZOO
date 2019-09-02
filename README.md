# SLAM/VO paper summary

This repo is the zoo for SLAM(Simultaneous localization and mapping) and VO. 

Thanks to the breakthrough in deep nerual net, many SLAM systems embrace CNN(convolution neural network) in their system. 
We also collect some papers about plane&object detection, depth pridiction and semantic segmentation.

## Monocular SLAM

* `CVPR2019` CodeSLAM — Learning a Compact, Optimisable Representation for Dense Visual SLAM [(link)](https://arxiv.org/pdf/1804.00874.pdf)
  `depth pridiction` `deep net`
  M Bloesch, J Czarnowski, R Clark, S Leutenegger, A J. Davison
  Imperial College London, UK

* `CVPR2019`An Efficient Schmidt-EKF for 3D Visual-Inertial SLAM [(link)](https://arxiv.org/abs/1903.08636)
  `indoor`
* `CVPR2017` CNN-SLAM: Real-time dense monocular SLAM with learned depth prediction [(link)](https://arxiv.org/abs/1704.03489) | [(github)](https://github.com/iitmcvg/CNN_SLAM) 
  `depth prediction` `deep net` `semantic segmentation`
  Keisuke Tateno, Federico Tombari, Iro Laina, Nassir Navab
  TU Munich
  * Estimating the absolute scale of the reconstruction. obtaining dense depths along texture-less regions and dealing with pure rotational motions
  * privileges depth prediction in image locations where monocular SLAM approaches tend to fail. 
  
* `ICRA2018`Constructing Category-Specific Models for Monocular Object-SLAM [(link)](https://ieeexplore.ieee.org/document/8460816)
  `CAD`
  
* `ICRA2018`A Monocular SLAM System Leveraging Structural Regularity in Manhattan World [(link)](https://ieeexplore.ieee.org/document/8463165)
  `camera pose estimation` `3D map` `man-made environments `

* `ICRA2018`ProSLAM: Graph SLAM from a Programmer's Perspective [(link)](https://arxiv.org/abs/1709.04377)
  `lightweight`
  
## Stereo SLAM

## Visual Odemeter(VO)

* `ICRA2018`Detection and Resolution of Motion Conflict in Visual Inertial Odometry
 [(link)](https://ieeexplore.ieee.org/document/8460870)
  `motion conflict`
  
* `ICRA2018`Direct Sparse Visual-Inertial Odometry Using Dynamic Marginalization[(link)](https://ieeexplore.ieee.org/document/8462905)
  `estimate camera pose` `estimate sparse scene geometry`
  
* `ICRA2018`Direct Line Guidance Odometry[(link)](https://ieeexplore.ieee.org/document/8461003)
  `Monocular` 
  
* `ICRA2018`Dense Planar-Inertial SLAM with Structural Constraints[(link)](https://ieeexplore.ieee.org/document/8461094)
  `DPI-SLAM` `large indoor` 
  
* `ICRA2018`Low-Drift Visual Odometry in Structured Environments by Decoupling Rotational and Translational Motion[(link)](https://ieeexplore.ieee.org/document/8463207)
  `low-drift`
  
* `ICRA2018`Relocalization, Global Optimization and Map Merging for Monocular Visual-Inertial SLAM[(link)](https://ieeexplore.ieee.org/document/8460780)
  `Monocular` 
  
* `ICRA2018`Towards Globally Consistent Visual-Inertial Collaborative SLAM[(link)](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8461213)
  `backend` `monocular-inertial odometry`
  
* `ICRA2018`A Benchmark Comparison of Monocular Visual-Inertial Odometry Algorithms for Flying Robots[(link)](https://ieeexplore.ieee.org/document/8460664)
  `evaluation` `VIO pipeline`
  
* `ICRA2018`Robust Stereo Visual Inertial Odometry for Fast Autonomous Flight[(link)](https://ieeexplore.ieee.org/document/8258858)
  `fast flight`
  
* `ICRA2018`UnDeepVO: Monocular Visual Odometry Through Unsupervised Deep Learning[(link)](https://ieeexplore.ieee.org/document/8461251)
  `depth` `Monocular` `deep neural networks` ``

# Related work

## 3D plane/object detection

* `CVPR2019` PlaneRCNN: 3D Plane Detection and Reconstruction from a Single Image [(link)](https://arxiv.org/abs/1812.04072) | [(github)](https://github.com/NVlabs/planercnn)
  `Plane detection` `Monocular` `3D`

* `CVPR2019` Stereo R-CNN based 3D Object Detection for Autonomous Driving [(link)](https://arxiv.org/abs/1902.09738) | [(github)](https://arxiv.org/abs/1902.09738) 
  `Object detection` `Stereo` `3D`

* `ICRA2018` Bayesian Scale Estimation for Monocular SLAM Based on Generic Object Detection for Correcting Scale Drift [(link)](https://ieeexplore.ieee.org/document/8461178) 
  `Object detection` `Monocular` `3D`

* `ICRA2018` Driven to Distraction: Self-Supervised Distractor Learning for Robust Monocular Visual Odometry in Urban Environments[(link)](https://ieeexplore.ieee.org/document/8460564) 
  `deep convolutional network` `Monocular` `driving`
  


## Depth and Ego motion estimation

* `CVPR2019` [Learning to Adapt for Stereo](https://arxiv.org/abs/1904.02957)  | [github](https://github.com/CVLAB-Unibo/Learning2AdaptForStereo)	
  Alessio Tonioni, Oscar Rahnama, Thomas Joy, Luigi Di Stefano, Thalaiyasingam Ajanthan, Philip H. S. Torr
  University of Oxford

* unsupervised adaptation to estimate depth.

## Auto-driving

# Datasets

* KITTI: [http://www.cvlibs.net/](http://www.cvlibs.net/)
  `outdoor` `driving` 
